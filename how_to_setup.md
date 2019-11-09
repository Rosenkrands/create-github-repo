# How to set up a new GitHub repository
The approach taken in this guide is to first create a local folder in which would act as the working directory.
Then initializing a Git repository in this directory and thereafter creating a repository in GitHub.
The GitHub repository will then be added as a remote origin using the command line, in this case GitBash.

## Create a local folder
Go to the place on your computer where you want to place the working directory, for example the desktop.
Press `ctrl + shift + n` to create a new folder, call the folder the name of the project.
Preferably lowercase with no spaces.

Navigate inside the folder and right click anywhere inside the folder, select `Git Bash here`.
When in the Git Bash terminal, type `git init`.
You should see something along the lines of:

![](screenshots\git_init.png)

## Create a new file
Whatever the type of project you want to start, you can now create a file.
This could just be a readme file or whatever.
After saving the new file, what you want to do is create your first commit.
Before making the commit, you first need to add the new file.
This is also known as staging and is done using the command `git add filename.extension` in the Git Bash terminal.
You should see something like:

![](screenshots\git_add.png)

You can now commit the staged changes using the command `git commit -m "Commit message"`.
You should see something like:

![](screenshots\git_commit.png)

## Create repository on GitHub
Now that you have made a commit we can create a GitHub repository.
Go to your site on GitHub.com and select the green new button.

![](screenshots\github_new.png)

This leads to the following site where we can give our repository a name and change additional settings.

![](screenshots\github_create_new.png)
