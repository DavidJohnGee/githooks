# githooks
Git hooks scripts for work flows

As git uses hooks to provide methods of running scripts in varying languages at different times, you can do linting, code 
vetting and build jobs during different phases of the git process if you so desired.

Files so far include the 'pre-commit' file, which is specifically for Golang. It does:

'gofmt', 'go vetting' and 'go linting'. 

In my workspace go directory structure, in addition to src, bin and pkg, I also have a githooks
directory.
