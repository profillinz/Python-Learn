# Python-Learn
This is a basic github practice.
# BASIC PYTHON PRACTICE
##  Variable = Is a reusable container for storing a value
##            A variable behaves as if it were the value it contains.



age = 30

 
print("I'm going to be " + str(age) + " soon") 
print("I'm going to be", age, "soon") 
print(f"I'm going to be {age} soon")

### INTEGER
An integer data type is a fundamental data type in programming that represents whole numbers without any fractional part.

Age = 30
players = 5
quantity = 3

print(f"You are {age} years old now")
print(f"There are {players} in the field")
print(f"She had to buy {quantity} oranges instead")


### FLOAT
A float data type is a programming variable type used to represent decimal numbers (floating-point numbers) with fractional parts. It allows for the representation of real numbers in a computer's memory.
gpa = 3.3
distance = 6.5
price = 14.99

print(f"Your gpa is {gpa}")
print(f"You ran {distance}km")
print(f"He bought it for ${price}")

### STRING

A string data type is a sequence of characters, typically used to represent text. In programming, strings are often enclosed in single (' ') or double (" ") quotes. Here's an example in Python:

```python
my_string = "Hello, World!"
print(my_string)
```

In this example, `my_string` is a variable of the string data type, and it contains the text "Hello, World!".
name = "Teegee"
food = "Rice"
email = "Teegee123@gmail.com"

print(f'Hello {name}')
print(f"You like {food}")
print(f"My email is: {email}")

### BOOLEAN
The boolean data type represents a binary value, typically denoted as either `True` or `False`. Booleans are fundamental in programming for logical operations and conditional statements. Here's an example in Python:

```python
is_true = True
is_false = False

print(is_true)   # Output: True
print(is_false)  # Output: False
```

In this example, `is_true` and `is_false` are variables of the boolean data type, representing true and false values, respectively. Booleans are commonly used in conditional expressions and control flow statements.

online = True
for_sale = False
running = True

print(f"Are you online?: {online}")
print(f"Is the item for sale?: {for_sale}")
print(f"Were you running?: {running}")

x, y, z = 1, 2, 3

print(x)
print(y)
print(z)


## Practicing input function
#function get_numbers()
def get_numbers():
    # Ask the user for input using() method
    # Save it in the input_string variable
    input_string = input("Type your numbers here:")
    # Convert the input_ string to a list of strings by splitting it into separate using split()
    # Save it in the list_of_strings variable
    list_of_strings = input_string.split()
    # Converts the list of strings to list of numbers by using the int() method
    # Save it in the numbers variable
    numbers = [int(num) for num in list_of_strings]
    #return the numbers variable
    return numbers

get_numbers()    
    

# Making a list of numbers
## Define a list of numbers
numbers = [1, 2, 3, 4, 5]

## Access and print individual elements
print(numbers[1])
print(numbers[2])
print(numbers[3])
print(numbers[-1])
print(numbers[-2])
print(numbers[-3])

## Modify an element
numbers[-1]=3
print(numbers)

## Add an element to the end
numbers.append(10)
print(numbers)

## Remove an element from the list
numbers.pop()
print(numbers)
numbers.remove(1)
print(numbers)

## Get the length of the list
print("print the length of the list")
print(len(numbers)) 

## Iterate through the list
print("iterate through the list")
list_of_strings = ["1", "2", "3", "4", "5"]
list_of_numbers = [int(x) for x in list_of_strings]
print(list_of_numbers)

## Practicing splitting
string_1 = "I am a boy"
string_2 = "2 3 4 5 6"
list_1 = ["I" "am" "a" "boy"]
list_2 = ["2" "3" "4" "5" "6"]

print(string_1)
print(string_1.split())

print(string_2)
print(string_2.split())
