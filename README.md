# Crossroads-Fates-Python-Game
An Adventure game using python


Name = input("What is your Name:")
print("Welcome",Name,"to this adventure! :)")
ans=input("You are on a dirt road, it has come to an end and you can go to left or right which way you want to go? ").lower()
if ans == "left":
    answer = input("you come to river you can walk around it or swim accross it,type W to walk around or S to swim accross").lower()
    if answer=='s':
       print("you swam accross and eaten by alligator and you lost." )
    elif answer=='w':
        print("You walked away from miles,ran out of water and you lost the game")
    else:
        print("Invalid option,you loose :(")
        

elif ans=="right":
    answer=input("you came to a bridge,it looks wobbly,do you want to cross or go back(cross/go back)?")
    if answer=='back':
       print("you go back and loose." )
    elif answer=='cross':
        answer= input("you crossed the bridge and met a stranger you want to talk(yes/no)?")
        if answer=='yes':
            print('you talk to the stranger and they give you Gold,You Won!')
        elif answer=='no':
            print("you didn't talk to the stranger you missed the Gold,you loose")
        else:
            print("Invalid option,you loose :(")
            

            
    else:
        print("Invalid option,you loose :(")
        
else:
    print("Invalid option,you loose :(")
print("Thank You for Playing",Name)

    
    
    
