# Name of project: 0x01. Shell, permissions
## shell permission Exercises using shell scripted files
## Requirements
	- Allowed editors: vi, vim, emacs
	- All your scripts will be tested on Ubuntu 20.04 LTS
	- All your scripts should be exactly two lines long ($ wc -l file should print 2)
	- All your files should end with a new line
	- The first line of all your files should be exactly #!/bin/bash
	- A README.md file, at the root of the folder of the project, describing what each script is doing
	- You are not allowed to use backticks, &&, || or ;
	- All your files must be executable
### Exercise 0 - Create a script that switches the current user to the user betty.
	- You should use exactly 8 characters for your command (+1 character for the new line)
	- You can assume that the user betty will exist when we will run your script
	- file name: 0-iam\_betty
### Exercise 1 - Write a script that prints the effective username of the current user.
	- file name: 1-who\_am\_i
### Exercise 2 - Write a script that prints all the groups the current user is part of.
	- file name: 2-groups
### Exercise 3 - Write a script that changes the owner of the file hello to the user betty.
	- file name: 3-new\_owner
### Exercise 4 - Write a script that creates an empty file called hello.
	- file name: 4-empty
### Exercise 5 - Write a script that adds execute permission to the owner of the file hello.
	- The file hello will be in the working directory
	- file name: 5-execute
### Exercise 6 - Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
	- The file hello will be in the working directory
	- file name: 6-multiple\_permissions
### Exercise 7 - Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello
	- The file hello will be in the working directory
	- You are not allowed to use commas for this script
	- file name: 7-everybody
### Exercise 8 - Write a script that sets the permission to the file hello as follows:
	- Owner: no permission at all
	- Group: no permission at all
	- Other users: all the permissions
	- file name: 8-James\_Bond
### Exercise 9 - Write a script that sets the mode of the file hello to this:
	- rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
	- The file hello will be in the working directory
	- You are not allowed to use commas for this script
	- file name: 9-John\_doe
### Exercise 10 - Write a script that sets the mode of the file hello the same as olleh’s mode.
	- The file hello will be in the working directory
	- The file olleh will be in the working directory
	- file name: 10-mirror\_permissions
### Exercise 11 - Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
	- Regular files should not be changed.
	- file name: 11-directories\_permissions
### Exercise 12 - Create a script that creates a directory called my\_dir with permissions 751 in the working directory.
	- file name: 12-directory\_permissions
### Exercise 13 - Write a script that changes the group owner to school for the file hello
	- The file hello will be in the working directory
	- file name: 13-change\_group
