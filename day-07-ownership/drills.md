_Create a shared project folder, apply the SGID bit so new files inherit its group, then audit the
whole system for unexpected SUID binaries._

1. mkdir sharedDir
2. chmod g+s sharedDir
3. find / -perm -4000
