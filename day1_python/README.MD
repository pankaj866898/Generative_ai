# Day 1 - Python Practice

# Function 1
def greet(name):
    return "Hello " + name

print(greet("Pankaj"))


# Function 2
def square(num):
    return num * num

print(square(5))


# List Practice
fruits = ["apple", "banana", "mango"]

print(fruits)
print(fruits[1])

fruits.append("orange")

print(fruits)


# Dictionary Practice
student = {
    "name": "Pankaj",
    "age": 23,
    "course": "AI & DS"
}

print(student)

print(student["name"])
print(student["course"])


# Function + Dictionary
def show_student(data):
    print("Name:", data["name"])
    print("Course:", data["course"])

show_student(student)


# Small Calculator Functions
def add(a, b):
    return a + b

def multiply(a, b):
    return a * b

print(add(10, 20))
print(multiply(5, 4))
