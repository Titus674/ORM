# Ex02 Django ORM Web Application
## Date: 22-09-2025

## AIM
To develop a Django application to store and retrieve data from Car Inventory Database using Object Relational Mapping(ORM).

## ENTITY RELATIONSHIP DIAGRAM

<img width="877" height="609" alt="image" src="https://github.com/user-attachments/assets/be46ca26-4cb2-4242-99e7-870cdfcc131f" />

## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create details for 10 books

## PROGRAM
```
admin.py

from django.contrib import admin
from.models import Employee, EmployeeAdmin
admin.site.register(Employee, EmployeeAdmin)    

models.py

from django.db import models
from django.contrib import admin
class Employee (models.Model):
    eid=models.CharField(max_length=20, help_text="Employee
    name=models.CharField(max_length=100)
    salary=models. IntegerField()
    age=models. IntegerField()
    email-models. EmailField()



class EmployeeAdmin(admin.ModelAdmin):
    list_display= 'eid', 'name', 'salary', 'age', 'email')
    


```



## OUTPUT

![alt text](<Screenshot 2025-09-15 173941.png>)



## RESULT
Thus the program for creating a database using ORM hass been executed successfully
