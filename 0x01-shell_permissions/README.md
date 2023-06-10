# SHELL PERMISSION
- r
	r irefers to read permission
- w
	w refers to write permission
- x
	x refers to execution permission

# User, Group, Everyone
- -rwx rwx rwx
	The first (-) there indicates the type that it is a regular file while (d) indicates it is a document.
	The irst column also indicate the user access to the file. rwx = 111(in binary) = 7(in decimal)

	tis logic also applies rto the rest of the colums, column 2, column3 = group and everyone respevtvely

- chgrp = change group
- chmod = change permission
- chown = changeg ownership

rwx = 111 = 7
rw- = 110 = 6
r-x = 101 = 5
r-- = 100 = 4
-wx = 011 = 3
--x = 001 = 1
no permission = 0 
