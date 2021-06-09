# christian-python

## 1. 
course = 'Python for Beginners'

print(course)

# The string above behaves much like an object,
# when we use the dot operator on a variable a list of functions will
# appear with unique behaviors
# FOR EXAMPLE:

# the upper function will return the context of course in uppercase letters
print(course.upper())

# This function will return the index of string characters set as
# parameter for the per string object example
# (returns index of first instance only, case sensetive)
print(course.find(''))

# Will replace the for in the string object example
# with string character number 4
print(course.replace('for', '4'))

print('Python' in course)

## 2. 
 First: 10.1
 Second: 20
 First = input('First: ')
 Second = input('Second: ')


 sum = float(First) + float(Second)

 print("Sum: " + str(sum))

OR

First = float(input('First: '))
Second = float(input('Second: '))

print(First + Second)

## 3. 

course = 'Python for Beginners'

print(course)

 The string above behaves much like an object,
 when we use the dot operator on a variable a list of functions will
 appear with unique behaviors
 FOR EXAMPLE:

 the upper function will return the context of course in uppercase letters
print(course.upper())

 This function will return the index of string characters set as
 parameter for the per string object example
 (returns index of first instance only, case sensetive)
print(course.find(''))

 Will replace the for in the string object example
 with string character number 4
print(course.replace('for', '4'))

print('Python' in course)

print(course.find('Python'))

 LOGICAL OPERATORS
 and, or, not

price = 25
print( price > 10 and price < 30)

 IF STATEMENTS
temperature = 35

if temperature > 30:
    print("It's a hot day" )
    print("Drink plenty of water" )
elif temperature > 20: #(20,30]
    print("It's a nice day")
elif temperature > 10: #(10, 20]
    print("it's a bit cold")

print("Done")

weight = float(input('Weight: '))

l = weight * .45
L = weight == weight
k = weight * 2.2
K = weight == weight

choice = input('(K)g or (L)bs: ')

if choice == l or K:
  print('Weight in Kg: ', l or K)

if choice == k or L:
  print('Weight in Lbs', k or L)



