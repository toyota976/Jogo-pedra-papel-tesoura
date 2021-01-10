from random import randint
from time import sleep
itens = ('Pedra', 'Papel', 'Tesoura')
pc = randint(0, 2)
print('''* * * * * * * * * 
[ 0 ] \033[37mPedra\033[m     *
[ 1 ] \033[34mPapel\033[m     *
[ 2 ] \033[35mTesoura\033[m   *
* * * * * * * * *''')
opção = int(input('Qual a sua opção?'))
print('Jo')
sleep(1)
print('Ken')
sleep(1)
print('Pô!!!!')
print('-='*15)
print(f'''O computador jogou {itens[pc]}
Você jogou {itens[opção]}''')
print('-='*15)
if pc == 0:
    if opção == 0:     # computador jogou pedra
        print('\033[33mEmpate\033[m')
    elif opção == 1:
        print('\033[34mO jogador ganhou\033[m')
    elif opção == 2:
        print('\033[31mO jogador perdeu\033[m')
    else:
        print('Opção invalida')
elif pc == 1:          # computador jogou papel
    if opção == 0:
        print('\033[31mO jogador perdeu\033[m')
    elif opção == 1:
        print('\033[33mEmpate\033[m')
    elif opção == 2:
        print('\033[34mO jogador ganhou\033[m')
    else:
        print('Opção invalida')
elif pc == 2:          # computador jogou tesoura
    if opção == 0:
        print('\033[34mO jogador ganhou\033[m')
    elif opção == 1:
        print('\033[31mO jogador perdeu\033[m')
    elif opção == 2:
        print('\033[33mEmpate\033[m')
    else:
        print('Opção invalida')
