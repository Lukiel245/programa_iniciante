#programa iniciante adivinhar numero que o computadoir pensou
from random import randint
computador =  randint (0 ,5) 
print('-' * 50)
print('teste de adivinhar, vamos ver se acerta.')
print('vou pensar num numero de 0 a 5 tente adivinhar.')
print('-' * 50)
jogador = int (input ('digite um valor de 0 a 5:'))
if jogador == computador:
    print('parabens voce acertou o numero.')
else:
    print(f'voce errou, eu pensei numero {computador} e nao o {jogador}. ')
