# Week-1_DevOps
## Linux Commands Summary

1. Navigating the File System

1. pwd - Print Working Directory – Shows the current directory.
2. ls - List directory contents.
3. cd - Change directory.
   - cd /home - Navigate to the /home directory.
   - cd .. - Move up one directory level.
   - cd ~ - Move to the home directory.

2. File Management

1. touch newfile.txt- Create an empty file named newfile.txt.
2. mkdir newdirectory - Create a new directory named newdirectory.
3. cp newfile.txt newdirectory/ - Copy newfile.txt into newdirectory.
4. mv newfile.txt newdirectory/- Move newfile.txt into newdirectory.
5. rm newfile.txt - Remove newfile.txt.
6. rmdir newdirectory - Remove the empty directory newdirectory.

3. System Monitoring

1. df -h - Display disk space usage in human-readable format.
2. top - Show real-time system summary including CPU, memory usage, and running processes.

4. User and Group Management

1. sudo adduser username - Add a new user with the specified username.
2. sudo usermod -aG groupname username - Add username to groupname.
3. sudo deluser username - Delete the specified username.
4. id username - Display user ID and group ID information for username.
5. su - username - Switch to the user username.

5. Aliases and Environment Variables

1. nano ~/.bashrc - Edit the .bashrc file to configure aliases and environment variables.
2. source ~/.bashrc - Reload the .bashrc file to apply changes.
3. alias ll=ls -la - Define command shortcut for listing files with details.
4. export MY_VAR="DevOps" - Set environment variable MY_VAR to "DevOps".
5. export PATH=$PATH:/home/skilluser/my_custom_path- Append custom path to the PATH environment variable.
