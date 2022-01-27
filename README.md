# rock-paper-scissor-game  


import random

win=int(input('what you wanna choose 0=rock,1=paper,2=scissor: \n'))
pin=random.randint(0,2)


print('computer\'s choice:') 



if pin==0:
  print('''
   _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)
''')
elif pin==1:
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



if win==0:
  print('''
   _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)
''')
elif win==1:
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
  
if win==pin:
  print('draw')
elif win==0 and pin==2:
  print('you win')
elif win==0 and pin==1:
  print('you lose')
elif win==1 and pin==2:
  print('you lose')
elif win==1 and pin==0:
  print('you win')
elif win==2 and pin==1:
  print('you win')
else :
  print('you lose')

  
