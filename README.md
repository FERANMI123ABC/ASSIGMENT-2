# ASSIGMENT-2
A for loop is ideal when you know in advance how many iterations you need or when iterating over a collection.

Iterating Over a Range:

Use a for loop when the number of iterations is predetermined.
python
Copy code
# Example: Print numbers from 1 to 10
for i in range(1, 11):
    print(i)
Iterating Over Collections:

When working with lists, dictionaries, or other iterable objects.
python
Copy code
# Example: Iterate through a list
fruits = ['apple', 'banana', 'cherry']
for fruit in fruits:
    print(fruit)
Known Increment/Sequence:

When you need to increment or decrement a value systematically.
python
Copy code
# Example: Print even numbers
for i in range(0, 20, 2):
    print(i)
Cleaner Syntax for Fixed Iterations:

Use a for loop for clarity when the termination condition is defined by a range or iterable.
When to Use a while Loop
A while loop is better suited for scenarios where the number of iterations depends on a condition being met, which may not be known in advance.

Condition-Based Iteration:

Use a while loop when you need to repeat an action until a certain condition changes.
python
Copy code
# Example: Print numbers until a threshold
x = 1
while x < 10:
    print(x)
    x += 1
Input Validation:

When waiting for valid user input or ensuring a certain condition is met.
python
Copy code
# Example: Prompt user until correct input
password = ""
while password != "secure123":
    password = input("Enter the password: ")
Infinite Loops:

For continuously running processes (e.g., game loops or server listeners).
python
Copy code
# Example: Infinite loop
while True:
    print("Running...")
    break  # Add a condition to exit
Dynamic Termination:

Use a while loop when the termination condition might change dynamically based on other factors.
python
Copy code
# Example: Countdown
count = 10
while count > 0:
    print(count)
    count -= 1
    switch(brand){
       case "Toyota":
       case "Honda":
       case "Niissan":
       alert('This is economy segment');
       break;
       case"Lamborghini":
       case"Benz":
       case"Ferrari":
       alert("This is luxury segment");
       break;
       case"BMW":
       case"Mazda":
       case"Porsche":
       alert("This is a sport car");
       break;
       default:
       alert("I dont have information on cars");
