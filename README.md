# Employee-Profile
It's simple template employee profile by usinh the pyhton language .


# Create a program for employee profile .

name = (input("Enter employee name : "))
age = (int(input("Enter employee age : ")))
contact_number = (int(input("Enter employee contact number : ")))
address = (input("Enter employee address : "))
post = (input("Enter employee post in company : "))
language = (input("Enter the employee language : "))
salary = (int(input("Enter the salary of employee : ")))
company = (input("Enter the employee name of company : "))

class employee :

    def __init__ (self , name , age , contact_number , address , post , language , salary , company) :
        self.name = name
        self.age = age
        self.contact_number = contact_number
        self.address = address
        self.post = post
        self.language = language
        self.salary = salary
        self.company = company

    def profile (self) :
        print(f"Hello {self.name} !\nYour age is {self.age} .\nAlso your contact number is : {self.contact_number}\n{self.name} you are address is ({self.address}) .\nYour post in {self.company} is {self.post} and your salary is {self.salary} .")

call_class = employee (name , age , contact_number , address , post , language , salary , company)

call_class.profile ()

print(call_class)

print(name)

print(age)

print(contact_number)

print(address)

print(post)

print(language)

print(salary)

print(company)
