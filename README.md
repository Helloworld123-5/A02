# A02 - Git, GitHub, and Visual Studio Code Tutorial

## Introduction

This tutorial explains how to use Git, GitHub, and Visual Studio Code (VS Code). These tools can be used together to create projects, track changes, and store projects online.

## Part 1: Directions

### Step 1: Create a GitHub Account

1. Go to https://github.com/
2. Click Sign Up.
3. Enter your email address.
4. Create a password and username.
5. Complete the account setup and sign in.

### Step 2: Install Git

1. Go to https://git-scm.com/
2. Download Git for your operating system.
3. Open the installer.
4. Follow the installation instructions.
5. Keep the recommended/default settings during installation.
6. Finish the installation.

To check that Git is installed, open the terminal and enter:

`git --version`

### Step 3: Install Visual Studio Code

1. Go to https://code.visualstudio.com/
2. Download Visual Studio Code for your operating system.
3. Open the installer.
4. Follow the installation instructions.
5. Open Visual Studio Code after installation.

### Step 4: Create a GitHub Repository

1. Sign in to GitHub.
2. Click the + button and select New repository.
3. Enter A02 as the repository name.
4. Select Public.
5. Click Create repository.

### Step 5: Create the Project in VS Code

1. Create a folder named A02 on your computer.
2. Open Visual Studio Code.
3. Open the A02 folder.
4. Create a new file named README.md.
5. Add the tutorial information to README.md.
6. Save the file.

### Step 6: Initialize Git

Open the terminal in Visual Studio Code and enter:

`git init`

This creates a local Git repository for the project.

### Step 7: Add the README File

Enter:

`git add README.md`

This tells Git to track the README.md file.

### Step 8: Commit the Changes

Enter:

`git commit -m "Task: Create Repository"`

A commit saves a snapshot of the project.

Other clear commit messages can include:

`git commit -m "Feature: added workflow for using github"`

`git commit -m "Fix: changed readme.md for definition of terms"`

### Step 9: Connect the Local Repository to GitHub

Enter:

`git branch -M main`

Then connect the local repository to the GitHub repository:

`git remote add origin https://github.com/yourUCID/A02.git`

Replace `yourUCID` with your GitHub username.

### Step 10: Push the Project to GitHub

Enter:

`git push -u origin main`

This uploads the local project to GitHub.

### Step 11: Making Future Changes

After changing files, use:

`git add .`

Then create a commit:

`git commit -m "Describe your changes"`

Finally, push the changes:

`git push`

### Step 12: Pull Changes

To get the newest changes from GitHub, use:

`git pull`

This updates the local project with changes from the remote repository.

---

## Part 2: Glossary

- **Branch** - A separate version of a project that allows changes to be made without immediately changing the main version.

- **Clone** - A copy of a Git repository that is downloaded to a local computer.

- **Commit** - A saved snapshot of changes made to files in a Git repository.

- **Fetch** - Downloads changes from a remote repository without automatically adding them to the current local branch.

- **GIT** - A version control system that tracks changes made to files and projects.

- **Github** - An online platform used to store, manage, and share Git repositories.

- **Merge** - The process of combining changes from one branch with another branch.

- **Merge Conflict** - A problem that happens when Git cannot automatically combine different changes to the same part of a file.

- **Push** - Sends commits from a local repository to a remote repository such as GitHub.

- **Pull** - Gets changes from a remote repository and integrates them into the local repository.

- **Remote** - A version of a repository stored somewhere else, such as on GitHub.

- **Repository** - A location that stores a project's files and tracks the history of changes.

---

## Conclusion

Git, GitHub, and Visual Studio Code work together to make it easier to create projects, track changes, and store work online. Learning this workflow makes it easier to manage projects and collaborate with others.

## References

GitHub Docs. Git and GitHub Documentation.  
https://docs.github.com/

Git. Git Documentation.  
https://git-scm.com/doc

Visual Studio Code. Version Control Documentation.  
https://code.visualstudio.com/docs/sourcecontrol/overview
