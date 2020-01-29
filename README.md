# introduction to Classes

## Object0 Oreinted Programming (OOP)

OOP is a pregramming paradigm that emphasizes designing your code so that it models real-word things.

- Objects: The *nouns* in our program; the things we are modeling
- Methods: The *verbs* that describe what our objects can do
- Attributes: the properties (think adjectives) that our objects have; ex. shirts have color, dogs eye color, etc

Objects communicate by passing messages to each other

** Python is inferently an object-oreiented language**

### THree pillars of object-oriented programming

- Encapsulation
- Inheritance
- Polymorphism

## Class and Instance 

- ** Class ** serves as a blueprint for creating objects

- ** Instance: ** an in-memory *thing* that was crerated using the class template

* Example:* a class is to an instance as a blueprint is to a house; cookie cutter

## Built-In Classes

Python ships with *many* built-in types all of which are themselves instances of classes

your classes are on equal footing with them

## A Little Terminology

![basic format of a class definition]

''' python
class DOG:
    def __init__(self, name):
        self._name = name
## Object Methods
How to declare and use methods on an object

A method is simply a functiton that belongs to a class. This means they can access class data directly.

Dunder methods are speicals methods ha python will calll directly under certain circumstances; ex. '__init__" gets called when we make a new instance of a class.

These make up what known as the **Python data model.** 162-Notes
