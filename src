def calculadora():
    """
    Calculadora simples que realiza operações básicas entre dois números.

    A calculadora suporta as operações de adição, subtração, multiplicação e divisão.
    O usuário pode digitar 'sair' para encerrar o programa.
    """
    while True:
        # Solicita o primeiro número ao usuário
        num1 = input("Digite o primeiro número (ou 'sair' para finalizar): ")
        if num1.lower() == "sair":
            print("Encerrando a calculadora.")
            break

        try:
            num1 = float(num1)  # Converte o número de entrada para float
        except ValueError:
            print("Entrada inválida. Por favor, digite um número válido.")
            continue

        # Solicita a operação ao usuário
        operacao = input("Digite a operação (+, -, *, /): ")

        # Solicita o segundo número ao usuário
        num2 = input("Digite o segundo número: ")
        try:
            num2 = float(num2)  # Converte o número de entrada para float
        except ValueError:
            print("Entrada inválida. Por favor, digite um número válido.")
            continue

        # Realiza a operação selecionada
        if operacao == "+":
            resultado = num1 + num2
        elif operacao == "-":
            resultado = num1 - num2
        elif operacao == "*":
            resultado = num1 * num2
        elif operacao == "/":
            if num2 == 0:
                print("Erro: Divisão por zero não é permitida.")
                continue
            resultado = num1 / num2
        else:
            print("Operação inválida.")
            continue

        # Mostra o resultado com um erro proposital
        resultado_com_erro = resultado + 3
        print("Resultado (com erro):", resultado_com_erro)

if __name__ == "__main__":
    calculadora()
