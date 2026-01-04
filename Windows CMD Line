🖥️ Windows Command Line Fundamentals – Hands-On Lab
📘 Overview
This repository documents my hands-on learning and practical use of the Windows Command Line (cmd.exe) through a TryHackMe lab environment.
The goal of this project was to build command-line fluency for system administration, troubleshooting, and cybersecurity use cases—especially in scenarios where graphical interfaces are unavailable, restricted, or inefficient.
Rather than focusing on memorizing commands, this lab emphasized understanding what information the CLI reveals, how it supports incident response, and why it remains a critical skill for defenders and attackers alike.

🧠 Why the Command Line Matters
While graphical user interfaces (GUIs) are intuitive, command-line interfaces (CLIs) offer major advantages:
Speed & efficiency — no mouse, no menus
Lower resource usage — ideal for servers and cloud systems
Automation — scripting repetitive tasks
Remote management — SSH access even on slow networks
Visibility — direct insight into system and network behavior
In cybersecurity and SOC environments, CLI access is often the only way to investigate or respond to an incident.

🧩 Lab Environment
Platform: TryHackMe
Target OS: Windows Server 2019
Access Method: SSH via AttackBox
Tools Used:
Windows Command Prompt (cmd.exe), OpenSSH, Built-in Windows networking and system utilities

![image alt](https://github.com/CodedByCarlosC/Labs/blob/5593351ccda0e37b99a48c6d59e3d955823fbca5/systeminfo.PNG)

🖥️ System Information & Environment Inspection
I used the command line to gather detailed system context, including:
OS version and build information
Hostname and system configuration
Environment variables and execution paths
Key commands practiced: ver, systeminfo, set, help, cls
These commands are essential for initial system triage during investigations or administrative work.


🌐 Network Configuration & Troubleshooting
I inspected and troubleshot network connectivity directly from the CLI using: ipconfig and ipconfig /all to view IP, DNS, DHCP, and gateway details
ping to test reachability and latency
tracert to trace packet paths across networks
nslookup to resolve domains and test DNS servers
netstat to inspect active connections and listening ports

![image alt](https://github.com/CodedByCarlosC/Labs/blob/5593351ccda0e37b99a48c6d59e3d955823fbca5/tracert.PNG)
![image alt](https://github.com/CodedByCarlosC/Labs/blob/5593351ccda0e37b99a48c6d59e3d955823fbca5/nslookup.PNG)
![image alt](https://github.com/CodedByCarlosC/Labs/blob/5593351ccda0e37b99a48c6d59e3d955823fbca5/ping.PNG)

Advanced netstat usage included:
Identifying services bound to ports
Mapping connections to process IDs (PIDs)
Understanding how services like SSH expose themselves on the system
These skills are directly applicable to network troubleshooting, threat hunting, and incident response.

![image alt](https://github.com/CodedByCarlosC/Labs/blob/5593351ccda0e37b99a48c6d59e3d955823fbca5/nstat-abon.PNG)

📂 File System Navigation & Management
I practiced navigating and manipulating the Windows file system without a GUI, including:
Navigating directories with cd
Listing contents using dir and tree
Creating and removing directories (mkdir, rmdir)
Viewing file contents (type, more)
Copying, moving, and deleting files (copy, move, del, erase)
Using wildcards (*) for bulk file operations
This reinforced how attackers and administrators alike interact with systems at a low level.

![image alt](https://github.com/CodedByCarlosC/Labs/blob/5593351ccda0e37b99a48c6d59e3d955823fbca5/cd.PNG)
![image alt](https://github.com/CodedByCarlosC/Labs/blob/5593351ccda0e37b99a48c6d59e3d955823fbca5/mkdir.PNG)
![image alt](https://github.com/CodedByCarlosC/Labs/blob/5593351ccda0e37b99a48c6d59e3d955823fbca5/ipconfig%20all.PNG)

⚙️ Process Enumeration & Control
I explored how to monitor and manage running processes from the CLI:
Listing processes with tasklist
Filtering processes by name
Identifying process IDs (PIDs)
Terminating processes using taskkill
Understanding process behavior is critical for identifying malicious activity, stuck services, or suspicious executables.

![image alt](https://github.com/CodedByCarlosC/Labs/blob/5593351ccda0e37b99a48c6d59e3d955823fbca5/tasklist.PNG)

🛠️ Additional System Commands
While not used extensively in this lab, I reviewed additional commands commonly used in system maintenance and security contexts:
chkdsk — disk and file system checks
driverquery — installed driver enumeration
sfc /scannow — system file integrity checks
I also practiced using / ? to explore command help & | more to manage long command output

🛡️ Security Takeaways
Command-line access provides deep system visibility
Many investigations occur without GUI access
Network and process inspection is essential for threat detection
CLI skills enable faster, more precise responses
Mastery of fundamentals supports advanced tools like PowerShell and SIEMs

📌 Why This Matters for Cybersecurity
This lab strengthened my ability to:
Investigate Windows systems efficiently
Troubleshoot network issues at a low level
Understand attacker and defender command usage
Operate confidently in restricted or headless environments
Command-line proficiency is foundational for SOC analysts, blue teamers, and incident responders, and this project reflects hands-on, real-world skill building—not just theory.
