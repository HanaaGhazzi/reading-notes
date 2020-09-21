### Setting up a Git Repository

**Importing**

To import an existing project or directory into Git, follow these steps using the Terminal or Command Line:

Switch to the target project’s directory
Example:

> $ cd test (cd = change directory)


Use the git init command

> $ git init
Note: At this stage, you have created a new subdirectory named .git that has the repository files. Tracking has not commenced.

*To start tracking these repository files, perform an initial commit by typing the following:* 

1. >$ git add *.c
2. >$ git add LICENSE
3. >$ git commit -m “any message here”

**Now, your files are tracked and there’s an initial commit. We will discuss the particular commands in detail soon.**