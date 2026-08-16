_Create a script file and set it to rwxr-xr-x using all three chmod methods (relative, assignment,
octal) in turn, confirming the result with ls -l after each change._

1. chmod 755 script.sh
2. chmod u=rwx,g=rx,o-rx
3. chmod o+x script2.sh
4. chmod o-w script2.sh
5. chmod g+x script2.sh
6. chmod u+x script2.sh
