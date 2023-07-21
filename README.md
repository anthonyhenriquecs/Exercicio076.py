# Exercicio076.py

listagem = (
    'lapis', 1.75,
    'caneta', 2,
    'estojo',25,
    'transferidor', 4.20,)
print('-'*40)
print(f'{"LISTAGEM DE PREÇO":^40}')
print('-'*30)
for i in range(0, len(listagem)):
    if i % 2 == 0:
        print(f'{listagem[i]:.<30}',end='')
    else:
        print(f'R${listagem[i]:>5.2f}')
print('-'*30)
