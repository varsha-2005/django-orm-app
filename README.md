# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).


##Entity Relationship Diagram
![WhatsApp Image 2023-01-22 at 11 57 48 PM](https://user-images.githubusercontent.com/119288183/213933495-f31658b4-4638-47f7-931e-e47007cba439.jpeg)


## DESIGN STEPS

### STEP 1:
create a django project

### STEP 2:
create models and create superuser

### STEP 3:
run the server

Write your own steps

## PROGRAM:

### models.py :
```
from django.db import models

from django.contrib import admin

class Student (models.Model):
    referencenumber = models.CharField(max_length=8,primary_key=True)
    name = models.CharField(max_length=100)
    age = models.IntegerField()
    email = models.EmailField()

class StudentAdmin(admin.ModelAdmin):
    list_display = ("referencenumber","name","age","email")
```



## OUTPUT

### serverside output
![Screenshot (28)](https://user-images.githubusercontent.com/119288183/213933423-dfb4a62e-d3ff-465b-be01-e29978dc3db0.png)


### clientside output

![Screenshot (27)](https://user-images.githubusercontent.com/119288183/213933442-a44d3f93-90ee-4766-aa60-ce139c2eaf70.png)

## RESULT:
and hence done
