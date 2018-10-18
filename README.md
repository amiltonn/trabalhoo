palavra = input('digite seu texto:')
tamanho=palavra.lower()

for x in set(palavra):
    b=palavra.count(x)
    print('o numero de vezes que', x ,'aparece é:',b)
