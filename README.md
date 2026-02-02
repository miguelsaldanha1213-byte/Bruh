import random
nível="fácil"
answer={"fácil":["1", "2", "3", "4", "5"]}
reposta=random.choice(answer[nível])
while True:
 player=input("you: ").lower()
 if player == reposta:
 print("corregulations, you guessed the number!")
 break
 else:#
 print("no, try again.")
