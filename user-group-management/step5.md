Add an existing user to a group using the command
`sudo usermod -a -G <groupname> <username>`

## Task

Add user `saradoe` to `projects` group:- `sudo usermod -a -G projects saradoe`{{execute}}

Let us check the groups a user is part of now:- `sudo groups saradoe`{{execute}}