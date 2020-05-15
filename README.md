# Python-Basic-Tutorial
Testing, made by me, copy this and paste it on Pycharm and using phyton
sorry if the english is bad or there are times that it's a mix of english & bisaya
# Basics steps by Maersk D. Piñero
# Hello World
# - Most basic step on starting programing, Green text means strings.
print("Hello World")
print("-----------------------------------------")
# Drawing a shape
# - Creating shapes on strings
print ("This is how you draw a shape:")
print("    /|")
print("   / |")
print("  /  |")
print(" /   |")
print("/____|")
print("----------------------------------------")
# Variables & Data Types
# - This is all about control and manage of the value.
# Eg. 1
print("Example 1")
print("This is all about variables & data types:")
print("Some may call him Maersky,")
print("but his real name is Maersk Piñero.")
print("He was a big fan of 88rising,")
print("His dream is to make his own software.")
print("Example 2")
# Eg. 2
character_name = "Beatrice Pilar"
character_two_name = "Beako"
artist_name = "BTS"
gender_name = "she"
gender_two_name = "her"
print("some may call her " + character_two_name + ",")
print("but " + gender_two_name + " real name is " + character_name + ".")
print("" + gender_name + " was a big fan of " + artist_name + ",")
print("" + character_two_name + " dream is to make " + gender_two_name + " own software.")
print("-----------------------------------------")

# When storing a number you don't need qoutation marks but when storing a string
# or plain text you need to put a qoutation mark
# Eg.
character_age = "20.321"
hero_name = "Chunchunmaru"
is_male = True
is_female = False
print("" + hero_name + " is already at the age of " + character_age + "." )
# The basic types of data in here are:
# 1.Strings or Plaintext
# 2.Whole numbers or Decimals Numbers
# 3.True or False Values
print("----------------------------------------")
# Working with string
print("Working with strings")
print(" ") #i just used this for the space
# \n means new line
# Eg.1
print("Silliman\nUniversity")
# If you want to put a qoutation mark on your string you should use \"
#Eg.2
print(" Sillaman University is \" AWESOME \"")
# You need to put an \" if you need to qoutation mark it so that it wont result to an error.
# You can also create a string variable
print(" ")
phrase = "Maersk D. Piñero"
print(phrase)
# you can also add another string called cuncatenation
# Eg.
phrase = "Maersky"
print(phrase + " is awesome")
# there is a special thing called function
# It can be use to modify our strings or get information about our strings
# we can also check too see if the strings are on entirely upper case or entirely on lower case
# Eg.
print(" ")
phrase = "BEAKO"
print (phrase)
print(phrase.isupper())
print(phrase.islower())
print(" ")
phrase = "beako"
print (phrase)
print(phrase.isupper())
print(phrase.islower())
# We can also use this functions as a combination
# Eg
print(" ")
print("Example 1")
phrase = "Silliman University"
print(phrase.upper().isupper())
print(" ")
print("Example 2")
phrase = "Silliman University"
print(phrase.lower().islower())
print (" ")
# We can also figure out the length of the string
print ("Counting all the characters of the string")
print ("Example 1")
print ("MAERSK D PINERO FUTURE SOFTWARE DEVELOPER\n=")
phrase = "MAERSK D PINERO FUTURE SOFTWARE DEVELOPER"
print(len(phrase))
print(" ")
# We can also get the individual character inside of a string, grabbing a specific character.
# Eg
phrase = "Maersk D Pinero"
print (phrase)
print(phrase[0])
print(phrase[7])
print(phrase[9])
print(" ")
# Another function is an Index function, it will tell us where a specific character or string is.
phrase = "Beako P Meowa"
print (phrase)
print(phrase.index("B"))
print(phrase.index("P"))
print(phrase.index("Meowa"))
# We can also use the replace function
# Eg.
phrase = "Silliman University"
print(phrase.replace("Silliman","Diliman"))
print(phrase.replace("University","By the sea"))
print (" ")
# Working with numbers
# You can use numbers such as whole number, decimal number, negative number, and basic arithmetic such as
# addition + , substraction - , multiplication * , division  , in using the % it will spit out the remainder
# Eg.
print (1+3.3)
print (-1 + 6.312)
print (-32 * -32)
print (3 * 4 + 5)
print (3 * (4 + 5))
print (10 % 3)
# we can also sote this numbers inside this variables
my_num = 321
print (my_num)
print (" ")
# we can also convert this number as a string using (str)
my_num = 2001
print (str(my_num))
print(str(my_num) + " My birth year")
print (" ")
# We can also get the absolute value of the number (abs)
my_num = -100
print(abs(my_num))
# There is another fucntion called power (pow)
print(pow(3,2))
print(pow(10,2))
print(pow(4,8))
print(" ")
# we can also use another function such as maximum & minimum (max) & (min)
print(max(4,6))
print(max(19,4))
print(min(-1,4))
print(min(6,199))
print(" ")
# we can also use the round function by rounding off a number (round)
print(round(3.4))
print(round(3.5))
print (" ")
# if you wanna imput some math function you got to imput  (from math import *) this is called a module.
# we can also use the floor method by grabbing off the smallest number (floor)
# and the ceil function will always round the number up no matter what (ceil)
# and the sqaure root function which will return the number to its sqaure root (sqrt)
from math import *
print(floor(3.7))
print(floor(5.2))
print(ceil(3.7))
print(ceil(5.2))
print(sqrt(36))
print(sqrt(100))
print(" ")
# you can search a bunch more of math functions on the internet and what we used here as an example are
# one of the most basic math functions on python
# getting input from a user
print("Getting input from a user")
name = input("enter your name: ")
age = input("Enter your age: ")
print ("Wassup Mananap the one and only " + name +"!")
print("bawal below " + age + " dito !")
print (" ")

# Building a calculator
print ("Combining Calculator")
num1 = input("Enter any number: ")
num2 = input("Enter another number: ")
result = num1 + num2
print(result)
print (" ")
# Building a addition calculator
print (" Addition calculator")
num1 = input("Enter a whole number: ")
num2 = input("Enter another whole number ")
result = int(num1) + int(num2)
print(result)
print(" ")
# The problem on this calculator is that it can't read decimal number if you use Int function (int)
# Int function is all about whole number, the solution to this is using float function (float)
print("addition calculator that can solve decimal addition problems")
num1 = input("Enter any number")
num2 = input("Enter another number")
result = float(num1) + float(num2)
print(result)
print(" ")
# we can make a mad libs game
print("Madlibs game")
print (" ")
Enter_a_color = input("Enter a color: ")
Enter_a_object = input ("Enter a object: ")
Enter_a_name = input ("Enter a name: ")
print("Roses are " + Enter_a_color )
print (Enter_a_object + " are blue")
print("I love " + Enter_a_name)
print(" ")
# this is how to make a list in python, we can use a bullian, strings & numbers.
# Eg. Making a list of friends
print ("List")
print ("Example 1")
friends = ["Luffy","Beako","Katakuri"]
print (friends)
print (" ")
print ("Example 2")
friends = ["Luffy","Beako","Katakuri"]
print (friends[0])
print (friends[1])
print (friends[2])
print (friends[-1])
print (friends[-2])
print (friends[-3])
print (" ")
# We can also grap a specific character
print ("Example 3")
friends = ["Luffy","Beako","Katakuri","Soma","Sinbad"]
print (friends[1:2])
print (friends[2:4])
print (friends[1:4])
print (friends[0:4])
print (" ")
# We can also  modify the value
print ("Example 4")
friends = ["Luffy","Beako","Katakuri","Soma","Sinbad"]
friends[1] = "Dragon"
print(friends[1])
# This will be all about using list as functions
print(" List Function")
# We will now use the extend function, just adding the list together (extend)
print("Example 1")
lucky_numbers = [3,6,9,12,15]
friends = ["Luffy","Beako","Chunchunmaru","Honda","Doremon"]
friends.extend(lucky_numbers)
print(friends)
print(" ")
# we can also add individual elements on the list, this will always add an item at the end of the list (append)
print("Example 2")
friends = ["Luffy","Beako","Chunchunmaru","Honda","Doremon"]
friends.append("Saitama")
print(friends)
print(" ")
# and if you want to add an item in the middle of the list or anywhere use insert (insert)
print("Example 3")
friends = ["Luffy","Beako","Chunchunmaru","Honda","Doremon","Konosuba"]
friends.insert(3,"Itachi")
print(friends)
print(" ")
# We can also remove elements or removing a value (remove)
print("Example 4")
friends = ["Luffy","Beako","Chunchunmaru","Honda","Doremon"]
friends.remove("Doremon")
print(friends)
print(" ")
# and we can also remove all the elements on the list (clear)
"Example 5"
friends = ["Luffy","Beako","Chunchunmaru","Honda","Doremon"]
friends.clear()
print(friends)
print(" ")
# we can also use pop, it will pop an item,value or element that is last on the list (pop)
print("Example 6")
friends = ["Luffy","Beako","Chunchunmaru","Honda","Doremon"]
friends.pop()
print(friends)
print(" ")
# if you want to know a certain value is on the list, it will just show its number on where its located (index)
print("Example 7")
friends = ["Luffy","Beako","Chunchunmaru","Honda","Doremon"]
print(friends.index("Beako"))
print(friends.index("Doremon"))
print(friends.index("Honda"))
print(" ")
# you can also count the number of silimar elements on the list
# This will tell you how many times a value shows up in the list (count)
print("Example 8")
friends = ["Luffy","Beako","Chunchunmaru","Honda","Doremon","Beako","Beako","Luffy"]
print(friends.count("Beako"))
print(friends.count("Luffy"))
print(friends.count("Honda"))
print(" ")
# we can also sort this list in an alphabetical order (sort)
print("Example 9")
lucky_numbers = [3,53,-3,133332,5]
friends = ["Luffy","Beako","Chunchunmaru","Honda","Doremon"]
lucky_numbers.sort()
friends.sort()
print(lucky_numbers)
print(friends)
print(" ")
# We can also reverse the order of list (reverse)
print("Example 10")
lucky_numbers = [3,53,-3,133332,5]
friends = ["Luffy","Beako","Chunchunmaru","Honda","Doremon"]
lucky_numbers.reverse()
friends.reverse()
print(lucky_numbers)
print(friends)
print(" ")
# and there is also a function that can copy a list (copy)
print("Example 11")
lucky_numbers = [3,53,-3,133332,5]
friends = ["Luffy","Beako","Chunchunmaru","Honda","Doremon"]
lucky_numbers2 = lucky_numbers.copy()
friends2 = friends.copy()
print(lucky_numbers)
print(friends)
print(friends2)
print(lucky_numbers2)
print(" ")
# This will be all about tuples, a tuples is a type of data structure, it means a
# container storing a different values or information, tuples is inmutable, you can't change it
# Tuples are index that starts at 0
print("Tuple")
print("Example 1")
coordinates = (4,5,54,312,65)
print(coordinates[0])
print(coordinates[1])
print(coordinates[4])
print(coordinates[3])
print(coordinates[2])
print (" ")
# List can assign different values, mutate, modify or change but in tuple you can't do that.
# Tuples is always used for data that will never change, storing data that does not need to change.
# But we can still add more coordinates or value in tuples like in a list but in tuples we can't change
# it's values or modify it unlike list. tuples are mostly used in special data.
print (" Functions ")
# Function is just a collection of code which perform a specific task, it can allow you to break up a code to
# do specific things.
# whenever using the keyword (def) this means that python understands that you want to use a function.
print (" Example 1") # ill make this function saying hello user
def say_hi():
    print("Hellow User")
print (" ")
say_hi()

# Now we will give them information, this is called a parameter, it is a piece of information that
# we give to a function
print (" ")
print ("Example 2")
def say_hi (name):
    print("Hello " + name)


say_hi("Maersky")
say_hi("Beako")
# we can also add another paramater, now ill try adding age to it,
print (" ")
print ("Example 3")
def say_hi (name, age):
    print("Hello " + name + ", you are " + age)


say_hi("Maersky","18")
say_hi("Beako","18")
# We can also use strings, buliens, arrays, numbers or any types of data in a function
# ill try using numbers in here by adding + str for it to work and won't cause an error.
print (" ")
print ("Example 4")
def say_hi (name, age):
    print("Hello " + name + ", you are " + str(age))


say_hi("Maersky",20)
say_hi("Beako",21)

# Now we will use the return statement in the python functions
# Normally we can cube a number using basic math function such as this
print("Return Statement")
print("Basic cube function")
print(6^3)
print(2^64)
print(9^4)
print(" ")
# now we will thy the return statement, but first thing we got to do is apply a function which is ( def cube() )
# basically this function will just cube this number, using the return statement
# we can also return string, bullien or array  on using the return statement function (return)
print("Example 1")
def cube(num):
    return num*num*num
print(cube(3))
print(cube(64))
print(" ")
print("Example 2")
def cube(num):
    return num*num
result = cube(4)
print(result)
print(" ")
