This repo will handle the PintOS shell.

Possible:
- show a prompt, read a line, loop (basic shell expectations)
- run a program so long as it's already in the file system
- pass argument as a single command line
- print simple error messages
- exit

Impossible:
- PATH search
- I/O redirection
- Pipes
- Job control/backgrounding (&, SIGKILL, etc)
- cd
- Globbing/quoting/variables
- Run Linux binaries
- Advanced line editing/history

I' not sure how to handle what is in the 'impossible' section besides handling all of this outside of PintOS and instead having it in a regular UNIX shell.