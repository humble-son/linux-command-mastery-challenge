# Day 07: Ownership and Special Bits

## Commands of the day

**1. chown**

This command is used to change the owner of a file in linux.

**2. chown user:group**

This command is used to change both the owner and the group in one command.

**3. chown -R**

This command is used to apply `chown` to a directory and all directories inside of it.

**4. chgrp**

This command is used to change the group of a file.

**5. chmod u+s**

This command is used to make an executable run with the file's owners priviledges instead of the priviledges of the user who launched it.

**6. chmod g+s**

This command on a directory is used to for making any new file or directory inherit the directory's group

**7. chmod +t**

This command is used to restricts file deletion.

**8. find -perm /4000**

This command is used find the search the filesystems for files matching a specific permission.

**9. gatfacle**

This command displays file's access control list.

**10 setfacl -m**

This command is used to add or change specific ACL.
