Here, I am practicing Object Oriented Programming in Python.
## Task-7.1 
# Basic Class and Object Creation
Creating a class Product
Attributes: name,price,category
Methods: get_info--> prints the product details
Optional: creating one more method apply_discount(Percent) that returns the discounted price.
creating the first method - product1
creating the second method - product2
## Task-7.2
# Modifying the Product class
Making price a private attribute-using double underscore
Creating getter and setter method:
~get_price()
~set_price(new_price).
 Testing modified prices using set_price(new_price) -only update if the price is > 0..
 Invalid input gets rejected.
## Task-7.3
# Inheritance(single level)
firstly , creating the main Product class
Creating a Subclass Electroniproduct that inherites from Product.
Additional Attribute: Warranty_years.
Overriding the get_info() mathod to inclue the warranty info.
Creating an object and demonstrating Inheritance and Overriding.
## Task-7.4
# Polymorphism
Creating two classes:
~Laptop(product)
~Mobile(product)
Both override get_info()
Writing a loop that iterates over objects of Laptop and Mobile and calls get_info() on each to show polymorphism.
## Task-7.5
# Abstraction (Using Abstract Base Class)
Creating an Abstract class Payment with abstract method:
process_payment(amount)
Creating the first subclass
CreditCardPayment()
Both subclasses are overriding process_payment()method with print statement.
Finally, testing all the classes.
# Task-7.6
# Magic method and Operator Overloading
Here we have our initial Product class:
and we have added __str__ mathod 
and it Returns a readable string:
Product(name, price, category) 
operator overloading(__add__)
allows product1 + product2
to return the total combined price.
Testing this two product objects. 
## Task-7.7
# Mini Project: Simple Inventory project(OOPS only)

 
