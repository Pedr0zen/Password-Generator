import random
import string
print('---Gerado_De_Senhas---')
#variaveis
Lista = []
letras = ['a,b,c,d,e,f,g,h,i,j,k,m,n,o,p,q,r,s,t,u,v,w,x,y,z'] #lista de strings
numeros = [1,2,4,5,6,7,8,9,0] #lista de numeros
tipo_str = 1 #menu de escolhas
tipo_int = 2
misturado = 3
try:
 qtd_caracteres = int(input('quantos caracteres/numeros voce deseja que sua senha tenha?'))
except ValueError:
    print('Somente numeros')
print('|[1]string|-[2]inteiro|-[3] misturado|')
escolha = int(input('voce deseja que a senha seja somente com numeros ou so letras ou ate mesmo misturado?'))
random_string = ''.join (random.choices(string.ascii_letters, k = qtd_caracteres)) #senha com string
if escolha==1:
    print(random_string)
elif escolha==3:
    random_misturado = ''.join (random.choices(string.ascii_letters + string.digits, k = qtd_caracteres)) #senha com numeros e strings
    print(random_misturado)
else:
    random_int = ''.join (random.choices(string.digits, k= qtd_caracteres))
    print(random_int)
