_Generate a SHA-256 checksum for a downloaded file to verify its integrity, make a file immutable
with chattr, then open only port 22 and port 443 on the firewall._

1. sha256sum script.sh > script.sha256
2. sha256sum -c script.sha256
3. sudo chattr +i script.sh
4. sudo ufw allow 443/tcp
5. sudo ufw allow 22/tcp
