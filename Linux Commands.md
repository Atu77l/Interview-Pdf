Linux Commands


1. **File and Directory Operations**:
   - **ls**: List files and directories.
     - Example: `ls -l` (long format listing)
   - **cd**: Change directory.
     - Example: `cd /path/to/directory` (change to a specific directory)
   - **cp**: Copy files and directories.
     - Example: `cp file.txt /path/to/destination` (copy a file to a new location)
   - **mv**: Move or rename files and directories.
     - Example: `mv file.txt newname.txt` (rename a file)
   - **rm**: Remove files and directories.
     - Example: `rm file.txt` (remove a file)
   - **cat**: Display the contents of a file.
     - Example: `cat file.txt` (display the contents of a file)
   - **head**: Display the beginning of a file.
     - Example: `head -n 10 file.txt` (display the first 10 lines of a file)
   - **tail**: Display the end of a file.
     - Example: `tail -n 5 file.txt` (display the last 5 lines of a file)

2. **File Permissions**:
   - **chmod**: Change file permissions.
     - Example: `chmod 644 file.txt` (set read-write permissions for the owner and read-only permissions for others)
   - **chown**: Change file owner and group.
     - Example: `chown user:group file.txt` (change the owner and group of a file)

3. **Process Management**:
   - **ps**: List running processes.
     - Example: `ps aux` (display a detailed list of running processes)
   - **kill**: Send a signal to terminate a process.
     - Example: `kill PID` (terminate a process with a specific process ID)

4. **Text Processing**:
   - **grep**: Search for a pattern in files.
     - Example: `grep "pattern" file.txt` (search for a specific pattern in a file)
   - **sed**: Stream editor for text manipulation.
     - Example: `sed 's/old/new/g' file.txt` (replace all occurrences of 'old' with 'new' in a file)

5. **Version Control**:
   - **git**: Distributed version control system.
     - Example: `git clone https://github.com/repository.git` (clone a remote Git repository)

Additional commands 

1. **File Searching**:
   - **find**: Search for files and directories based on various criteria.
     - Example: `find /path/to/search -name "file.txt"` (search for a file by name)

2. **Text Editing**:
   - **nano**: A simple command-line text editor.
     - Example: `nano file.txt` (open a file for editing in Nano)
   - **vim**: A text editor.
      - Example: `vim file_name.txt`(opens a file in Vim)

3. **Process Monitoring**:
   - **htop**: Interactive process viewer and system monitor.
     - Example: `htop` (launch the htop process monitor)

4. **System Information**:
   - **uname**: Print system information.
     - Example: `uname -a` (display all system information)

5. **Disk Usage**:
   - **df**: Display disk space usage of file systems.
     - Example: `df -h` (show disk space usage in a human-readable format)
   - **du**: Estimate file and directory space usage.
     - Example: `du -sh /path/to/directory` (display the total size of a directory)

6. **Compression and Archiving**:
   - **tar**: Archive files and directories into a single file.
     - Example: `tar -czvf archive.tar.gz /path/to/directory` (create a compressed tarball of a directory)
   - **gzip**: Compress files.
     - Example: `gzip file.txt` (compress a file using gzip)

7. **SSH Key Management**:
   - **ssh-keygen**: Generate SSH key pairs.
     - Example: `ssh-keygen -t rsa -b 4096` (generate a 4096-bit RSA SSH key pair)

8. **Network Utilities**:
   - **netstat**: Network statistics and active connections.
     - Example: `netstat -tuln` (display all active TCP and UDP connections)
   - **wget**: Retrieve files from the web via HTTP, HTTPS, and FTP.
     - Example: `wget https://example.com/file.txt` (download a file from a URL)

9. **System Resource Monitoring**:
   - **free**: Display system memory usage.
     - Example: `free -h` (show memory usage in a human-readable format)
   - **top**: Display system resource usage in real-time.
     - Example: `top` (display an interactive real-time view of system resource usage)

.

