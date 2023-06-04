# cursogit

Documentation: https://git-scm.com/doc

- First step:
Set yout user name and emal, for example:
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com

To verify your information, write the next comand line:
$ git config --list
You can close the list by pressing the letter "q"

- Second step
We can initialice a local repository with the command line:
$ git init
We must to be in the folder that will be the local master of the repository, check your directory location with: pwd
We can see the status and files available to add to another repository with the command:
$ git satuts
To add files to the local repository, we can write:
$ git add <file name>
This command allows to track files
If you wanto to add all files, you have to write in <file name> a point <.>
  
 - Third step
To commit the add files, we can write:
$ git commit -m "Adding files"
The "phrase" can be anything
We can check the status with: $ git status 
