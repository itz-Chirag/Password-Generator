import random

def intro(a=1):
    digits = int(input("No. of Digits of Password You Want : "))
    main(digits)

password = []
letters = list(map(chr, range(97, 123)))
numbers = []
characters = ["!","@","#","$","%","&","/","?","[","]", "{", "}"]

finalList = letters + numbers + characters

def preMain():
    for i in range(0,10):
        numbers.append(i)
        i+=1

def main(digits):
    for i in range(0,digits):
        password.append(random.choice(finalList))
        i+=1
    postMain()

finalPassword=""
def postMain(a=1):
    global finalPassword
    for i in password:
        finalPassword += i
intro()
print(finalPassword)
