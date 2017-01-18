# learn-python-the-hard-way

Exercise 0

- Author gives instructions for Python setup (OSX, Microsoft and Linux)
- Author suggests TextWrangler text editor for OSX

Exercise 1 - A Good First Program

- ex1.py file contains:
print "Hello World"
print "Hello Again"
print "I like typing this"
print "This is fun."
print "Yay! Printing."
print "I'd much rather you 'not'."
print 'I "said" do not touch this.'

- First exercise try to show how to use text editor and commandline as a start
- Study Drills:
  - Add new print line
  - Print just one line
  - What is #

Exercise 2 - Comments and Pound Characters

- ex2.py contains:
# A comment, this is so you can read your program later.
# Anything after the # is ignored by python.

print "I could have code like this. "  # and the comment after is ignored

# You can also use a comment to "disable" or comment out a piece of code:
# print "This won't run."

print "This will run."

- Second exercise tell us how important comments are
- Try to show the general usage of # 
- Study Drills:
  - Read the code backwards (This helps programmers brain to not attach the meaning of each part)

Exercise 3 - Numbers and Math

- ex3.py contains: 
print "I will now count my chickens:"

print "Hens", 25 + 30 / 6
print "Roosters", 100 - 25 * 3 % 4

print "Now I will count the eggs:"

print 3 + 2 + 1 - 5 + 4 % 2 - 1 / 4 + 6

print "Is it true that 3 + 2 < 5 - 7?"

print 3 + 2 < 5 - 7

print "What is 3 + 2?", 3 + 2
print "What is 5-7?", 5 - 7

print "Oh, that's why it's False"

print "How about some more."

print "Is it greater?", 5 > -2
print "Is it greator or equal?", 5 >= -2
print "Is it less or equal?", 5 <= -2

- This exercise teach us the basic math calculations with python
- With study drills I worked on floating numbers so to find the exact answers of the calculations
- To work with floating numbers assing them as 5.2

Exercise 4 - Variables and Names

- Tricks to solve problems when you get stuck with the exercises: 
 1- Write comment on every line to explain yourself what you are doing
 2- Read your .py file backwards
 3- Read your .py file out loud, saying even the characters

- ex4.py contains:
cars = 100
space_in_a_car = 4.0
drivers = 30
passengers = 90
cars_not_driven = cars - drivers
cars_driven = drivers
carpool_capacity = cars_driven * space_in_a_car
average_passengers_per_car = passengers / cars_driven


print "There are", cars, "cars available."
print "There are only", drivers, "drivers available."
print "There will be", cars_not_driven, "empty cars available."
print "We can transport", carpool_capacity, "people today."
print "We have", passengers, "to carpool today."
print "We need to put about", average_passengers_per_car, "in each car."

- This section help us to learn using variables and use them wisely to code clearly and easily
