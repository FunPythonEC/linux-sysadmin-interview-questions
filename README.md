Linux System Administrator/DevOps Interview Questions
====================================================

A collection of linux sysadmin/devops interview questions. Feel free to contribute via pull requests, issues or email messages.


## <a name='toc'>Table of Contents</a>

  1. [Contributors](#contributors)
  1. [General Questions](#general)
  1. [Simple Linux Questions](#simple)
  1. [Medium Linux Questions](#medium)
  1. [Hard Linux Questions](#hard)
  1. [Expert Linux Questions](#expert)
  1. [Networking Questions](#network)
  1. [MySQL Questions](#mysql)
  1. [DevOps Questions](#devop)
  1. [Fun Questions](#fun)
  1. [Demo Time](#demo)
  1. [Other Great References](#references)


#### [[⬆]](#toc) <a name='contributors'>Contributors:</a>

* [moregeek](https://github.com/moregeek)
* [typhonius](https://github.com/typhonius)
* [schumar](https://github.com/schumar)
* [negesti](https://github.com/negesti)
* peter
* [andreashappe](https://github.com/andreashappe)
* [quatrix](https://github.com/quatrix)
* [biyanisuraj](https://github.com/biyanisuraj)
* [pedroguima](https://github.com/pedroguima)
* Ben
* [bharatnc](https://github.com/bharatnc)
* [FunPython](https://github.com/FunPythonEC) - [ZioGuillo](https://github.com/zioguillo)


#### [[⬆]](#toc) <a name='general'>General Questions:</a>

* What did you learn yesterday/this week?
* Talk about your preferred development/administration environment. (OS, Editor, Browsers, Tools etc.)
* Tell me about the last major Linux project you finished.
* Tell me about the biggest mistake you've made in [some recent time period] and how you would do it differently today. What did you learn from this experience?
* Why we must choose you?
* What function does DNS play on a network?
The Domain Name System (DNS) is an important part of the internet, providing a way to map names (a website you're seeking) to numbers (the address for the website). Anything connected to the internet - laptops, tablets, mobile phones, websites - has an Internet Protocol (IP) address.
* What is HTTP?
HTTP is the protocol used to transfer data over the internet. HTTP is a request/response protocol.
* What is an HTTP proxy and how does it work?
An HTTP proxy is a server that sits between the client and the server. It is responsible for the transfer of data between the client and the server.
* Describe briefly how HTTPS works.
HTTPS is a protocol that is used to transfer data over the internet. It is a request/response protocol.
* What is SMTP? Give the basic scenario of how a mail message is delivered via SMTP.
SMTP is a protocol used to send email messages.
* What is RAID? What is RAID0, RAID1, RAID5, RAID10?
RAID is a method of storing multiple disks in a single drive. RAID0 is a type of RAID that uses a single drive to store all the data. RAID1 is a type of RAID that uses a single drive to store all the data. RAID5 is a type of RAID that uses multiple drives to store all the data. RAID10 is a type of RAID that uses multiple drives to store all the data.
* What is a level 0 backup? What is an incremental backup?
Level 0 backups are a type of backup that stores all the data on the hard drive. Incremental backups are a type of backup that stores only the data that has changed since the last backup.
* Describe the general file system hierarchy of a Linux system.
The file system hierarchy is a way of organizing files and folders in a Linux system.
* Which difference have between public and private SSH key?
Public SSH keys are used to log into a server without a password. Private SSH keys are used to log into a server with a password.


#### [[⬆]](#toc) <a name='simple'>Simple Linux Questions:</a>

* What is the name and the UID of the administrator user?
The administrator user is the user with the highest UID.
* How to list all files, including hidden ones, in a directory?
The command `ls -a` lists all files in a directory, including hidden files.
* What is the Unix/Linux command to remove a directory and its contents?
The command `rm -rf` removes a directory and its contents.
* Which command will show you free/used memory? Does free memory exist on Linux?
The command `free` shows free/used memory.
* How to search for the string "my konfu is the best" in files of a directory recursively?
The command `grep -r "my konfu is the best"` searches for the string "my konfu is the best" in files of a directory recursively.
* How to connect to a remote server or what is SSH?
SSH is a command used to connect to a remote server.
* How to get all environment variables and how can you use them?
The command `env` shows all environment variables.
* I get "command not found" when I run ```ifconfig -a```. What can be wrong?
The command `ifconfig -a` is a command that shows all network interfaces.
* What happens if I type TAB-TAB?
The command `TAB-TAB` is a command that shows all commands that start with the same letters as the command typed so far.
* What command will show the available disk space on the Unix/Linux system?
The command `df` shows the available disk space on the Unix/Linux system.
* What commands do you know that can be used to check DNS records?
The commands `dig` and `host` can be used to check DNS records.
* What Unix/Linux commands will alter a files ownership, files permissions?
The commands `chown` and `chmod` can be used to alter a files ownership, files permissions.
* What does ```chmod +x FILENAME``` do?
The command ```chmod +x FILENAME``` makes a file executable.
* What does the permission 0750 on a file mean?
The permission 0750 on a file means that the file is readable, writable and executable by the owner, readable and writable by the group and readable and writable by others.
* What does the permission 0750 on a directory mean?
The permission 0750 on a directory means that the directory is readable, writable and executable by the owner, readable and writable by the group and readable and writable by others.
* How to add a new system user without login permissions?
The command `useradd` can be used to add a new system user without login permissions.
* How to add/remove a group from a user?
The command `usermod` can be used to add/remove a group from a user.
* What is a bash alias?
A bash alias is a command that can be used instead of another command.
* How do you set the mail address of the root/a user?
The command `echo "root:root@localhost" >> /etc/aliases` can be used to set the mail address of the root/a user.
* What does CTRL-c do?
The command `CTRL-c` can be used to stop a process.
* What does CTRL-d do?
The command `CTRL-d` can be used to stop a process.
* What does CTRL-z do?
The command `CTRL-z` can be used to stop a process.
* What is in /etc/services?
The file /etc/services contains a list of all services and their ports.
* How to redirect STDOUT and STDERR in bash? (> /dev/null 2>&1)
The command `> /dev/null 2>&1` redirects STDOUT and STDERR in bash.
* What is the difference between UNIX and Linux.
The difference between UNIX and Linux is that UNIX is a family of operating systems, while Linux is a single operating system.
* What is the difference between Telnet and SSH?
The difference between Telnet and SSH is that Telnet is a client-server protocol while SSH is a protocol that allows you to connect to a server from a client.
* Explain the three load averages and what do they indicate. What command can be used to view the load averages?
The load averages are the average number of processes in the system. The command `uptime` can be used to view the load averages.
* Can you name a lower-case letter that is not a valid option for GNU ```ls```?
No, there is no lower-case letter that is not a valid option for GNU ```ls```.
* What is a Linux kernel module?
A Linux kernel module is a piece of code that is loaded into the kernel.
* Walk me through the steps in booting into single user mode to troubleshoot a problem.
The steps are: 
1. Boot into single user mode. 
2. Run ```ls``` and see if it works. 
3. Run ```ls -a``` and see if it works. 
4. Run ```ls -l``` and see if it works. 
5. Run ```ls -a -l``` and see if it works. 
6. Run ```ls -a -l -R``` and see if it works. 
7. Run ```ls -a -l -R /``` and see if it works. 
8. Run ```ls -a -l -R /dev``` and see if it works. 
9. Run ```ls -a -l -R /dev/null``` and see if it works. 
10. Run ```ls -a -l -R /dev/null/null``` and see if it works.

* Walk me through the steps you'd take to troubleshoot a 404 error on a web application you administer.
The steps are: 

* What is ICMP protocol? Why do you need to use?
ICMP protocol is used to send messages to other computers.

#### [[⬆]](#toc) <a name='medium'>Medium Linux Questions:</a>

* What do the following commands do and how would you use them?
 * ```tee``` - copies the content of a file to a new file.
 * ```awk```  - is a command that can be used to process text files.
 * ```tr``` - is a command that can be used to process text files.
 * ```cut``` - is a command that can be used to process text files.
 * ```tac``` - is a command that can be used to process text files.
 * ```curl``` - is a command that can be used to download files.
 * ```wget``` - is a command that can be used to download files.
 * ```watch``` - is a command that can be used to monitor a file.
 * ```head``` - is a command that can be used to view the first lines of a file.
 * ```tail``` - is a command that can be used to view the last lines of a file.
 * ```less``` - is a command that can be used to view a file.
 * ```cat``` - is a command that can be used to view a file.
 * ```touch``` - is a command that can be used to create a file.
 * ```sar``` - is a command that can be used to monitor system activity.
 * ```netstat``` - is a command that can be used to monitor network activity.
 * ```tcpdump``` - is a command that can be used to monitor network activity.
 * ```lsof``` - is a command that can be used to monitor network activity.
* What does an ```&``` after a command do?
The command ```&``` runs the command in the background.
* What does ```& disown``` after a command do?
The command ```& disown``` disowns the command.
* What is a packet filter and how does it work?
A packet filter is a program that can be used to filter network traffic.
* What is Virtual Memory?
Virtual Memory is a concept that is used to manage memory.
* What is swap and what is it used for?
Swap is a concept that is used to manage memory.
* What is an A record, an NS record, a PTR record, a CNAME record, an MX record?
An A record is an A record that contains the IP address of a host.
* Are there any other RRs and what are they used for?
There are other RRs and they are used to describe other records.
* What is a Split-Horizon DNS?
Split-Horizon DNS is a concept that is used to manage DNS.
* What is the sticky bit?
The sticky bit is a concept that is used to manage files.
* What does the immutable bit do to a file?
The immutable bit does to a file that the file cannot be altered.
* What is the difference between hardlinks and symlinks? What happens when you remove the source to a symlink/hardlink?
Hardlinks are used to create a link to a file.
* What is an inode and what fields are stored in an inode?
An inode is a concept that is used to manage files.
* How to force/trigger a file system check on next reboot?
The command `/sbin/e2fsck -f -y /dev/sda1` can be used to force/trigger a file system check on next reboot.
* What is SNMP and what is it used for?
SNMP is a concept that is used to manage network devices.
* What is a runlevel and how to get the current runlevel?
A runlevel is a concept that is used to manage system services.
* What is SSH port forwarding?
SSH port forwarding is a concept that is used to manage network devices.
* What is the difference between local and remote port forwarding?
The difference between local and remote port forwarding is that local port forwarding is used to forward ports from a local machine to a remote machine.
* What are the steps to add a user to a system without using useradd/adduser?
The steps to add a user to a system without using useradd/adduser are: 1. Create a user account 2. Create a home directory 3. Create a shell 4. Create a password 5. Create a group 6. Add the user to the group.
* What is MAJOR and MINOR numbers of special files?
MAJOR and MINOR numbers of special files are used to manage special files.
* Describe the mknod command and when you'd use it.
The mknod command is used to create special files.
* Describe a scenario when you get a "filesystem is full" error, but 'df' shows there is free space.
The scenario is when you get a "filesystem is full" error, but 'df' shows there is free space.
* Describe a scenario when deleting a file, but 'df' not showing the space being freed.
The scenario is when deleting a file, but 'df' not showing the space being freed. 
* Describe how 'ps' works.
The 'ps' command is used to manage processes.
* What happens to a child process that dies and has no parent process to wait for it and what’s bad about this?
The child process that dies and has no parent process to wait for it and what’s bad about this is that the child process is orphaned.
* Explain briefly each one of the process states.
The process states are: 
  * Running
  * Sleeping  (sleeping, waiting for an event to happen)
  * Waiting  (waiting for a child process to finish)
  * Zombie  (a child process that has finished, but is waiting for its parent to finish)
  * Stopped  (a child process that has finished, but is waiting for its parent to finish)
  * Dead  (a child process that has finished, and is waiting for its parent to finish)
* How to know which process listens on a specific port?
The command `netstat -an | grep LISTEN` can be used to know which process listens on a specific port.
* What is a zombie process and what could be the cause of it?
A zombie process is a process that has finished, but is waiting for its parent to finish.
* You run a bash script and you want to see its output on your terminal and save it to a file at the same time. How could you do it?
- - 
* What is the difference between a pipe and a redirection?
The difference between a pipe and a redirection is that a pipe is used to connect two processes.
* Explain what echo "1" > /proc/sys/net/ipv4/ip_forward does.
The echo "1" > /proc/sys/net/ipv4/ip_forward does set the ip_forward to 1.
* Describe briefly the steps you need to take in order to create and install a valid certificate for the site https://foo.example.com.
The steps you need to take in order to create and install a valid certificate for the site https://foo.example.com are: 1. Create a private key 2. Create a certificate signing request 3. Create a certificate 4. Install the certificate on the server. 
* Can you have several HTTPS virtual hosts sharing the same IP?
You can have several HTTPS virtual hosts sharing the same IP.
* What is a wildcard certificate?
A wildcard certificate is a certificate that can be used to match any domain.
* Which Linux file types do you know?
The Linux file types do you know are: - - 

* What is the difference between a process and a thread? And parent and child processes after a fork system call?
The difference between a process and a thread is that a process is a thread of execution.
* What is the difference between exec and fork?
The difference between exec and fork is that exec is used to execute a new program.
* What is "nohup" used for?
The "nohup" used for is to run a program in the background.
* What is the difference between these two commands?
 * ```myvar=hello``` - is a command that can be used to set a variable.
 * ```export myvar=hello``` - is a command that can be used to set a variable.
* How many NTP servers would you configure in your local ntp.conf?
The NTP servers would you configure in your local ntp.conf are:
  * ntp.ubuntu.com  (United States)  (default)  (preferred)  (synchronized) (synchronized)  
  * ntp.ubuntu.com  (United Kingdom)  (default)  (preferred)  (synchronized) (synchronized)

* What does the column 'reach' mean in ```ntpq -p``` output?
The column 'reach' means that the server is reachable.
* You need to upgrade kernel at 100-1000 servers, how you would do this?
You would use the command: 
```
for i in $(seq 100 1000); do
  echo "Upgrading server $i"
  ssh root@$i "apt-get update && apt-get upgrade -y"
done
```

* How can you get Host, Channel, ID, LUN of SCSI disk?
You can use the command:
```
for i in $(ls /dev/sd*); do
 echo "Host: $(cat /sys/block/$i/device/host) Channel: $(cat /sys/block/$i/device/channel) ID: $(cat /sys/block/$i/device/id) LUN: $(cat /sys/block/$i/device/lun)"
done
```

* How can you limit process memory usage?
You can use the command:
```
ulimit -v 1000000
ulimit -v unlimited
```

* What is bash quick substitution/caret replace(^x^y)?
The bash quick substitution/caret replace(^x^y) is used to replace a string with another string.
* Do you know of any alternative shells? If so, have you used any?
The alternative shells are:
bash
dash
ksh
mksh
pdksh
zsh

* What is a tarpipe (or, how would you go about copying everything, including hardlinks and special files, from one server to another)?
The tarpipe (or, how would you go about copying everything, including hardlinks and special files, from one server to another) is to use the command:
```
tar -cpf - / | ssh root@destination "tar -xpf -"
```

* How can you tell if the httpd package was already installed?
You can use the command:
```
dpkg -s httpd
```

* How can you list the contents of a package?
You can use the command:
```
dpkg -L <package>
```

* How can you determine which package is better: openssh-server-5.3p1-118.1.el6_8.x86_64 or openssh-server-6.6p1-1.el6.x86_64 ?
You can use the command:
```
dpkg -l openssh-server
```

* Can you explain to me the difference between block based, and object based storage?
The difference between block based, and object based storage is that block based storage is used to store data in a file system.

#### [[⬆]](#toc) <a name='hard'>Hard Linux Questions:</a>

* What is a tunnel and how you can bypass a http proxy?
A tunnel is a connection between two servers. You can bypass a http proxy by using the command: 
```
ssh -D 8080 -N
```

* What is the difference between IDS and IPS?
The difference between IDS and IPS is that IDS is used to identify the source of the traffic. IPS is used to identify the destination of the traffic. 
* What shortcuts do you use on a regular basis?
The shortcuts do you use on a regular basis are:
  * `Ctrl+C` - to interrupt a process
  * `Ctrl+Z` - to suspend a process
  * `Ctrl+D` - to exit a shell
  * `Ctrl+L` - to clear the screen
  * `Ctrl+R` - to redraw the screen
  * `Ctrl+S` - to save the screen
  * `Ctrl+Q` - to exit the terminal
  * `Ctrl+F` - to search
  * `Ctrl+H` - to search backwards
  * `Ctrl+P` - to go up one directory
  * `Ctrl+N` - to go down one directory
  * `Ctrl+T` - to create a new tab
  * `Ctrl+W` - to close a tab
  * `Ctrl+U` - to delete a word
  * `Ctrl+V` - to paste
  * `Ctrl+X` - to cut
  * `Ctrl+Y` - to redo
  * `Ctrl+Z` - to suspend a process
  * `Ctrl+A` - to select all
  * `Ctrl+B` - to move backward one word
  * `Ctrl+E` - to move forward one word
  * `Ctrl+F` - to move forward one character
  * `Ctrl+G` - to move to the beginning of the line
  * `Ctrl+H` - to move backward one character
  * `Ctrl+J` - to move down one line
  * `Ctrl+K` - to delete to end of line
  * `Ctrl+L` - to clear the screen
  * `Ctrl+M` - to move down one line
  * `Ctrl+N` - to move forward one line
  * `Ctrl+O` - to open a file
  * `Ctrl+P` - to move backward one line
  * `Ctrl+Q` - to quit
  * `Ctrl+R` - to redraw the screen
  * `Ctrl+S` - to save the screen
  * `Ctrl+T` - to create a new tab
  * `Ctrl+U` - to delete a word
  * `Ctrl+V` - to paste
  * `Ctrl+W` - to close a tab
  * `Ctrl+X` - to cut
  * `Ctrl+Y` - to redo
  * `Ctrl+Z` - to suspend a process
  * `Ctrl+[` - to move backward one word
  * `Ctrl+]` - to move forward one word

* What is the Linux Standard Base?
The Linux Standard Base is a set of standards that are used to ensure that Linux systems are compliant with the latest security and performance standards.
* What is an atomic operation?
An atomic operation is an operation that is performed atomically.
* Your freshly configured http server is not running after a restart, what can you do?
You can use the command:
```
service httpd restart
```

* What kind of keys are in ~/.ssh/authorized_keys and what it is this file used for?
The ~/.ssh/authorized_keys file is used to store the public keys of the authorized users. The file is used to allow the users to log in to the server without entering the password. 

* I've added my public ssh key into authorized_keys but I'm still getting a password prompt, what can be wrong?
The ~/.ssh/authorized_keys file is used to store the public keys of the authorized users. The file is used to allow the users to log in to the server without entering the password.  If you are getting a password prompt, it is because the ~/.ssh/authorized_keys file is not being read by the ssh daemon.

* Did you ever create RPM's, DEB's or solaris pkg's?
Yes, I've created RPM's, DEB's and solaris pkg's.  I've also used the command: `rpm -qa` to list all the packages installed on the system.  I've also used the command: `dpkg -l` to list all the packages installed on the system. I've also used the command: `pkg list` to list all the packages installed on the system. I've also used the command: `pkg list -a` to list all the packages installed on the system. 

* What does ```:(){ :|:& };:``` do on your system?
The :(){ :|:& };: is a shell function that is used to run a command in the background.  It is used to run a command in the background.
* How do you catch a Linux signal on a script?
You can use the command:
```
trap "echo 'Signal caught'" SIGINT
```

* Can you catch a SIGKILL?
Yes, you can catch a SIGKILL. You can use the command: 
```
trap "echo 'Signal caught'" SIGKILL
```

* What's happening when the Linux kernel is starting the OOM killer and how does it choose which process to kill first?
The Linux kernel is starting the OOM killer and how does it choose which process to kill first is that the kernel is trying to kill the processes in the order of their memory usage.

* Describe the linux boot process with as much detail as possible, starting from when the system is powered on and ending when you get a prompt.
The Linux kernel is starting the OOM killer and how does it choose which process to kill first is that the kernel is trying to kill the processes in the order of their memory usage.

* What's a chroot jail?
A chroot jail is a jail that is used to isolate a user from the rest of the system.  The user can only access the files that are in the chroot jail.
* When trying to umount a directory it says it's busy, how to find out which PID holds the directory?
You can use the command:
```
lsof -p <PID>
```

* What's LD_PRELOAD and when it's used?
LD_PRELOAD is used to load a library before the program is executed.  LD_PRELOAD is used to load a library before the program is executed.  The library is loaded before the program is executed.  
* You ran a binary and nothing happened. How would you debug this?
You can use the command:
```
gdb <binary>
```

* What are cgroups? Can you specify a scenario where you could use them?
Cgroups are used to control the resources that are used by a process.  You can specify a scenario where you could use them.  For example, you could specify a scenario where you could use cgroups to control the memory usage of a process.  You could specify a scenario where you could use cgroups to control the CPU usage of a process.  You could specify a scenario where you could use cgroups to control the disk usage of a process.  You could specify a scenario where you could use cgroups to control the network usage of a process.  You could specify a scenario where you could use cgroups to control the number of processes that are running on a system.  You could specify a scenario where you could use cgroups to control the number of threads that are running on a process.  You could specify a scenario where you could use cgroups to control the number of files that are open on a process.
* How can you remove/delete a file with file-name consisting of only non-printable/non-type-able characters?
You can use the command:
```
rm -f <file-name>
```

* How can you increase or decrease the priority of a process in Linux?
You can use the command:
```
renice <priority> <PID>
```

#### [[⬆]](#toc) <a name='expert'>Expert Linux Questions:</a>

* A running process gets ```EAGAIN: Resource temporarily unavailable``` on reading a socket. How can you close this bad socket/file descriptor without killing the process?
You can use the command:
```
lsof -p <PID>
```

* What do you control with swapiness?
You control with swapiness what the system will use to swap out the pages.  The system will use swapiness to determine how much memory it will use to swap out the pages.
* How do you change TCP stack buffers? How do you calculate it?
You can use the command:
```
sysctl -a | grep net.core
```
  
* What is Huge Tables? Why isn't it enabled by default? Why and when use it?
Huge Tables is a feature that allows the system to allocate more memory for the kernel.  Huge Tables is a feature that allows the system to allocate more memory for the kernel.  Huge Tables is not enabled by default.
* What is LUKS? How to use it?
LUKS is a Linux Unified Key Setup.  


#### [[⬆]](#toc) <a name='network'>Networking Questions:</a>

* What is localhost and why would ```ping localhost``` fail?
localhost is the name of the local host.
* What is the similarity between "ping" & "traceroute" ? How is traceroute able to find the hops.
The "ping" command is used to check if a host is alive.  The "traceroute" command is used to find the hops. The "traceroute" command is used to find the hops.  
* What is the command used to show all open ports and/or socket connections on a machine?
The command used to show all open ports and/or socket connections on a machine is:
```
lsof -i
netstat -natupx
ss -lptuxa
```

* Is 300.168.0.123 a valid IPv4 address?
No, IPv4 addresses are canonically represented in dot-decimal notation, which consists of four decimal numbers, each ranging from 0 to 255, separated by dots, e.g., 172.16.254.1. Each part represents a group of 8 bits (octet) of the address. So 2 ** 8 = 256(255) is a max number for each octet.
  
* Which IP ranges/subnets are "private" or "non-routable" (RFC 1918)?
The Internet Assigned Numbers Authority (IANA) has reserved the following three blocks of the IP address space for private internets:
     10.0.0.0        -   10.255.255.255  (10/8 prefix)
     172.16.0.0      -   172.31.255.255  (172.16/12 prefix)
     192.168.0.0     -   192.168.255.255 (192.168/16 prefix)

* What is a VLAN?
A virtual LAN (VLAN) is any broadcast domain that is partitioned and isolated in a computer network at the data link layer (OSI layer 2).
To subdivide a network into virtual LANs, one configures a network switch or router. Simpler network devices can only partition per physical port (if at all), in which case each VLAN is connected with a dedicated network cable (and VLAN connectivity is limited by the number of hardware ports available). More sophisticated devices can mark packets through tagging, so that a single interconnect (trunk) may be used to transport data for multiple VLANs. Since VLANs share bandwidth, a VLAN trunk might use link aggregation and/or quality of service prioritization to route data efficiently.

* What is ARP and what is it used for?
ARP is used to resolve the MAC address of a host.

* What is the difference between TCP and UDP?
The TCP and UDP are two different protocols.  The TCP is a reliable, connection-oriented protocol.  The UDP is a connectionless protocol.  
* What is the purpose of a default gateway?
A default gateway is used to route traffic to the internet.  
* What is command used to show the routing table on a Linux box?
The command used to show the routing table on a Linux box is:
```
route -n
```

* A TCP connection on a network can be uniquely defined by 4 things. What are those things?
A TCP connection on a network can be uniquely defined by 4 things.  The 4 things are:
* Source IP address
* Destination IP address
* Source port
* Destination port

* When a client running a web browser connects to a web server, what is the source port and what is the destination port of the connection?
The source port is the port number that the client is using to connect to the web server.  The destination port is the port number that the web server is using to connect to the client.  
* How do you add an IPv6 address to a specific interface?
You can use the command:
```
ip addr add <IPv6-address> dev <interface>
```

* You have added an IPv4 and IPv6 address to interface eth0. A ping to the v4 address is working but a ping to the v6 address gives you the response ```sendmsg: operation not permitted```. What could be wrong?
The IPv6 address is not added to the interface. The IPv6 address is not added to the interface.

* What is SNAT and when should it be used?
SNAT is used to map the source IP address of a packet to a specific IP address.  SNAT is used to map the source IP address of a packet to a specific IP address.  
* Explain how could you ssh login into a Linux system that DROPs all new incoming packets using a SSH tunnel.
You can use the command:
```
iptables -A INPUT -p tcp --dport 22 -j DROP
```

* How do you stop a DDoS attack?
You can use the command:
```
iptables -A INPUT -p tcp --dport 22 -j DROP
```

* How can you see content of an ip packet?
You can use the command:
```
tcpdump -i eth0 -n -s 0 -A -v -X
```

* What is IPoAC (RFC 1149)?
IPoAC is a protocol that is used to provide IPv4 address configuration.   
* What will happen when you bind port 0?
When you bind port 0, the kernel will assign a random port number.  



#### [[⬆]](#toc) <a name='mysql'>MySQL questions:</a>

* How do you create a user?
You can use the command:
```
mysql -u root -p
```   
and then type:  ```CREATE USER '<username>'@'localhost' IDENTIFIED BY '<password>';```

* How do you provide privileges to a user?
You can use the command:
```
mysql -u root -p
```   
and then type:  ```GRANT ALL PRIVILEGES ON *.* TO '<username>'@'localhost' WITH GRANT OPTION;```

* What is the difference between a "left" and a "right" join?
The "left" join is used to join two tables.  The "right" join is used to join two tables.  
* Explain briefly the differences between InnoDB and MyISAM.
InnoDB is a transactional storage engine.  MyISAM is a non-transactional storage engine.
* Describe briefly the steps you need to follow in order to create a simple master/slave cluster.
You need to create a master and slave.  
* Why should you run "mysql_secure_installation" after installing MySQL?
You should run "mysql_secure_installation" after installing MySQL.  
* How do you check which jobs are running?
You can use the command:
```
ps -ef | grep mysql
```  
* How would you take a backup of a MySQL database?
You can use the command:
```
mysqldump -u root -p <database> > <filename>.sql
```


#### [[⬆]](#toc) <a name='devop'>DevOps Questions:</a>

* Can you describe your workflow when you create a script?
You can describe your workflow when you create a script and then run it in the terminal or in the browser or in the cloud.  
* What is GIT?
GIT is a version control system.
* What is a dynamically/statically linked file?
A dynamically/statically linked file is a file that is linked to a shared library.   
* What does "./configure && make && make install" do?
"./configure && make && make install" is used to compile and install a program.
* What is puppet/chef/ansible used for?
Puppet is used to create and manage infrastructure.  Chef is used to create and manage infrastructure.  Ansible is used to create and manage infrastructure.
* What is Nagios/Zenoss/NewRelic used for?
Nagios is used to monitor infrastructure.  Zenoss is used to monitor infrastructure.  NewRelic is used to monitor infrastructure.
* What is Jenkins/TeamCity/GoCI used for?
Jenkins is used to build and deploy infrastructure.  TeamCity is used to build and deploy infrastructure.  GoCI is used to build and deploy infrastructure.
* What is the difference between Containers and VMs?
Containers are used to run applications.  VMs are used to run applications.   
* How do you create a new postgres user?
You can use the command:
```
createuser -s <username>
```

* What is a virtual IP address?
A virtual IP address is an IP address that is assigned to a container.
* What is a cluster?
A cluster is a group of computers that are connected to a network.  
* How do you print all strings of printable characters present in a file?
You can use the command:
```
strings <filename>
```
    
* How do you find shared library dependencies?
You can use the command:
```
ldd <filename>
```

* What is Automake and Autoconf?
Automake is used to generate Makefiles.  Autoconf is used to generate configure scripts.  
* What is a Dockerfile?
A Dockerfile is a file that is used to build a Docker image.
* ./configure shows an error that libfoobar is missing on your system, how could you fix this, what could be wrong?
You can use the command:
```
sudo apt-get install libfoobar
```    
and then run the command: ```./configure``` again.

* What are the advantages/disadvantages of script vs compiled program?
Scripts are easier to understand.  Compiled programs are easier to understand.   !!!  
* What's the relationship between continuous delivery and DevOps?
Continuous delivery is used to deliver software to customers.  DevOps is used to deliver software to customers.   !!!   !!! 
* What is the difference between a "master" and a "slave"?
A master is used to create a cluster.  A slave is used to create a cluster.
* What are the important aspects of a system of continuous integration and deployment?
Continuous integration is used to deliver software to customers.  Deployment is used to deliver software to customers.  
* How would you enable network file sharing within AWS that would allow EC2 instances in multiple availability zones to share data?
You can use the command:
```
sudo apt-get install nfs-kernel-server
```
and then run the command: ```sudo service nfs-kernel-server start```


#### [[⬆]](#toc) <a name='fun'>Fun Questions:</a>

* A careless sysadmin executes the following command: ```chmod 444 /bin/chmod ``` - what do you do to fix this?
You can use the command:
```
sudo chmod 755 /bin/chmod
```

* I've lost my root password, what can I do?
You can use the command:
```
sudo passwd
```

* I've rebooted a remote server but after 10 minutes I'm still not able to ssh into it, what can be wrong?
You can use the command:
```
sudo service ssh start
```

* If you were stuck on a desert island with only 5 command-line utilities, which would you choose?
You can use the command:
```
sudo apt-get install tree wget curl less vim  # vim is the best choice because it is the most powerful editor.
```

* You come across a random computer and it appears to be a command console for the universe. What is the first thing you type?
You can type:
```
universe
```

* Tell me about a creative way that you've used SSH?
You can use the command:
```
ssh -X <username>@<hostname>
```

* You have deleted by error a running script, what could you do to restore it?
You can use the command:
```
sudo cp <filename> /usr/local/bin/
```
    
* What will happen on 19 January 2038?
You can use the command:  ```sudo date -s '2038-01-19 00:00:00'```   !!!

* How to reboot server when reboot command is not responding?
You can use the command:
```
sudo reboot
```
        


#### [[⬆]](#toc) <a name='demo'>Demo Time:</a>

* Unpack test.tar.gz without man pages or google.

* Remove all "*.pyc" files from testdir recursively?   

* Search for "my konfu is the best" in all *.py files. 

* Replace the occurrence of "my konfu is the best" with "I'm a linux jedi master" in all *.txt files.

* Test if port 443 on a machine with IP address X.X.X.X is reachable.

* Get http://myinternal.webserver.local/test.html via telnet.
* How to send an email without a mail client, just on the command line?
* Write a ```get_prim``` method in python/perl/bash/pseudo.
* Find all files which have been accessed within the last 30 days.
* Explain the following command ```(date ; ps -ef | awk '{print $1}' | sort | uniq | wc -l ) >> Activity.log```
* Write a script to list all the differences between two directories.
* In a log file with contents as ```<TIME> : [MESSAGE] : [ERROR_NO] - Human readable text``` display summary/count of specific error numbers that occurred every hour or a specific hour.


#### [[⬆]](#toc) <a name='references'>Other Great References:</a>

Some questions are 'borrowed' from other great references like:

* https://github.com/darcyclarke/Front-end-Developer-Interview-Questions
* https://github.com/kylejohnson/linux-sysadmin-interview-questions/blob/master/test.md
* http://slideshare.net/kavyasri790693/linux-admin-interview-questions
