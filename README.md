CIS 191 Project 3
=================

Eric Lee   
_ericslee_

This is a demo site that is a simplified version of the CIS 191 website. It is
used as a testbed/training ground for Git usage and merge conflict resolution.

Project Questions:
-----------------
**What does the git hook do?**   
The git hook 'post-receive' runs after content is pushed to the EC2 server. It copies files from the deploy directory (which is a git repo) to the www directory. A message is echo'd to annouce that the server is (re)starting, and server.py is run to restart and update the server with the new code in www

**What does the Python server do?**   
The Python server publishes the www directory online, accessible via PORT 9001.

**What is a bare repository?**   
A bare repo does not contain working copies of the source file. It is meant to be a centralized server that code gets pushed to from other working directories.

**Extra**   
Added some basic markdown syntax to enhance the readme. 
