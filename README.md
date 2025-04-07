# calculadora em phyton 

print('CALCULADORA SIMPLES')
print('Operações disponíveis: Adição, Subtração, Multiplicação e Divisão')
print('-------------------------------------------------------------------')

n1 = int(input('Digite o primeiro número: '))
n2 = int(input('Digite o segundo número: '))
operador = input('1-adicao\n2-Subtração\n3-Multiplicação\n4-Divisão')

if operador == '1':
  resultado = n1 + n2

elif operador == '2':
  resultado = n1 - n2

elif operador == '3':
  resultado = n1 * n2

elif operador == '4':
  resultado = n1 / n2



print(f'O resultado da operação entre {n1} e {n2} é:', resultado)
