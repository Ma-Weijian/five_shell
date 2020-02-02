# five_shell
A tiny shell derived from CS:APP shell lab

This is a tiny shell with job control. It has special SIGINT, SIGTSTP, SIGCHLD and SIGQUIT handlers and has bg, fg, job and quit as its builtin commands. 

This shell can execute external programs such as /bin/ls and so on but it does not support complicated programs such as vi.

It can also run the jobs as foreground jobs and background jobs as well as recycling the PCB of zombie children.

Type make in the directory to compile and ./fivesh to run the shell. Other four source files are tiny trial programs.

Note that this tiny shell does not have the advanced functions such as the arrow keys.
