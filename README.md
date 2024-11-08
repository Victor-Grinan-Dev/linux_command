# linux_command


Certainly! Here’s a summary of 20 of the most commonly used Linux commands, along with their basic functions:

## 1. touch
Creates an empty file or updates the timestamp of an existing file.
```bash
touch newfile.txt
```

## 2. echo
Displays a message or writes content to a file.
```bash
echo "Hello, World!" > hello.txt
```

## 3. cat
Displays the contents of a file, concatenates multiple files, or creates and adds content interactively.
```bash
cat file1.txt file2.txt
```

## 4. nano / vim
Opens a text editor to create or edit a file interactively.
```bash
nano myfile.txt
```

## 5. >
Creates an empty file or overwrites an existing file with the content of another command or file.
```bash
echo "This is new content" > newfile.txt
```

## 6. ls
Lists files and directories in the current directory.
```bash
ls -l
```

## 7. cd
Changes the current directory.
```bash
cd /home/user/Documents
```

## 8. pwd
Prints the current working directory (path).
```bash
pwd
```

## 9. cp
Copies files or directories from one location to another.
```bash
cp myfile.txt /home/user/Backup/
```

## 10. mv
Moves or renames files or directories.
```bash
mv oldfile.txt newfile.txt
```

## 11. rm
Deletes files or directories.
```bash
rm myfile.txt
```

## 12. chmod
Changes file or directory permissions (read, write, execute).
```bash
chmod 755 myscript.sh
```

## 13. chown
Changes the owner and/or group of a file or directory.
```bash
chown user:group myfile.txt
```

## 14. mkdir
Creates a new directory.
```bash
mkdir new_directory
```

## 15. man
Displays the manual or help page for a command, providing detailed information and options.
```bash
man ls
```

## 16. find
Searches for files and directories based on conditions like name, type, size, or modification time.
```bash
find /home/user -name "*.txt"
```

## 17. grep
Searches for specific patterns or text within files or command output.
```bash
grep "error" logfile.txt
```

## 18. df
Displays information about disk space usage on mounted file systems.
```bash
df -h
```

## 19. du
Shows disk usage statistics for files and directories, helping to identify space usage.
```bash
du -sh /home/user/Documents
```

## 20. ps
Displays a snapshot of current running processes.
```bash
ps aux
```

## 21. top
Displays real-time information about system processes, resource usage (CPU, memory), and system performance.
```bash
top
```

## 22. kill
Terminates a process by its process ID (PID).
```bash
kill 1234
```

## 23. tar
Archives and extracts files in .tar, .tar.gz, or .tar.bz2 formats.
```bash
tar -czvf archive.tar.gz myfolder/
```

## 24. wget
Downloads files from the internet via HTTP, HTTPS, or FTP protocols.
```bash
wget https://example.com/file.zip
```

## 25. curl
Transfers data from or to a server using various protocols (HTTP, FTP, etc.).
```bash
curl -O https://example.com/file.zip
```

## 26. history
Displays a list of recently used commands from the command history.
```bash
history
```

## 27. sudo
Executes a command with superuser (root) privileges.
```bash
sudo apt-get install vim
```

## 28. apt-get / apt
Package manager commands used to install, upgrade, or remove software packages on Debian-based distributions like Ubuntu.
```bash
sudo apt-get update
```

## 29. yum
Package manager for RPM-based distributions like CentOS and Red Hat, used for installing, updating, or removing packages.
```bash
sudo yum install vim
```

## 30. service
Used to start, stop, or manage services (like web servers, databases, etc.) on the system.
```bash
sudo service apache2 restart
```

