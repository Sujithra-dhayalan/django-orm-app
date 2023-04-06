# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS

### STEP 1:

### STEP 2:

### STEP 3:

Write your own steps

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
