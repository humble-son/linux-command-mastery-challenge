_Create a group named devs, add two users to it, confirm membership with getent, remove one
member, then delete the group entirely_

1. sudo groupadd devs
2. sudo usermod -aG devs abassibrahim
3. sudo usermod -aG devs test
4. getent group devs
5. sudo gpasswd -d test devs
6. sudo groupdel devs
