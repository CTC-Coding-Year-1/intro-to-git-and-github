# Getting Started with Git and GitHub

This guide will walk you through the process of initializing your first Git project, cloning a repository, making changes, and pushing those changes to your GitHub repository.

## Prerequisites

Before you begin, make sure you have the following:

- A GitHub account: If you don't have one, sign up at [GitHub](https://github.com/).

- Git installed on your local machine: Download and install Git from [here](https://git-scm.com/downloads).

- A folder to in your Documents folder named "repos". When you download/pull/clone a new repo it will install the project folder (which shares the same name as the repo), with all of its files here.

## Step 1: Initializing Your Git Project

1. Open your terminal or command prompt.

2. Navigate to the directory where you want to create your Git project.

3. Run the following command to initialize a new Git repository:

   ```shell
   git init
   
- **NEVER** initialize a git repo inside of a folder that already has one. Every project folder should only have _one_ initialization of git in it.
  
## Step 2: Cloning a Repository

If you already have a repository on GitHub that you want to work with, you can clone it to your local machine.

  1. Go to the top of this GitHub repository page.

  2. Click the green "Code" button and copy the repository URL.

  3. In your terminal, navigate to the directory where you want to clone the repository.

  4. Run the following command, replacing <repository-url> with the URL you copied:
        _Make sure you use **Ctrl + ***Shift*** + V** to paste it in_

      ```shell
      git clone <repository-url>
      
## Step 3: Make the changes to the markdown-assignment.md file. 

  Ways to edit Markdown (.md) files:
  -  In [VSCode](https://code.visualstudio.com/docs/languages/markdown)
  -  Directly in the the [GitHub Repo](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github)
  -  Use an online editor like [StackEdit](https://stackedit.io)

## Step 4: Stage and Commit your changes on your local repo.

  - **Windows Users** You can use the Git Bash or PowerShell terminals
  - **Mac Users**  use the Terminal
  - **Linux Users** use a Bash terminal

    ```shell
    git add . && git commit -m "Add a descriptive commit message here"


## Step 5: Push changes to the GitHub Repo

- You can set-up an origin repo for your projects (Useful for when you are only going to be pushing to one online repo. Saves the online repo as "origin" so you do not have to type out the url)

1. 
    ```shell
      git remote add origin <repository-url>
    
2. 
      ```shell
      git push -u origin main

**OR**

- You can do a push straight to the repo's url (Useful for if you need to push to multiple repos, but having to copy + paste the urls every time takes longer and is more likely to fail because of typos)

    ```shell
      git push <repository-url>

## Step 6: Refresh the repo page on GitHub to verify changes.
