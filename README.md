# ps-command-implementation
Implementing ps command in linux terminal and c program

# ps command is used to list the currently running processes and their PIDs 
PID – the unique process ID 
TTY – terminal type that the user is logged into 
TIME – amount of CPU in minutes and seconds that the process has been running 
CMD – name of the command that launched the process. 

# The getpid() used to get the process id of the current process. 
# The process ID of the parent process can find using getppid().

# Implement ps command in linux
$ ps -A : List all processes on the system
$ ps -F: List process with extra full format
