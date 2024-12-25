# How to Push Code to GitHub

## Step 1: Install Git

If you haven't already, download and install Git from [git-scm.com](https://git-scm.com/).

## Step 2: Configure Git

Open your terminal or command prompt and configure your Git username and email:

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

## Step 3: Initialize a Git Repository

Navigate to your project directory and initialize a Git repository:

```bash
cd /path/to/your/project
git init
```

## Step 4: Add Your Files

Add your project files to the repository:

```bash
git add .
```

## Step 5: Commit Your Changes

Commit the added files with a message:

```bash
git commit -m "Initial commit"
```

## Step 6: Create a New Repository on GitHub

Go to [GitHub](https://github.com/) and create a new repository. Do not initialize it with a README, .gitignore, or license.

## Step 7: Add the Remote Repository

Add the GitHub repository as a remote:

```bash
git remote add origin https://github.com/your-username/your-repository.git
```

## Step 8: Push Your Code

Push your code to the GitHub repository:

```bash
git push -u origin master
```

Congratulations! Your code is now pushed to GitHub.
