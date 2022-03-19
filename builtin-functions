#builtin-functions

#task 1
spisok = [float(i) for i in input(' enter numbers of the list: ').split()]
def multiply(numbers):  
    total = 1
    for x in numbers:
        total *= x  
    return total  
print(multiply(spisok))


#task 2
upper = 0
lower = 0
s = input()
for i in s:
    if i.isupper():
        upper +=1
    elif i.islower():
        lower +=1
print ("number of Upper case characters: ", upper)
print ("number of Lower case characters: ", lower)


#task 3
stroka = input("enter the string: ").lower()
if stroka == stroka[::-1]:
    print("the string is a palindrome")
else:
    print("the string is NOT a palindrome")


#task 4
import math

a = int(input())
c = int(input())
b = math.sqrt(a)

print("Square root of", a, "after", c, "miliseconds is ", b )


#task 5
x = (True, True, True)
result = all(x)
print(result)


#dir-and-files

#task 1
import os

dirname = input("Enter your directory: ")
files = os.listdir(dirname)

print(files)


#task 2
import os
print('Exist:', os.access('C:\\Users\\kan_d\\Desktop\\tilt\\pp-2 (python)', os.F_OK))
print('Readable:', os.access('C:\\Users\\kan_d\\Desktop\\tilt\\pp-2 (python)', os.R_OK))
print('Writable:', os.access('C:\\Users\\kan_d\\Desktop\\tilt\\pp-2 (python)', os.W_OK))
print('Executable:', os.access('C:\\Users\\kan_d\\Desktop\\tilt\\pp-2 (python)', os.X_OK))



#task 3
path = input("Enter the path: ")
import os
if os.path.exists(path):
    print("Path exists")
    print("Filename: ", os.path.basename(path))
    print("Directory: ", os.path.dirname(path))
else:
    print("Path does not exist")


#task 4
path = input("Enter the path of the file: ")
with open(path, 'r') as f:
    count = 0
    for line in f:
        count += 1
print("The number of lines in the file is: ", count)


#task 5
fileName = input("Enter file name: ")
list = input("Enter list: ").split()
for i in range(len(list)):
    print(list[i], file=open(fileName, "a"))


#task 6
import string
alphabet = string.ascii_uppercase
for letter in alphabet:
    with open(letter+".txt",'w') as file:
        file.write(letter)

#task 7
with open("test.txt") as f:
    with open("out.txt", "w") as f1:
        for line in f:
            f1.write(line)


#task 8
import os
filePath = input("Enter the path in '' : ")

if os.path.exists(filePath):
    os.remove(filePath)
else:
    print("Can not delete the file as it doesn't exists")
