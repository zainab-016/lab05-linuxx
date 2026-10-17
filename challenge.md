## Question 1: Current identity and path
- **Answer:** I am logged in as zainab-016. My home folder path is /home/zainab-016.
- **Commands used:** `whoami`, `pwd`

## Question 2: Host platform name and OS distribution
- **Answer:** The server name is ubuntu. It is running Ubuntu 24.04.1 LTS.
- **Commands used:** `hostname`, `cat /etc/os-release`

## Question 3: Available RAM limits and free disk capacity
- **Answer:** The server has 1.6Gi total memory. There is 4.3G of disk space available on the root partition.
- **Commands used:** `free -h`, `df -h /`

## Question 4: Login shell access list
- **Answer:** zainab-016:x:1000:1000:zainab-016,,,:/home/zainab-016:/bin/bash
- **Commands used:** `grep "bash" /etc/passwd`

## Question 5: Total active running processes
- **Answer:** There are 220 processes running.
- **Commands used:** `ps aux | wc -l`

## Question 6: Target profile creation and deletion timestamps
- **Answer:** Creation time: Oct 17 08:33. Deletion time: Oct 17 08:45.
- **Commands used:** `sudo grep lab5user /var/log/auth.log`
