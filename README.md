 # Apresentação : 

print("*Calculadora Simples*")
print()
 
 # Variáveis e Estruturas : 

n1 = float(input("Digite o primeiro número: "))
n2 = float(input("Digite o segundo número: "))

print()
print("Escolha uma operação: ")
print("[1] Adição")
print("[2] Subtração")
print("[3] Multiplicação")
print("[4] Divisão")
print()

operacao = int(input("Digite a operação desejada: "))
loop = False
resultado = 0

while loop == False:
    if(operacao == 1):
        operacao = str(operacao)
        operacao = "Adição"
        resultado = n1 + n2
        loop = True
    elif(operacao == 2):
        operacao = str(operacao)
        operacao = "Subtração"
        resultado = n1 - n2
        loop = True
    elif(operacao == 3):
        operacao = str(operacao)
        operacao = "Multiplicação"
        resultado = n1 * n2
        loop = True
    elif(operacao == 4):
        operacao = str(operacao)
        operacao = "Divisão"
        resultado = n1 / n2
        loop = True
    else:
        print("Erro, Verifique as Suas Respostas e Tente Novamente.")
print("Operação  : {}".format(operacao))
print("Resultado : {}".format(resultado))
