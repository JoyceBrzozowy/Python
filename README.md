
```diff

- Python Mundo 1


- Tipos primitivos


- Tipo string
n1 = input('Digite um valor: ')
print(type(n1))

- Tipo float 
n3 = (float(input('Digite um valor: ')))
print(type(n3))

- Tipo boleano
n4 = (bool(input('Brasil é hexa? ')))
print(type(n4)) 

- Concatenar juntar strings

n1 = (input('Digite um valor: '))
n2 = (input('Digite outro valor: '))
s= n1 + n2
print('A soma vale', s)

- Soma de valores inteiros

n1 = int(input('Digite um valor: '))
n2 = int(input('Digite outro valor: '))
s= n1 + n2
print('A soma vale', s)


- Digite função numerico
n = input('Digite algo: ')
print(n.isnumeric())

- Digite função alfanuméricos
n = input('Digite algo: ')
print(n.isalnum())

- Digite função alfabetico
n = input('Digite algo: ')
print(n.isalpha())

- Digite função letras maiusculas
n = input('Digite algo: ')
print(n.isupper())

- Operadores aritiméticas

### Exercicío 03  Ordem de precedencia 1º (), 2º **, 3º * / // %, 4º + -,

5+3*2
4*2+1
3*5+4**2


- Exercicío 04 Operadores Aritméticos -operações aritméticas
n1 =int(input('Digite um valor:'))
n2 = int(input('Outro valor:'))
s = n1 + n2
m = n1 * n2
d = n1 / n2
di = n1 // n2
e = n1 ** n2
print('A soma é {}, \n o produto é {} e a \n divisão é {:.3f}'.format(s, m , d),  end=' ')
print( 'Divisão inteira {} e potência {}'.format(di, e))


- Exercicío 05 Antecessor e Sucessor
Outra opção - print('Analisando o valor {}, seu antecessor é {} e o sucessor é {}' .format(n, (n-1), (n+1)))
n = int(input('Digite um número:'))
a = n - 1
s = n + 1
print('Analisando o valor {}, seu antecessor é {} e o sucessor é {}'.format(n, a, s))

- Exercicío 06 Dobro, triplo, raiz quadrada
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


- Exercicío 07 Média Aritmética
Ex 1 ponto flutuante: print('A média entre {:.1f} e {:.1f} é igual {:.1f}'.format(n1, n2, m)) 
n1 = float(input('Primeira nota do aluno:'))
n2 = float(input('Segunda nota do aluno:'))
m = (n1 + n2) / 2
print('A média entre {} e {} é igual {}'.format(n1, n2, m))

- Exercicío 08 Conversor de Medidas
medida = float(input('Uma distância em metro:'))
cm = medida * 100
mm = medida * 1000
print('A medida de {}m corresponde a {:.0f}cm e {:.0f}mm'.format(medida, cm, mm))


- Exercicío 09 Tabuada
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


- Exercicío 10 Conversor de Moedas
real = float(input('Quanto dinheiro você tem na carteira?R$'))
dolar = real / 3.27
print('Com R${:.2f}  você pode comprar U$${:.2f}' .format(real, dolar))


- Exercicío 11 Pintando Parede
larg = float(input('Largura da parede'))
alt = float(input('Altura da parede:'))
área = larg * alt
print('Sua parede tem a dimensão de {}x{} e sua área é de {}m².'.format(larg, alt, área))
tinta = área/ 2
print(' Para pintar essa parede, você precisará de {}l de tinta.'.format(tinta))


- Exercício 12 – Calculando Descontos
#10*5/100
#1500*10/100
#875*15/100
preço = float(input('Qual é o preço do produto? R$'))
novo = preço - (preço * 5/ 100)
print('O produto que custava R${}, na promoção com desconto de 5% vai custar R${}' .format(preço, novo))

-  Exercício 13 – Reajuste Salarial
salário = float(input('Qual é o salário do Funcionário? R$'))
novo = salário + (salário * 15/100)
print('Um funcionário que ganhava R${:.2f}, com 15% de aumento passa a receber R${:.2f}'.format(salário, novo))

- Exercício 14 – Conversor de Temperaturas
c = float(input('Informe a temperatura em °C:'))
f = ((9*c)/5)+32
print('A temperatura de {0}°C corresponde a {1}°F!'.format(c, f))

- Exercício 15 – Aluguel de Carros
dias = int(input('Quantos dias alugados?'))
km = float(input('Quantos km rodados?'))
pago = (dias * 60) + (km * 0.15)
print('O total a pagar é de R${:.2f}'.format(pago))

- antes dos : condicao
print(20*'-')
a= int(input(''))
if a==0:
  print('ele é louco')
elif a==1:
  print('ele não é maluco')
else:
  print('ele nao é louco nem maluco')
print(20*'-')

- um colchete uma lista com [[]] estarei chamando lista dentro de lista

 append adiciona valores dentro da lista

a = [[1, 2, 3, 4, 5]]

b = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

# adicionado lista b dentro da a

a.append(b)

# com print (a) essa lista contem a lista b

#print(a)

# chamando elemento dentro da lista

a[1][9]


- Utilizando Módulos
#ceil faz arredondamento para cima
#floor fazer arredondamento para baixo
#trunc truncar, elmina da vírgula para frente
#pow que é power = potência, funciona semelhante aos 2**
#sqrt para calcuar a raiz quadrada = square quadrada
#factorial 
# se fizer o comando import math, ele pode utilizar qualquer uma das funcionalidades acima
#se for utlizar um cálculo de raiz quadrada >> from>>math>>import>>sqrt
#>> from>>math>>import>>sqrt,ceil
import math
num = int(input('Digite um número:'))
raiz = math.sqrt(num)
print('A raiz de {} é igual a {}'.format(num, raiz))


-Quebrando um número - quando for dig um num colocar ponto por ex: 6.145
from math import trunc
num = float(input('Digite um valor:'))
print('O valor digitado foi {} e a sua porção inteira é {}'.format(num, trunc(num)))


-Catetos e Hipotenusa
co = float(input('Comprimento do cateto oposto:'))
ca = float(input('Comprimento do cateto adjacente:'))
hi = (co ** 2 + ca **2) ** (1/2)
print('A hipotenusa vai medir {}'.format(hi))


-Seno, Cosseno e Tangente
import math
ângulo = float(input('Digite o ângulo que você deseja:'))
seno = math.sin(math.radians(ângulo))
print('O ângulo de {} tem o Seno de {:.2f}'.format(ângulo, seno))
cosseno = math.cos(math.radians(ângulo))
print('O ângulo de {} tem o cosseno de {:.2f}'.format(ângulo, cosseno))
tangente = math.tan(math.radians(ângulo))
print('O ângulo de {} tem a Tangente de {:.2f}' .format(ângulo, tangente))

-Tocando um MP3 (install packge game)pycharm
import pygame
pygame.int()
pygame.mixer.music.load('nome do arquivo que você salvou')
pygame.mixer.music.play()
paygame.event.wait()
#executar e a música começa tocar/ obs: tentar procurar no colab opção de instalar 

-Manipulando Texto - fatiamento
frase = 'Curso em vídeo'
print(frase[0:14])
print('Oi')

-Analisador de Textos
nome= str(input('Digite seu nome completo: ')).strip()
print('Analisando seu nome...')
print('Seu nome em maiúsculas é {}'.format(nome.upper()))
print('Seu nome em minúsculas é {}'.format(nome.lower()))
print('Seu nome tem ao todo {} letras'.format(len(nome)))
print('Seu primeiro nome tem {} letras'.format(nome.find(' ')))
separa = nome.split()
print('Seu primeiro nome é {} e ele tem {} letras'.format(separa [0], len(separa[0])))


-Separando dígitos de um número
num = int(input('Informe um número:'))
u = num // 1
print('Analisando o número {}'.format(num))
print('Dezena: {}'.format())
print('Centena: {}'.format())
print('Milhar: {}'.format())

-Verificando as primeiras letras de um texto
cid = str(input('Em que cidade você nasceu? ' )).strip()
print(cid[:5].upper() ==  'SANTO')

!Estrutura de loop FOR  -- UDEMY
for QualquercoisaqueQuiser in range(10):
  print(QualquercoisaqueQuiser)

!Laço FOR2 --UDEMY
Lista = ['Brasil', 'Argentina', 'Uruguai', 'Paraguai'] 
for QualquercoisaqueQuiser in Lista:
  print( QualquercoisaqueQuiser )

  #Loop While --- UDEMY - é usado para executar um bloco de instruções repetidamente até que uma determinada condição seja satisfeita.
#looping infinito
Parar = 0
while Parar <= 10:
  print( Parar )
  Parar += 1


!Loop while 2 ---UDEMY
# Joguinho

while True:

Eu = random.randint(0, 10)
Contra_Voces = random.randint(0, 10)
print ('Eu tirei o valor', Eu )
print ('E voces tiraram o', Contra_Voces)

 if Eu > Contra_Voces:
   print( 'Ganhei !!!!' )
   break
   print('\n')

   #Procurando uma string dentro de outra
nome = str(input('Qual é seu nome completo? ' )) .strip()
print('Seu nome tem Silva? {}'.format('Silva' in nome))

-Primeira e última ocorrência de uma string
#não colocar muitos espaços pois interfere no resultado
frase = str(input('Digite uma frase: ')).upper()
print('A letra A aparece {} vezes na frase'.format(frase.count('A')))
print('A primeira letra A apareceu na posição {}'.format(frase.find ('A')+ 1))
print('A última letra A apareceu na posição {}'.format(frase.rfind('A')+1))

-Primeiro e último nome de uma pessoa
n = str(input('Digite seu nome completo: ')).strip()
nome = n.split()
print('Muito prazer em te conhecer!')
print('Seu primeiro nome é {}'.format(nome [0]))
print('Seu último nome é {}'.format(nome[len(nome)-1]))

-Condições em Python (if..else)
n1 = float(input('Digite a primeira nota:'))
n2 = float(input('Digite a segunda nota:'))
m = (n1 + n2)/2
print('A sua média foi {:1}'.format(m))
print('PARABÉNS' if m >= 6 else 'ESTUDE MAIS!')

-Jogo da Adivinhação v.1.0
from random import randint
computador = randint(0, 5) # Faz o computador "PENSAR"
print('-=-' * 20)
print('Vou pensar em um número entre o 0 e 5. Tente adivinhar...')
print('-=-' * 20)
jogador = int(input('Em que número eu pensei?')) #Jogador tenta adivinhar
if jogador == computador:
  print('PARABÉNS! Você conseguiu me vencer!')
else:
    print('GANHEI! Eu pensei no número {} e não no {}!'.format(computador, jogador))

-Radar eletrônico
velocidade = float(input('Qual é a velociodade atual do carro? '))
if velocidade > 80:
  print('MULTADO! Você excedeu o limite permitido que é de 80KM/h')
  multa = (velocidade - 80) * 7
  print('Você deve pagar uma multa de R${:.2f}!'.format(multa))
  print('Tenha um ótimo dia!Dirija com segurança!')







