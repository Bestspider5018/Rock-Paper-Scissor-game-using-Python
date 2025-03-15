# Rock-Paper-Scissor-game-using-Python
import random
print("What Do you want to Choose?type 0 for Rock Or 1 for Scissors Or 2 for Paper :")
enter=int(input("Enter the no 0 for selecting rock or 1 for selecting scissors or for 2 for selecting paper :"))
r_0="rocks"
s_1="scissors"
p_2="paper"
computer_choice=random.randint(0,2)
print(f"computer choose {computer_choice}")
print(f"user choose {enter}")
if computer_choice==0 and enter==0:
    print(r_0)
    print("draw")
    
if computer_choice==1 and enter==1:
    print(s_1)
    print("draw")
    
if computer_choice==2 and enter==2:
    print(p_2)
    print("draw")    
     
if computer_choice==0 and enter==1:
    if computer_choice==0:
        print(r_0)
    else:
        print(s_1)   
    print("computer won . user lose ")
    
if computer_choice==1 and enter==0:
    if computer_choice==1:
        print(s_1)
    else:
        print(r_0)
    print("user won !") 
    
if computer_choice==2 and enter==0:
    if computer_choice==2:
        print(p_2)
    else:
        print(r_0)    
    print("computer won . user lose")

if computer_choice==0 and enter==2:
    if computer_choice==0:
        print(r_0)
    else:
        print(p_2)    
    print("user won !")

if computer_choice==1 and enter==2:
    if computer_choice==1:
        print(s_1)
    else:
        print(p_2)    
    print("computer won . user lose")
    
if computer_choice==2 and enter==1:
    if computer_choice==2:
        print(p_2)
    else:
        print(r_0)
    print("user won !")
