# trabalhoo
frase = input('digite seu texto:')
frase=frase.lower()
x=frase.count('a')
print('o numero de vezes que a aparece é:',x)
tamanho=len(frase)
z=int(x*100/tamanho)
print('a porcentagem é:{}%'.format(z))
x=frase.count('b')
print('o numero de vezes que b aparece é:',x)
tamanho=len(frase)
z=int(x*100/tamanho)
print('a porcentagem é:{}%'.format(z))
x=frase.count('c')
print('o numero de vezes que c aparece é:',x)
tamanho=len(frase)
z=int(x*100/tamanho)
print('a porcentagem é:{}%'.format(z))




palavra = input('digite seu texto:')
tamanho=palavra.lower()
print({p:palavra.count(p)for p in set(palavra)})

