# codigo_python_reverseList
Código em python de um programa que receba o nome de uma pessoa e imprima ele invertido em uma string formatada

nome = input('Informe seu nome: ')

lista = []
for i in nome:
    lista.append(i)
print(lista)

lista.reverse()
print(lista)

nome_inv = ''
for i in lista:
    nome_inv = nome_inv + i
    #print(nome_inv)
print(nome_inv)

