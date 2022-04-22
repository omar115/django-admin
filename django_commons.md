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
