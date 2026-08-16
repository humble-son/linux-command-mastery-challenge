# Day 06: Reading and setting permissions

## Commands of the day

**1. ls -l**

This command is used to list files and directories in long format.

**2. chmod (+/-)**

This command is used to change the permission on a file by adding or subtracting a specific permission without touching others.

**3. chmod (=)**

This command is used to set permission to exactly what you specify.

**4. chmod 755**

This command is used to set permission in octal mode.

**5. chmod 644**

This command is used to set permission in octal mode.

**6. chmod 600**

This command is used to set permission in octal mode. It restricts a file so only the owner can read and write, no access for group and others.

**7. chmod -R**

This command is used to set permission in octal mode for everything in a directory.

**8. umask**

This command is used to sets the default permission mask applied automatically to newly created files and directories.

**9. umask -S**

This command displays the current umask in human-readable symbolic form.

**10. stat -c '%A %U %G**

This command is used show detail about a file and `-c` format the output to show only what you desire.

`%A` - permission string
`%U` - owner's name
`%G` - owner's group name
`%a` - permission in octal mode
`%n` - file name
