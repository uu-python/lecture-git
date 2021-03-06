# An introduction to git
After this lecture/tutorial you will be able to 
* use git repositories 
* understand the importance of version control
* join collaborative coding/writing projects (using git)

## Get started
For this lecure, you need git to be installed on your computer (most likely this is already the case). 
If you type `git` in the terminal, you should see the following:
```bash
usage: git [--version] [--help] [-C <path>] [-c name=value]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p|--paginate|--no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

The most commonly used git commands are:
   add        Add file contents to the index
   bisect     Find by binary search the change that introduced a bug
   branch     List, create, or delete branches
   checkout   Checkout a branch or paths to the working tree
   clone      Clone a repository into a new directory
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   fetch      Download objects and refs from another repository
   grep       Print lines matching a pattern
   init       Create an empty Git repository or reinitialize an existing one
   log        Show commit logs
   merge      Join two or more development histories together
   mv         Move or rename a file, a directory, or a symlink
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects
   rebase     Forward-port local commits to the updated upstream head
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index
   show       Show various types of objects
   status     Show the working tree status
   tag        Create, list, delete or verify a tag object signed with GPG

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
```

In case the above help message is not shown, you need to install git. You can find installers for different operating systems here: [https://git-scm.com/downloads](https://git-scm.com/downloads)

## Lecture notes
The slides are available here: [slides.pdf](./slides.pdf)

## Exercise 1
1. Create a local copy (clone) of the following project: [https://github.com/uu-python/particpants](https://github.com/uu-python/particpants)
2. Create a new file ```YOURNAME.md```
3. Write something about yourself and add your file to the files tracked by git
4. Commit your changes and give a meaningful log message
5. Update your local repository by pulling from the remote
6. Update the remote repository by pushing your local changes

## Exercise 2
1. Create a local copy (clone) of the following project:  [https://github.com/uu-python/particpants](https://github.com/uu-python/particpants)
2. Create a new branch "yourname"
3. Edit a certain section of the file ```cheatsheet.md``` which was given to you by the teachers.
4. Commit your changes and give a meaningful log message
5. Push your local to remote branch with the same name
6. Switch to the master branch and merge the branch “yourname" into master
7. Update local master branch (pull)
8. Update remote master branch (push)

