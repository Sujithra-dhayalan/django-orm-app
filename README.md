# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS

### STEP 1:
Clone the repository to Theia IDE.Start a new inside the project folder.

### STEP 2:
Type the appropriate code for your table and provide appropriate datatypes to the columns.

### STEP 3:
Create a report about project in readme.md file and upload the django-orm-app folder to your remote repository.



## PROGRAM

Include your code here
```
from django.db import models

from django.contrib import admin
# Create your models here.
class Student (models.Model):
    referencenumber=models.CharField(primary_key=True,max_length=20,help_text="reference number")
    name=models.CharField(max_length=100)
    age=models.IntegerField()
    email=models.EmailField()
    bloodgroup=models.CharField(max_length=100)


class StudentAdmin (admin.ModelAdmin):
    list_display=('referencenumber','name','age','email','bloodgroup')
```
## OUTPUT

Include the screenshot of your admin page.

![django students](https://user-images.githubusercontent.com/115523950/230268752-69f69a09-af76-4dc8-b670-8046f7d3286d.png)

## RESULT
Thus the program for Django admin is created successfully.
