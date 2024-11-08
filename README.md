# PLP-Python-OOP-And-Asynchronous-Frameworks-week-four-assignment
Create a Python class named Person.
The Person class should have the following attributes:
name: representing the person's name.
age: representing the person's age.
gender: representing the person's gender.
Implement a method called introduce that prints a message introducing the person with their name, age, and gender.
Create an instance of the Person class and call the introduce method to display the person's information.
Create a GitHub repository for your assignment and submit the link.

class Person:
    def __init__(self, name, age, gender):
        # Initializing the attributes
        self.name = name
        self.age = age
        self.gender = gender
    
    def introduce(self):
        # Printing a message introducing the person
        print(f"Hello, my name is {self.name}. I am {self.age} years old and I am {self.gender}.")

# Creating an instance of the Person class
person1 = Person("Joana", 20, "Female")

# Calling the introduce method
person1.introduce()
