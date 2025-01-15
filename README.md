# GitHub File Creation and Push Guide

This guide provides step-by-step instructions to create a folder, initialize it as a Git repository, and push it to your GitHub account.

---

## 🚀 Steps to Create and Push Files to GitHub

### 1. Open the Terminal
- Open your terminal (Command Prompt, PowerShell, or Bash).

### 2. Check Your Current Directory
- Use the following command to see your current location:  
  ```List the contents of the current directory:
  ls
  ```
  ```Navigate to Your Desired Folder:
  cd ..
  ```
  ```To enter a specific folder:
  cd 'foldername'
  ```
  ```Create a new folder where you want to store your project:
  mkdir "foldername"
  ```
  ```Verify that the folder is created:
  ls
  ```
  ```To enter a specific folder:
  cd 'foldername'
  ```
  ```Check the Git status in this folder:
  git status
  ```
  ```Initialize the folder as a git repository:
  git init
  ```
  ```Check exisiting remote repositories(if any):
  git remote
  ```
  ```Add your github repository link:
  git remote add origin 'repository-link'
  ```
  ```Confirm the remote repository has been added:
  git remote
  ```
  ```Clone the GitHub repository if required:
  git clone 'repository-link'
  ```
  ```List the contents to ensure the repository is cloned:
  ls
  ```
  ```Add all files to the staging area:
  git add .
  ```
  ```Commit the changes with a meaningful message:
  git commit -m "your message"
  ```
  ```Push the changes to the main branch of the remote repository:
  git push origin main
  ```
  
  ##🎉 You're Done!
Your folder and files are now pushed to your GitHub repository. You can verify this by visiting your repository on GitHub.

  
