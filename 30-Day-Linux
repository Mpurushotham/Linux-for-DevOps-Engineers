/*
================================================================================
30-Day Linux for DevOps Engineers: A Practical, Hands-On Learning Framework
================================================================================

Welcome! This 30-day journey is designed to transform you into a confident Linux user, ready to tackle real-world DevOps challenges. Each day builds on the last, blending theory, analogies, hands-on scripts, and DevOps scenarios. Let's get started!

--------------------------------------------------------------------------------
Day 1: Introduction to Linux & The Command Line
--------------------------------------------------------------------------------
**Goal:** Understand what Linux is, why it powers DevOps, and get comfortable with the terminal.

**Before you begin:**  
- Ensure you have access to a Linux system (VM, WSL, or cloud shell).
- Open a terminal window.

**What it is:**  
Linux is an open-source operating system that forms the backbone of most cloud and DevOps infrastructure. The command line (shell) is your primary interface for interacting with Linux.

**Why it matters:**  
DevOps pipelines, automation scripts, and cloud servers all run on Linux. Mastering the shell is like learning the language of DevOps.

**Real-life analogy:**  
Think of Linux as the engine room of a ship. The command line is your control panel—buttons, levers, and dials to operate everything.

**Command-line example:**
# Print your current working directory
pwd

# List files and directories
ls -l

# Display your username
whoami

--------------------------------------------------------------------------------
Day 2: Navigating the Filesystem
--------------------------------------------------------------------------------
**Goal:** Move around the Linux directory tree and understand paths.

**Key commands:**
cd /path/to/directory    # Change directory
ls                      # List contents
pwd                     # Show current directory

**Try this:**
cd ~        # Go to your home directory
cd /        # Go to the root directory
cd ..       # Move up one directory

--------------------------------------------------------------------------------
Day 3: Working with Files and Directories
--------------------------------------------------------------------------------
**Goal:** Create, view, and remove files and directories.

**Key commands:**
touch filename           # Create a new file
mkdir dirname            # Create a new directory
rm filename              # Remove a file
rmdir dirname            # Remove an empty directory
cat filename             # View file contents

--------------------------------------------------------------------------------
Day 4: Viewing and Editing Files
--------------------------------------------------------------------------------
**Goal:** Learn to read and edit files from the command line.

**Key commands:**
cat filename             # Print file contents
less filename            # View file page by page
nano filename            # Edit file in a simple editor
vim filename             # Edit file in a powerful editor

--------------------------------------------------------------------------------
Day 5: File Permissions and Ownership
--------------------------------------------------------------------------------
**Goal:** Understand and modify who can read, write, or execute files.

**Key commands:**
ls -l                    # Show permissions
chmod u+x script.sh      # Add execute permission for user
chown user:group file    # Change file owner

--------------------------------------------------------------------------------
Day 6: Searching and Finding Files
--------------------------------------------------------------------------------
**Goal:** Locate files and search within them.

**Key commands:**
find /path -name "file*"     # Find files by name
grep "text" filename         # Search for text in a file
grep -r "text" /dir          # Search recursively

--------------------------------------------------------------------------------
Day 7: Redirects and Pipes
--------------------------------------------------------------------------------
**Goal:** Chain commands and redirect input/output.

**Key commands:**
command > file           # Redirect output to file
command >> file          # Append output to file
command1 | command2      # Pipe output to another command

--------------------------------------------------------------------------------
Day 8: Users and Groups
--------------------------------------------------------------------------------
**Goal:** Manage users and groups.

**Key commands:**
whoami                   # Show current user
id                       # Show user and group info
sudo adduser newuser     # Add a new user (as admin)
sudo groupadd newgroup   # Add a new group

--------------------------------------------------------------------------------
Day 9: Package Management
--------------------------------------------------------------------------------
**Goal:** Install and update software.

**Key commands (Debian/Ubuntu):**
sudo apt update
sudo apt install packagename

**Key commands (RedHat/CentOS):**
sudo yum install packagename

--------------------------------------------------------------------------------
Day 10: Processes and System Monitoring
--------------------------------------------------------------------------------
**Goal:** View and manage running processes.

**Key commands:**
ps aux                   # List all processes
top                      # Interactive process viewer
kill PID                 # Kill a process by PID

--------------------------------------------------------------------------------
Day 11: Environment Variables
--------------------------------------------------------------------------------
**Goal:** Understand and set environment variables.

**Key commands:**
echo $HOME               # Show value of HOME
export VAR=value         # Set a variable for current session

--------------------------------------------------------------------------------
Day 12: Shell Scripting Basics
--------------------------------------------------------------------------------
**Goal:** Write simple shell scripts.

**Example:**
#!/bin/bash
echo "Hello, Linux!"

--------------------------------------------------------------------------------
Day 13: Scheduling Tasks (cron)
--------------------------------------------------------------------------------
**Goal:** Automate tasks with cron.

**Key commands:**
crontab -e               # Edit cron jobs
# Example: Run script every day at 2am
0 2 * * * /path/to/script.sh

--------------------------------------------------------------------------------
Day 14: Networking Basics
--------------------------------------------------------------------------------
**Goal:** Check connectivity and network configuration.

**Key commands:**
ifconfig or ip addr      # Show network interfaces
ping google.com          # Test connectivity
netstat -tuln            # List open ports

--------------------------------------------------------------------------------
Day 15: SSH and Remote Access
--------------------------------------------------------------------------------
**Goal:** Connect to remote servers securely.

**Key commands:**
ssh user@host            # Connect to remote server
scp file user@host:/path # Copy file to remote server

--------------------------------------------------------------------------------
Day 16: Disk Usage and Filesystems
--------------------------------------------------------------------------------
**Goal:** Check disk space and manage filesystems.

**Key commands:**
df -h                    # Show disk usage
du -sh /path             # Show size of directory

--------------------------------------------------------------------------------
Day 17: Archives and Compression
--------------------------------------------------------------------------------
**Goal:** Compress and extract files.

**Key commands:**
tar -czvf archive.tar.gz dir/   # Create compressed archive
tar -xzvf archive.tar.gz        # Extract archive
gzip file                       # Compress file

--------------------------------------------------------------------------------
Day 18: System Logs
--------------------------------------------------------------------------------
**Goal:** View and analyze system logs.

**Key commands:**
tail -f /var/log/syslog         # View live logs
less /var/log/auth.log          # View authentication logs

--------------------------------------------------------------------------------
Day 19: Services and Daemons
--------------------------------------------------------------------------------
**Goal:** Manage background services.

**Key commands:**
systemctl status servicename    # Check service status
systemctl start servicename     # Start a service
systemctl enable servicename    # Enable service at boot

--------------------------------------------------------------------------------
Day 20: Advanced Permissions (sudo, su)
--------------------------------------------------------------------------------
**Goal:** Use superuser privileges safely.

**Key commands:**
sudo command                    # Run command as superuser
su -                            # Switch to root user

--------------------------------------------------------------------------------
Day 21: Bash Aliases and Customization
--------------------------------------------------------------------------------
**Goal:** Speed up your workflow with aliases.

**Key commands:**
alias ll='ls -l'                # Create an alias
echo "alias gs='git status'" >> ~/.bashrc

--------------------------------------------------------------------------------
Day 22: Regular Expressions and Text Processing
--------------------------------------------------------------------------------
**Goal:** Manipulate text with powerful tools.

**Key commands:**
grep "pattern" file             # Search with regex
awk '{print $1}' file           # Print first column
sed 's/foo/bar/g' file          # Replace text

--------------------------------------------------------------------------------
Day 23: Advanced Shell Scripting
--------------------------------------------------------------------------------
**Goal:** Use variables, loops, and conditionals.

**Example:**
for file in *.txt; do
  echo "Processing $file"
done

--------------------------------------------------------------------------------
Day 24: System Updates and Upgrades
--------------------------------------------------------------------------------
**Goal:** Keep your system secure and up to date.

**Key commands:**
sudo apt update && sudo apt upgrade   # Debian/Ubuntu
sudo yum update                      # RedHat/CentOS

--------------------------------------------------------------------------------
Day 25: Security Best Practices
--------------------------------------------------------------------------------
**Goal:** Harden your Linux system.

- Use strong passwords and SSH keys
- Keep software updated
- Limit sudo access
- Use firewalls (ufw, firewalld)

--------------------------------------------------------------------------------
Day 26: Troubleshooting and Help
--------------------------------------------------------------------------------
**Goal:** Diagnose and fix common issues.

**Key commands:**
dmesg                       # Kernel messages
journalctl                  # Systemd logs
man command                 # Read manual pages

--------------------------------------------------------------------------------
Day 27: Containers and Linux
--------------------------------------------------------------------------------
**Goal:** Understand the basics of containers.

**Key commands:**
docker ps                   # List running containers
docker run hello-world      # Run a test container

--------------------------------------------------------------------------------
Day 28: Automation with Ansible
--------------------------------------------------------------------------------
**Goal:** Automate configuration with Ansible.

**Key commands:**
ansible --version
ansible-playbook playbook.yml

--------------------------------------------------------------------------------
Day 29: Monitoring and Alerting
--------------------------------------------------------------------------------
**Goal:** Monitor system health.

**Key tools:**
htop, atop, Nagios, Prometheus, Grafana

--------------------------------------------------------------------------------
Day 30: DevOps in Practice
--------------------------------------------------------------------------------
**Goal:** Combine your Linux skills in a real DevOps scenario.

- Write a script to deploy a web server
- Automate user creation
- Monitor logs and send alerts

**Congratulations!**  
You’ve completed 30 days of Linux for DevOps. Keep practicing, explore advanced topics, and start automating your workflows!
--------------------------------------------------------------------------------
Explore Advanced Topics: Scripts & Explanations
--------------------------------------------------------------------------------

**1. Bash Scripting: Automate Repetitive Tasks**

_Bash scripts let you automate sequences of commands._

**Example: Backup your home directory**
