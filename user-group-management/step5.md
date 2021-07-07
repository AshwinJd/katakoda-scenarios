# Adding user to groups

Add an existing user to a group using the command
`usermod -a -G <groupname> <username>`

## Task

Add user `saradoe` to `projects` group:- `usermod -a -G projects saradoe`{{execute}}

Let us check the groups a user is part of now:- `groups saradoe`{{execute}}