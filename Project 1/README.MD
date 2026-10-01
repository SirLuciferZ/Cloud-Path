
### Part 1
  I installed VBox without any problem. 
  Then, I added a new VM and installed UBUNTU server 26.04 on it
  > A quick note that why I chose server over desktop: 
  >> UBUNTU server has no gui and is extremely lightweight compared to desktop version. most of the componies has the server version because cloud resources are valuable. Due   to the fact that UBUNTU server has the same foundation as any other UBUNTU linux distro, I can install the desktop GUI any time that i want using the `sudo apt install ubuntu-desktop` command.

### Part 2
  I installed ubuntu and set my username and password. also I installed ssh server, for the time that i want to control my server from other systems.
  the installation process took me a little time because the vbox did and unintended installation. but after some research, I fixed the problem. and now it works without any    problem.

### Part 3
  I logged in to my ubuntu. tested some commands to check everything is ok and running smoothly. the commands that I've used are:
```bash
hostnamectl
lsblk
ip a
```

### Part 4
  I connected to my VM server using ssh from my OS. It was easier than I thought. 
  > the purpose of this is that most of the time we connect to our server using our own clients. the servers are not close enough to work on them from their own CLI, maybe in another country, so we can access them from the company and work on them remotely.

### Part 5
I navigated through the folders and file. I learned some new commands such as:
```bash
cd
mkdir
ls
pwd
touch
cat
nano
echo
```

### Part 6
This time I tried using chmod and nano and sudo. i changed my hostname using `sudo nano /etc/hostname`.
I worked with nano and vim before so im not gonna have any problem using them and im quite familiar with them. i tried every number in chmod to see want happens. it was interesting. i tried to cd root but i couldnt enter it and it says permission denied. also when i wanted to nano hostname, i didnt put sudo , so it gave me a file unwrittable error. then i tried sudo and it worked. 

### Part 7
I updated my apps using `sudo apt update && sudo apt upgrade -y`
then I installed htop and fastfetch.
htop is like task manager on windows.
and fastfetch gave me all the system info.
> "Troubleshooting Win: Attempted to install neofetch but encountered a 'package not found' error (due to its recent deprecation in Ubuntu repos). Investigated using `apt search` and successfully installed the modern, faster alternative: fastfetch."

### Part 8
the new commands that i learned on linux today was ```bash 
`grep`, 
`less`, 
`find`, 
`head`, 
`rm`, 
`cp`, 
`mv` 
and `2>/dev/null` 
```
also on windows I learned ```bash 
`copy`, 
`dir`, 
`move`, 
`del`, 
`mkdir` (same as linux), 
`cd` (same as linux) 
and `pwd`
```
I also learned piping two commands together using `|` . 
