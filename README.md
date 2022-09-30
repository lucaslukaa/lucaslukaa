- 👋 Hi, I’m @lucaslukaa
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
lucaslukaa/lucaslukaa is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
name = "Lucas"
age = "10"
salary = "2000"
print(name, age, salary)
print(1 + 1)

a = 10
b = 10
c = 10
# ao inves que fazer uma linha pra cada posso usar o de baixo
a = b = c = 10
x = 20
y = 30
z = 40
x, y, z = 20, 30, 40

print(y, a)

j = 20
J = 10
print(j)
print(J)

name1 = "Lucas"
name2 = "Luka"

multiline = '''stri1
stri2
stri3
'''
print(multiline)

# boolean literals = true and false
# numeric literals = int (sem virgula), long (número completo), float (numero com virgula)

# arithmetic operator = takes two operand to perferom operation on them
# example  +, -, *, /, %

# assignment operator = assign a value to a variable
# example   =, +=, -=, *=
var1 = 10
var1 += 10  # it's mean var = var+10
print(var1)
var1 -= 10
print(var1)

# comparison operator = <, >, <=, >=, !=
k = 10
l = 9
sera = k <= l
print(sera)

#logic operator = performs logical operation and return true or false as output
#example = and, or, not

m = 10<10 and 2>-1 #false and true = false
print(m)

#used to performer bitwise calculation
#example = &, | , >>, <<, ~
v = 7|5
p = 7&5
y = 10>>2 # 10: 1010 10>>2 = 0010
r = 10<<2 # = 101000
e = 10<<3 # = 1010000
print(v)
print(p)
print(y)
print(r)
print(e)

#identity operator = test if the two operands share an identity
#example =  is, is not
zz = int(10)
aa = zz == 10 # ou pode usar "zz is 10"
print(aa)
aa = zz != 10 # ou pode usar "zz is not 10"
print(aa)

#membership operator = test whether a value is a member of a sequence
#example = in, not in
bb = ['dog','cat','wolf']
cc = 'lion' in bb # tem que dar false
print(cc)
cc = 'wolf' in bb # tem que dar true
print(cc)
cc = 'me' in 'appointment' #vai pesquiser o "me" na palavra "appointMEnt"
print(cc)
