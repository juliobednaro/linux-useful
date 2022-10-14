# Get only users from /etc/passwd
cat /etc/passwd | cut -d: -f1

# MOTD - message of the day
cat /etc/update-motd.d/00-header

# Ubuntu version check
lsb_release -a

# Clear any file
cat /dev/null > file
