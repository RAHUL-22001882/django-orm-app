# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS

### STEP 1:
open theia idle and start server 
### STEP 2:
create an folder myapp
### STEP 3:
write the following program and run the server
Write your own steps

## PROGRAM

Include your code her
hml
```
from django.db import models
from django.contrib import admin

# Create your models here.
class Student (models.Model):
    referencenumber=models.CharField(primary_key=True,max_length=20,help_text="reference number")
    name=models.CharField(max_length=100)
    age=models.IntegerField()
    email=models.EmailField()
    phone=models.IntegerField()
class StudentAdmin(admin.ModelAdmin):
    list_display=('referencenumber','name','age','email','phone')
  ```

## OUTPUT

Include the screenshot of your admin page.
![Screenshot (80)](https://github.com/RAHUL-22001882/django-orm-app/assets/123528986/92d31a50-dc99-4605-969c-bba76aec1ac2)



## RESULT
Thus orm app is created using HTML .
