# Python
Trilha de estudos para Python

## Tipos primitivos

### Tipo string
n1 = input('Digite um valor: ')
print(type(n1))

### Tipo float 
n3 = (float(input('Digite um valor: ')))
print(type(n3))

### Tipo boleano
n4 = (bool(input('Brasil é hexa? ')))
print(type(n4)) 

### Concatenar juntar strings

n1 = (input('Digite um valor: '))
n2 = (input('Digite outro valor: '))
s= n1 + n2
print('A soma vale', s)

### Soma de valores inteiros

n1 = int(input('Digite um valor: '))
n2 = int(input('Digite outro valor: '))
s= n1 + n2
print('A soma vale', s)


### Digite função numerico
n = input('Digite algo: ')
print(n.isnumeric())

### Digite função alfanuméricos
n = input('Digite algo: ')
print(n.isalnum())

### Digite função alfabetico
n = input('Digite algo: ')
print(n.isalpha())

### Digite função letras maiusculas
n = input('Digite algo: ')
print(n.isupper())

# Operadores aritiméticas

### Exercicío 03  Ordem de precedencia 1º (), 2º **, 3º * / // %, 4º + -,

5+3*2
4*2+1
3*5+4**2


### Exercicío 04 Operadores Aritméticos -operações aritméticas
n1 =int(input('Digite um valor:'))
n2 = int(input('Outro valor:'))
s = n1 + n2
m = n1 * n2
d = n1 / n2
di = n1 // n2
e = n1 ** n2
print('A soma é {}, \n o produto é {} e a \n divisão é {:.3f}'.format(s, m , d),  end=' ')
print( 'Divisão inteira {} e potência {}'.format(di, e))



### Exercicío 05 Antecessor e Sucessor
Outra opção - print('Analisando o valor {}, seu antecessor é {} e o sucessor é {}' .format(n, (n-1), (n+1)))
n = int(input('Digite um número:'))
a = n - 1
s = n + 1
print('Analisando o valor {}, seu antecessor é {} e o sucessor é {}'.format(n, a, s))

### Exercicío 06 Dobro, triplo, raiz quadrada
n = int(input('Digite um número:'))
Outra opção print ('O dobro de {} vale {}.' .format(n, (n+2)))
print ('O triplo de {}.\nA raiz quadrada de {} é igual a {:.2f}.'.format(n, (n+3), n (n**(1/2))))
print ('O triplo de {}.\nA raiz quadrada de {} é igual a {:.2f}.'.format(n, (n+3), pow (n, (1/2))))
n = int(input('Digite um número:'))
d = n * 2
t = n * 3
r= n** (1/2)
print('O dobro de {} vale {}'.format(n, d))
print('O triplo de {} vale {}. \nA raiz quadrada de {} é igual a {:.2f}.'.format(n, t, n, r))


### Exercicío 07 Média Aritmética
Ex 1 ponto flutuante: print('A média entre {:.1f} e {:.1f} é igual {:.1f}'.format(n1, n2, m)) 
n1 = float(input('Primeira nota do aluno:'))
n2 = float(input('Segunda nota do aluno:'))
m = (n1 + n2) / 2
print('A média entre {} e {} é igual {}'.format(n1, n2, m))

### Exercicío 08 Conversor de Medidas
medida = float(input('Uma distância em metro:'))
cm = medida * 100
mm = medida * 1000
print('A medida de {}m corresponde a {:.0f}cm e {:.0f}mm'.format(medida, cm, mm))


### Exercicío 09 Tabuada
num = int(input('Digite um número para ver sua tabuada:'))
print('-' * 12)
print('{} x {:2} = {}'.format(num, 1, num*1))
print('{} x {:2} = {}'.format(num, 2, num*2))
print('{} x {:2} = {}'.format(num, 3, num*3))
print('{} x {:2} = {}'.format(num, 4, num*4))
print('{} x {:2} = {}'.format(num, 5, num*5))
print('{} x {:2} = {}'.format(num, 6, num*6))
print('{} x {:2} = {}'.format(num, 7, num*7))
print('{} x {:2} = {}'.format(num, 8, num*8))
print('{} x {:2} = {}'.format(num, 9, num*9))
print('{} x {:2} = {}'.format(num, 10, num*10))
print('-' * 12)


### Exercicío 10 Conversor de Moedas
real = float(input('Quanto dinheiro você tem na carteira?R$'))
dolar = real / 3.27
print('Com R${:.2f}  você pode comprar U$${:.2f}' .format(real, dolar))


### Exercicío 11 Pintando Parede
larg = float(input('Largura da parede'))
alt = float(input('Altura da parede:'))
área = larg * alt
print('Sua parede tem a dimensão de {}x{} e sua área é de {}m².'.format(larg, alt, área))
tinta = área/ 2
print(' Para pintar essa parede, você precisará de {}l de tinta.'.format(tinta))


### Exercício 12 – Calculando Descontos
#10*5/100
#1500*10/100
#875*15/100
preço = float(input('Qual é o preço do produto? R$'))
novo = preço - (preço * 5/ 100)
print('O produto que custava R${}, na promoção com desconto de 5% vai custar R${}' .format(preço, novo))

###  Exercício 13 – Reajuste Salarial
salário = float(input('Qual é o salário do Funcionário? R$'))
novo = salário + (salário * 15/100)
print('Um funcionário que ganhava R${:.2f}, com 15% de aumento passa a receber R${:.2f}'.format(salário, novo))

### Exercício 14 – Conversor de Temperaturas
c = float(input('Informe a temperatura em °C:'))
f = ((9*c)/5)+32
print('A temperatura de {0}°C corresponde a {1}°F!'.format(c, f))

### Exercício 15 – Aluguel de Carros
dias = int(input('Quantos dias alugados?'))
km = float(input('Quantos km rodados?'))
pago = (dias * 60) + (km * 0.15)
print('O total a pagar é de R${:.2f}'.format(pago))




