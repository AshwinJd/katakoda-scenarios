Users in Linux systems can be created using the command  
`useradd -u <userid> <username>`


## Task


Create a user **johndoe** with user id **1618**

Before we create the user lets see what all users are present in the system currently

`cat /etc/passwd`{{execute}}

**Create user** `useradd -u 1618 johndoe`{{execute}}

Let us confirm if the user is create `id -u johndoe`{{execute}}

Let us all the list of users present in the system `cat /etc/passwd`{{execute}}