# rock-paper-scissor-game  



import random

user_choice = int(input('what you wanna choose 0=rock,1=paper,2=scissor: \n'))
computer_choice = random.randint(0,2)


print('computer\'s choice:') 



if computer_choice == 0:
  print('''
   _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)
''')
elif computer_choice == 1:
  print('''
  _______
---'   ____)____
          ______)
          _______)
         _______)
---.__________)
'''
  ''')  
''')
else:
  print(''' 
   _______
---'   ____)____
          ______)
       __________)
      (____)
---.__(___)
'''
  
  ''') ''')
 
 

print('you chose:')



if user_choice == 0:
  print('''
   _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)
''')
elif user_choice == 1:
  print('''
  _______
---'   ____)____
          ______)
          _______)
         _______)
---.__________)
'''
  ''')  
''')
else:
  print(''' 
   _______
---'   ____)____
          ______)
       __________)
      (____)
---.__(___)
'''
  
  ''') ''')
  
if user_choice == computer_choice :
  print('draw')
elif user_choice == 0 and computer_choice == 2:
  print('you win')
elif user_choice == 0 and computer_choice == 1:
  print('you lose')
elif user_choice == 1 and computer_choice == 2:
  print('you lose')
elif user_choice == 1 and computer_choice == 0:
  print('you win')
elif user_choice == 2 and computer_choice == 1:
  print('you win')
else :
  print('you lose')
