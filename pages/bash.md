# Hello Bash

## Standard Stream, Redirection, and a bit of Grep
Standard stream lies (almost) the same on every Unix/Unix-like system. Standard Input (stdin), Standard Output (stdout), and Standard Error (stderr).

For redirections, we can think of redirection as the post process after a certain process. The most notable example of this, is when we run a certain command in our terminal

Assume that in your current directory, you have a bunch of files and directories. And you're looking for one of them. And even worse, you only remember a part of the name of file you're looking for. 

The normal way would be doing something like `ls`.

The output will be overwhelming in some cases. But now, we can pipe it, or post process it to another command to narrow it down, say by using `grep` for example.

So the whole command would be like this, `ls | grep "lala"`
