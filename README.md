frase = input('digite seu texto:')
frase = frase.lower()
tamanho=len(frase)
for x in set(frase):
    b = frase.count(x)
    c =((1 - (b /tamanho)) * 100)
    print('o numero de vezes que', x ,'aparece é:',b,'sua porcentagem é',c)
