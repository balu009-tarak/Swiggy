order=[]
prize=[]
bill=0
print("welcome")
print("here is the menu please select ur order:")
menu={
    1:['dosa',40],
    2:['Edli',40],
    3:['Vada',50],
    4:['Chapathi',70],
    5:['Puri',40],
    6:['Icecream',80],
    7:['Chicken',90]
}
print(menu)
a=int(input("enter order number:"))
order.append(menu[a][0])
prize.append(menu[a][1])
print("ur orders are:")
print(order)
print(prize)
c=str(input("any extra orders:"))
def extraorder():
    b = int(input("enter order number:"))
    order.append(menu[b][0])
    prize.append(menu[b][1])
    print("ur orders are:", order)
    print("prizes of orders:",prize)

if (c=="yes"):
        extraorder()
else:
    print("ur orders are:",order)
d=input("any other order:")
if d=="yes":
    extraorder()
else:
    print("ur orders are:",order)
    print("prizes of orders:",prize)
for i in range(len(prize)):
    bill=bill+prize[i]
    i+=1
print(bill)
