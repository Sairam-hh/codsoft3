import random
lower_case = 'abcdefghijklmnopqrstuvwxyz'
upper_case = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ'
symbol = '!@#$^_()[]{}/'
number = '1234567890'
all = lower_case + upper_case + symbol + number
length = int(input('enter a number : '))
password= "".join(random.sample(all,length))
print('The Generated Password is',password)
