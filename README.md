# kalkulyator
print('ikki son ustida 4ta arifmetik ammallar bajarish dasturi')
n="son kiriting:"
a="amal kiriting:"
m="ikkinchi son kiriting:"

y="amal kiriting:"

while True:
    son=input(n)
    amal=input(a)
    son1=input(m)
    amal1=input(y)
    if   amal1=='clear':
         print('yechimi',end="")

    elif amal=='+':
        qiymat3=int(son)+int(son1)
        print(qiymat3)
    elif amal=='-':
        qiymat2=int(son)-int(son1)
        print(qiymat2)
    elif amal=='*':
        qiymat1=int(son)*int(son1)
        print(qiymat1)
    elif amal=='/':
        qiymat=int(son)/int(son1)
        print(qiymat)
    else:
        break
