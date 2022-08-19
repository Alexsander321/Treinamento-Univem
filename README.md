N=int(input("Quantos candidatos tem: "))
a=0
b=0
c=0

for i in range(N):
    voto=str(input("A-votar para a B-votar para B C-votar para C: "))[0].upper()
    if voto=="A":
        a+=1
    elif voto=="B":
        b+=1
    elif voto=="C":
        c+=1




if a>b and a>c:
    print("A vencedor")
elif b>a and b>c:
    print("B vencedor")
elif c>a and c>b:
    print("C vencedor")
else:
    print("empate")

