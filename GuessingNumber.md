# Python-Number-Guessing-Game
Python number guessing game that guides users to guess a random number. 

Code:

import random

target = random.randint(1,100)

while True:
    userchoice = int(input("Guess the number:"))
    
    if(userchoice == target):
        print("Sucessfully Guessed!!")
        break
    elif(userchoice < target):
        print("Your number is too small, guess the biggger number")
    else:
        print("Your number is too big, guess the smaller number")

print("**Gamer Over**")
