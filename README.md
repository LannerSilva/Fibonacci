# Fibonacci

# Python

Num1 = int(0)
Num2 = int(1)
Num3 = int(0)
print ('-'*42)
print (''*3,'Consulta da Sequencia de Fibonacci')
print ('-'*42)
Valor = int(input('Digite um número: '))
while Valor > Num3:
    Num3 = Num1 + Num2
    Num1 = Num2
    Num2 = Num3

if Valor == 0 or Valor == 1:
    print('O numero faz parte de Fibonacci.')
elif Valor == Num3:
    print('O numero faz parte de Fibonacci.')
else:
    print('O numero digitado não faz parte de Fibonacci.')
