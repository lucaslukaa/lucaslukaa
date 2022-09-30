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

# python datatype
# immutable (cannot be change) → numbers, strings, tuples
# mutable (can be change) → dictionaries, lists, sets

# numbers
'a = 10'
'name = "Jill"'
'salary = 2000.23'
'print(type(a))'  # tag "int"
'print(type(name))'  # tag "str"
'print(type(salary))'  # tag "float

# strings
str1 = "Hello-World"  # 0,1,2,3,4,5,6,7,8,9,10
str2 = "Estudando"  # 0,1,2,3,4,5,6,7,8,9
print(str1[0])  # show the first letter "H"
print(str2[-1])  # show the last letter "O"
print(str1[0:5])  # extract "hello" from "hello-world"
print(str2[4:9])  # extract "dando" from "estudando"

str = "attachment"
a = str.find("me")  # returns the position of the string
print(a)
c = str.replace("me", "m")  # replaces one characte/string with other
print(c)
b = str.replace("ment", "  ")
print(b)

splitsrt = "word1, word2, word3"
d = splitsrt.split(",")  # creates a split on the basis of a character
print(d)

str4 = "Intellipaat"
e = str4.count("I")  # returns the count of the character in the string
print(e)

str5 = "Intellipaat".upper()  # upper pra deixar tudo em letra maiuscula
print(str5)

print("Maximum of 4, 12, 15, 20, 21.2, 100 is : ", end='')
print(max(4, 12, 16, 20, 21.2, 100))  # return the max or min value (ASCIII)
# or
str6 = "!@134AabB"
print(max(str6))

    # Tuple → tuple are a group of values within ()

mytuple = ('a', 'b', 'c', 'd',)
mytuple1 = ('e', 'f')
g= mytuple + mytuple1 #concatenation → connecting tuples
print(g)

h = mytuple*2 #repetition → vai mostrar a tuple por quantas vezes eu colocar
print(h)

j = mytuple[2] #indexing → shows the indexed character/string
print(j)

k = mytuple[1:4] #slicing → shows a specific set of indexed
print(k)



# python datatype
# mutable (can be change) → dictionaries, lists, sets

# lists  are a group of values within []
mylist = ["a", 10, 7.12, "data"]
mylist1 = ["Python", 20]
a = mylist + mylist1  # concatenation - adiciona uma lista na outra
print(a)

b = a * 2  # repetation - multiplica a lista pela quantidade que indicar
print(b)

c = mylist[1:4]  # slicing - mostrar o que está entre o intervalo mostrado
print(c)

mylist.append("10")  # adiciona algo na lista
print(mylist)

mylist2 = ['c', 'd', 'e', 'f']
mylist.extend(mylist2)  # extend = estende a lista com a variavel colocada
print(mylist)

mylist.insert(1,
              30)  # insert - vai inserir o desejado na posição desejada .insert (x, y) x = posição y= o que vai ser inserido
print(mylist)

# DICTIONARIES are a group of values within {}

mydict = {1: "Lucas", 2: "Teste", 3: "Estudando"}  # 1 = key "lucas" = value, para mostrarmos lucas usaremos a chave 1
print(mydict[1])

mydict2 = {"name": "Lucas", 1: [2, 3, 4, 5]}  # mixed keys, diferentes tipos de chaves
print(mydict2['name'])  # usei a chave "name" para mostrar o value "lucas"

mydict3 = dict([(1, 'apple'), (2, 'ball')])  # paring = não entendi ainda PESQUISAR DEPOIS
print(mydict3[1])

print(len(mydict))  # len = vai mostrar quantos elementos tem no meu dicionário

print(mydict.keys())  # vai mostrar quais são as chaves do dicionário

print(mydict.values())  # vai mostrar quais os values do dicionário

# SETS
# unordered collection of items within {}
myset = {1, 2, 3, "Z"}  # a diferença entre ‘set’ e dicionário é de que o ‘set’ não vai ter nenhuma chave
print(myset)

myset2 = {1, 5, 3, "Z"}
print(myset | myset2)  # Union = | usado para unir os sets

print(myset & myset2)  # Intersection = & usado para achar o elemento comum entre os sets

print(myset - myset2)  # vai subtrair os iguais e manter os itens restantes do primeiro nesse caso o "myset"


# Flow control

# FOR

fruits = ['apple', 'banana', 'cherry']
for x in fruits:  # "x" uma variavel genérica que vai rodar tudo que está no value "fruits"
    print(x)
    if x == 'banana':  # quando "X" variavel genérica, for igual a "banana" vai parar
        break

# WHILE (condidition is true):
a = 1
while a <= 5:
    print(a)
    a += 2  # toda vez que fizer o ciclo vai somar +2 no valor total, na primeira vez vai ser 1, na proxima vai ser
    # 1+2, na proxima 3+2 e aqui vai parar pq só vai mostrar WHILE "a" for menor que 5
a = 1
while a <= 3:  # enquanto a for menor que 3

    if a % 2 == 0:  # se a dividido por 2 sobrar 0
        print(a, "is even")  # então mostrar "a is even", que quer dizer" a é par"
    else:  # se não resultar em 2 a divisão
        print(a, "is odd")  # mostrar "a, is odd", que quer dizer "a é impar"
    a += 1  # toda vez que fizer o ciclo vai somar +1 no valor de a total

# BREAK - stop a condition

b = 10
while b > 0:  # enquanto "b" for maior que "0"
    b -= 1
    if b != 5:  # enquanto não for igual a "5" mostrar "b"
        print(b)
    else:  # se "b" for igual a "5" então para
        break

# CONTINUE - unbreak the loop
c = 10
while c > 0:  # enquanto "c" for maior que "0'
    c -= 1  # diminui 1 a cada loop
    if c != 3:  # enquanto não for igual a "3" mostrar "c"
        print(c)
    else:  # vai pular o 3 em algum momento e para não parar é só usar isso
        continue


# FUNCTIONS are a block of organized, reusable sets of instructions that is used to perform some related actions

# USER DEFINED FUNCTION
# a funcion is a block of code which only runs WHEN it is CALLED
def myfunction():
    print('Hello from a function')


myfunction()  # was called, so will work, if I not used that don't work


######################################
def my_function(name):
    print(name + "Henrique")


my_function('Lucas ')
my_function('Miguel ')
my_function('Gabriel ')


######################################
def unknown(*kid):  # if the number of arguments is inknown, add a * before the parameter name:
    print('The youngest child is ' + kid[2])


unknown("Lucas", "Gabriel", "Miguel")  # 0 ,1 ,2


######################################
def key(child1, child2, child3):  # determinando as chaves
    print("The oldest son is " + child1)


key(child1="Gabriel", child2="Lucas", child3="Miguel")  # chaves and values


######################################
def keyunknown(**kid):
    print("His last name is " + kid["lastname"])  # vai usar o que estiver na chave citada


keyunknown(firstname="Lucas", lastname="Lima")


######################################
def withoutargument(country="Norway"):  # "country" é a variavel e "norway" é o valor principal, se não tiver valor
    # determinado vai ser "norway"
    print("Iam from " + country)


withoutargument('Brazil')
withoutargument('Japan')
withoutargument()
withoutargument("Icelands")

continuar
https://www.w3schools.com/python/python_functions.asp
