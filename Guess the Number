#Importing random and sys
import random
import sys

#Welcoming the user to the game
welcome="Welcome to Guess the Number Game"
print(welcome.center(48,"*"))
print()

#Getting the user name
name=str(input("Please enter your name : "))
print()
print("Hi",name)

#Displaying the game procedure
print("You need to guess the number,\nif you select correctly you will win the game\nand earn stars")
print("Otherwise, you will loose the game and lost stars")
print()

    
while True:
    print()
    print("Let's begin")
            
    try:
        rand=random.randrange(0,11)
        print(rand)
        num=int(input("Enter a number from 0 to 10 : "))
        while True:
            if num>=0 and num<=10:
                        
                        
                if num==rand:
                    print()
                    print("You Won the game")
                    print("You earned ***** ")
                    print("     :)          ")
                    break
                        
                else:
                    print("You lost the game")
                    print("Try again")
                    print()
                    break
            else:
                print("You entered a invalid number")
                print("Try again")
                break
                        
                
    except ValueError:
        print("There is a value error")
        print()

    #Check whether user wants to play again.       
    again=str(input("Do you want to play again (y/n) : "))
            
    if again=="y" or again=="Y":
        
        print()
        continue
        
            
    elif again=="n" or again=="N":
        print("Thank you for playing.")
        print("Bye")
        break
    
        
    
    
