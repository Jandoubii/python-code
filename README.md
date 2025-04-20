# python-code
from numpy import*
def saisir ():
    global n
    n=int(input("donner un entier"))
    while not (2<n and n<20):
        n=int(input("donner un entier"))
def remplir(t,n):
    for i in range(n):
        t[i]=input("donner une chaine")
        while not verif(t[i])== true and len(t[i])>i:
            t[i]=input("donner une chaine")
def verif ():
    i=0
    while i<=len(ch)-1 and (ch[i]).upper()>="A" and (ch[i]).upper()<="Z":
        i=i+1
    return i>len(ch)-1
def afiicher():
    for i in range(n):
        print(t[i][0:i+1])
saisir()
t=array([str]*n)
remplir(t,n)
afficher(t,n)
