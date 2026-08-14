_CHECKPOINT. Create a symbolic link to a config file, resolve its real path, print a two-level tree
of /etc, and explain to a peer, in your own words, the difference between a hard link and a symbolic
link._

1. ln -s /etc/sudo.conf symlink
2. readlink symlink
3. tree -L 2 /etc
