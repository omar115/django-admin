# django-commons

## choice field
li = [
    ("FR", "FRANCE"),
]
first val is the actual value that will be in db,
second val is the visual that will show only

## on_delete = models.CASCADE, models.SET_NULL, models.PROTECT
A is associated with B 
for CASCADE: if you delete A, associated B will also deleted
for SET_NULL: if you delete A, associated B will be NULL
for SET_DEFAULT: if you delete A, associated B will be set to a Default value
for PROTECT: if you delete A, it will prevent the deletion of B

## using contenttypes we can create generic relationships in our model
if you go to settings.py you will see contenttypes in installed apps
using contenttypes we can create generic relationships in our model
that will be useful for us to manage multiple apps altogether.

## Django ORM (Object Relation Mapper)
Django's ORM is just a pythonical way to create SQL to query and manipulate your database and get results in a pythonic fashion.

## features of ORM
- reduce complexity in code
- make the code more understandable
- help us get more done in less time

## django managers
a manager is like the interface of the database.