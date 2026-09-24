# Linux Fundamentals for Cybersecurity

A foundational understanding of Linux is critical for navigating systems, analyzing configurations, and managing services during security assessments.

## System & Process Monitoring
Understanding what is running on a system is the first step in identifying anomalies or managing resources.
* **View running processes:** `ps aux`
* **Check system resource usage:** `top` or `htop`
* **Kill an unresponsive process:** `kill -9 <PID>`

## File Management & Navigation
Navigating the file system efficiently allows for rapid inspection of logs and configurations.
* **List files (including hidden):** `ls -la`
* **Find a specific file:** `find / -name "filename"`
* **Read file contents:** `cat filename` or `less filename`

## Permissions & Ownership
In security, understanding who has access to read, write, or execute a file is paramount for privilege escalation and access control.
* **Check file permissions:** `ls -la`
* **Change file permissions:** `chmod 755 filename`
* **Change file owner:** `chown user:group filename`

## Network Configuration Basics
Verifying how the machine is communicating with the network.
* **Check IP address:** `ip a` or `ifconfig`
* **Check open ports/connections:** `netstat -tulnp` or `ss -tulwn`
