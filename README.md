# CalculadoraV-TRABALHO
Calculadora em phyton que faz as 4 operações básicas

# Calculadora simples

num1 = float(input("Digite o primeiro número: "))
num2 = float(input("Digite o segundo número: "))

print("Operações:")
print("1: Adição")
print("2: Subtração")
print("3: Multiplicação")
print("4: Divisão")

operacao = input("Escolha uma operação: ")

if operacao == "1":
    resultado = num1 + num2
    print("Resultado:", resultado)

elif operacao == "2":
    resultado = num1 - num2
    print("Resultado:", resultado)

elif operacao == "3":
    resultado = num1 * num2
    print("Resultado:", resultado)

elif operacao == "4":
    if num2 != 0:
        resultado = num1 / num2
        print("Resultado:", resultado)
    else:
        print("Erro: divisão por zero não é permitida.")

else:
    print("Operação inválida.")
