# Take-input-of-age-of-3-people-by-user-and-determine-oldest-and-youngest-among-them-using-python
person1= input('Enter Age of First Person: ')
person2= input('Enter Age of Second Person: ')
person3= input('Enter Age of Third Person: ')
if int(person1)>int(person2) and int(person1)>int(person3):
  print('First Person is Older')
elifint(person2) >int(person1) and int(person2) >int(person3):
  print('Second Person is Older')
else :
  print('Third Person is Older')

if int(person1) <int(person2) and int(person1) <int(person3):
  print('First Person is Youngest')
elifint(person2) <int(person1) and int(person2) <int(person3):
  print('Second Person is Youngest')
else:
  print('Third Person is Youngest')
