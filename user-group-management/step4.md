In Linux, groups are used to organize and administer user accounts. The primary purpose of groups is to define a set of privileges such as reading, writing, or executing permission for a given resource that can be shared among the users within the group.



Create a group using the command `sudo groupadd <groupname>`.
Only user with **sudo** privileges can create groups


## Task

Create a group:- `sudo groupadd projects`{{execute}}

The command adds an entry for this group in `/etc/group` and `/etc/shadow` files.

Let us see,  
`sudo cat /etc/group`{{execute}}  
`sudo cat /etc/shadow`{{execute}}  