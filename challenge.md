## Question 1
Answer: I am hadiaemaanmalik. My home folder is /home/hadiaemaanmalik.
Commands: whoami, pwd

## Question 2
Answer: The server name is ubuntu. It runs <Ubuntu version, e.g. Ubuntu 24.04.3 LTS>.
Commands: hostname, cat /etc/os-release | head -2

## Question 3
Answer: The server has <total RAM> of RAM and <Avail> of free disk space.
Commands: free -h, df -h /

## Question 4
Answer: The users that can log in with bash are <names from grep output>.
Commands: grep bash /etc/passwd

## Question 5
Answer: <number> processes are running right now.
Commands: ps aux | wc -l

## Question 6
Answer: lab5user was created at <created time> and deleted at <deleted time>.
Commands: sudo grep lab5user /var/log/auth.log
