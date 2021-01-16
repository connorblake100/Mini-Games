# Mini Games

import random

print("Welcome to Mini Game...Pick a number from 1-5 if you guess the correct number you win!")

def Mini_Game(Game):
    b = input("Pick a number between 1 and 5: ")
    a = random.randint(1,5)
    if a==int(b):
        print("Congradulations you're a winner!")
    else: 
        print("Looks like your a Loser, Sorry.")
        
def Mini_Game2(Game):
    print("In this game you have 1 chance at answering the trivial question. Ready Set...")
    q = input("What year was salvery abolished in America? Go: ")
    if q == "1865":
        print("Wow your IQ must be out of this world because You Are CORRECT.")
    else:
        print("Ouch. History may not be for you because You Are WRONG.")
        
Mini_Game("Game")
answer = input("Enter 'yes' to play again OR 'next' to play a different game OR 'no' to stop playing. \nEnter Here: ")
if answer == "yes":
    Mini_Game("Game")
    print("You've reached max amount of games for today, come again later.")
elif answer == "next":
    Mini_Game2("Game")
    print("You've reached max amount of games for today, come again later.")
else:
    print("Sad to see you leave, come again when your feelin' Lucky")
