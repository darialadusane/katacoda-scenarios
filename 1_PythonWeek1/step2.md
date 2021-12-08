# Strings
Strings are text in code. They can be declared in Python like so:

`email = "donotreply@vodafone.com"
`{{execute}}

The code above declares the variable ```email``` and assigns it the string 'donotreply@vodafone.com'. We can print it out in Python like so:

`print(email)`{{execute}}

We can also print out strings directly like so:

`print("I like trains!")`{{execute}}

You can print a new line using ```\n```.

`print("I like\ntrains!")`{{execute}}

Try it yourself using the terminal on the right.

# Input
We can obtain user input using a special Python keyword/method called ```input()```. Let's say we want to obtain the user's name, in Python we do the following:

`username = input("What is your name?")`{{execute}}

 When we run this code, the program will wait for the user to enter a name before continuing. Please go to the terminal, type your name, and then press <kbd>ENTER</kbd>. In the above example, the user's name is stored in a variable ```username```. We can print out the user's name like so:

 `print("Your name is " + username)`{{execute}}

In the above code, we are combining the text *'Your name is '* with the string stored in ```username```. This is known as String Concatenation; joining two strings together.

 `print("Hello " + username + ", nice to meet you!")`{{execute}}

# Quick Exercise
- Type your code line by line into the Terminal (don't forget to press <kbd>ENTER</kbd>)
- Ask the user to input their age and save it as a variable
- Ask the user to input the current year (2021 as of writing) as a second variable
- Use maths to figure out their birth year (assume they're born on 1st Jan to make the maths simpler)
- Save the answer as a third variable and print it

# Practical Uses
A lot of software require user input of some sort, be it a mouse click, a finger tap, via your keyboard or something else entirely. Instagram can only load your feed if you login and tell Instagram what your username/password is. Minecraft can only move your character if you tell it to, via mouse and keyboard. (Again, there's a few more steps involved in real life, but you get the idea.)