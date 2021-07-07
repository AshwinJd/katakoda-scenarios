# Sudo Group

Most Linux systems, including Ubuntu, have a user group for sudo users. To grant the new user elevated privileges, add them to the sudo group.

**Adding user to sudoers group**


Create a new user with a new command `adduser <username>`
`adduser rondoe`{{execute}} provide all the details as required along with the password.

Create another user `adduser saradoe`{{execute}}

Add user rondoe to sudo group using `usermod` command

`usermod -aG sudo rondoe`{{execute}}

Check the user is correctly added to the group by listing the groups user is part of:- `groups rondoe`

Let us switch to the new user.

`su - rondoe`{{execute}} enter the password for login to the account.

