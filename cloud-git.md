Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.

Types of version control
    1-  Local Version Control
    2-  Centralized Version Control
    3-  Distributed Version Control

Git is a Distributed Control Version Storage that Data in a file made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. Every single change applied to any file or directory is tracked by Git.

# History of Git
Git traces its roots to the open source software project Linux kernel. Developers of this project began using a DVCS called BitKeeper in 2002.
Since its inception in 2005, Git has become one of the most utilized Version Control Systems in the world.

## How to configure Git
An inherent Git tool called git config allows the setting of configuration variables that control aspects of Git’s operation and look.

ype the following into Terminal or Command Line:

git config --global user.name "Jane Smith"

git config --global user.email "example@email.com"
To confirm that you have the correct settings, enter the following command:

git config --global user.name (should return Jane Smith)

git config --global user.email (should return example@email.com)

## Importing

1.  Switch to the target project’s directory
    - $ cd test (cd = change directory)        
2.  Use the git init command
    - $ git init
3.  To start tracking these repository files, perform an initial commit by typing the following:

   - $ git add *.c
   - $ git add LICENSE
    -$ git commit -m “any message here”

## Cloning

You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL:

    **$ git clone https://github.com/test**

To clone a repository into a directory with another name of your choosing, use the following command format:

    $ git clone https://github.com/test mydirectory

## File Status

To determine the state of files, utilize the git status command:

    **$ git status**

## Tracking and Staging New Files

    $ git add filename
    $ git commit -m “made change x,y,z
    $ git push origin master
Committing All Changes
    $ git commit -a

Seeing Your Remotes

By running the git remote command, you can view the short names, such as “origin,” of all specified remote handles.

By using git remote -v, you can view all the remote URLs next to their corresponding short names.

$ cd example

$ git remote -v

remote1 https://github.com/remote1/example (fetch)

remote1 https://github.com/remote1/example (push)

remote2 https://github.com/remote2/example (fetch)

remote2 https://github.com/remote2/example (push)

remote3 https://github.com/remote3/example (fetch)

remote3 https://github.com/remote3/example (push)

Adding Remotes
To create a new remote Git repository with a short name, use the following format:

git remote add shortname url
Example:

    $ git remote

    origin

    $ git remote add js https://github.com/janesmith/project1

    $ git remote -v

    origin https://github.com/johndoe/project1 (fetch)

    origin https://github.com/johndoe/project1 (push)

    js     https://github.com/janesmith/project1 (fetch)

    js     https://github.com/janesmith/project1 (push)

$ git remote rename js jane

$ git remote

origin

jane

$ git remote rm jane

$ git remote

origin
