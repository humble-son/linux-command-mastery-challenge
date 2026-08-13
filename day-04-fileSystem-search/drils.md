_Find every .conf file under /etc, find every file larger than 1MB in /var, then report total disk usage
of /home and remaining free space on the root filesystem._

1. find /etc -name "\*.conf"
2. find /var -size +1M
3. du -h /home
4. df
