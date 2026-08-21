_Create a new user with a home directory and Bash shell, set their password, add them to a
secondary group, rename the account, then remove it along with its home directory._

1. sudo useradd -m -s /bin/bash drills
2. sudo passwd drills
3. sudo usermod -aG sudo drills
4. sudo usermod -l test drills
5. sudo userdel -r test
