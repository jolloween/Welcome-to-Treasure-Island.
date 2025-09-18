# Welcome-to-Treasure-Island.
#exercise

print(r'''
*******************************************************************************
          |                   |                  |                     |
 _________|________________.=""_;=.______________|_____________________|_______
|                   |  ,-"_,=""     `"=.|                  |
|___________________|__"=._o`"-._        `"=.______________|___________________
          |                `"=._o`"=._      _`"=._                     |
 _________|_____________________:=._o "=._."_.-="'"=.__________________|_______
|                   |    __.--" , ; `"=._o." ,-"""-._ ".   |
|___________________|_._"  ,. .` ` `` ,  `"-._"-._   ". '__|___________________
          |           |o`"=._` , "` `; .". ,  "-._"-._; ;              |
 _________|___________| ;`-.o`"=._; ." ` '`."\ ` . "-._ /_______________|_______
|                   | |o ;    `"-.o`"=._``  '` " ,__.--o;   |
|___________________|_| ;     (#) `-.o `"=.`_.--"_o.-; ;___|___________________
____/______/______/___|o;._    "      `".o|o_.--"    ;o;____/______/______/____
/______/______/______/_"=._o--._        ; | ;        ; ;/______/______/______/_
____/______/______/______/__"=._o--._   ;o|o;     _._;o;____/______/______/____
/______/______/______/______/____"=._o._; | ;_.--"o.--"_/______/______/______/_
____/______/______/______/______/_____"=.o|o_.--""___/______/______/______/____
/______/______/______/______/______/______/______/______/______/______/_____ /
*******************************************************************************
''')
print("Welcome to Treasure Island.")
print("Your mission is to find the treasure.")

you_choose = input("Do you Want to go to right or left? Digite (R) to right or (L) to left: ")
if you_choose == "L":
    print("you passed the first objective")
    swin_or_wall = input("do you want to swim or wait? type (S) to swin or (W) to wait: " )
    if swin_or_wall == "W":
        print("You to go to the second objective.")
        which_door = input("which door do you choose? type (R) to red, (B) to blue and (Y) to yellow: ")
        if which_door == "R":
            print("Burbed by fire. Game Over.")
        elif which_door == "B":
            print("Eaten by Beasts. Game Over!")
        elif which_door == "Y":
            print("You Win!")
        else:
            print("Game Over!")
    else:
        print("Attacked by trout.Game Over.")
else:
    print("Fall into a hole.Game Over.")



