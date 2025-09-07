# Working with GitHub

## Creating and Cloning Repositories
- Create a new repository on GitHub via the GitHub interface.
- Clone the newly created repository to your local machine:
``git clone https://github.com/YourUsername/my-workshop-repo.git``
**Note**: Replace ``YourUsername`` with your GitHub username.

## Pushing Changes to GitHub
- Add the remote (from GitHub) URL to your local repository:
``git remote add origin https://github.com/YourUsername/my-workshop-repo.git``

## Push the local commits (from your computer) to GitHub:
``git push -u origin main``

## Pulling Changes from GitHub
- Pulling changes made by others (pulling from GitHub down to your file on your computer):
``git pull``

## Collaborate via Forks and Pull Requests
- Forking, making changes, and creating pull requests are key concepts in collaborative workflows using GitHub. Here is a detailed guide on how to collaborate via forks and pull requests, complete with step-by-step instructions and code snippets.
1. Fork a Repository
Forking is the process of creating a personal copy of someone else's repository on GitHub. 
- This is useful for contributing to open-source projects or collaborating on projects where you don’t have direct write access.
- Steps to Fork a Repository:
    - Navigate to the Repository:
    - Go to the GitHub page of the repository you'd like to contribute to.
    - Fork the Repository:
        - Click on the "Fork" button located at the top-right corner of the page.
        - This creates a copy of the repository in your personal GitHub account.
2. Make Changes to a Forked Repository
- Once you have your fork, you can make changes to it as desired.
- Steps to Make Changes:
    - Clone Your Forked Repository:
    - Use the following command (in anew terminal wondow) to clone your forked repository to your local machine. Replace ``YourUsername`` with your GitHub username.
``git clone https://github.com/YourUsername/RepositoryName.git``

- Navigate into the cloned repository:
``cd RepositoryName``

- Make Changes**:
    - Open files in your editor and make the desired changes or additions.
    -  Save your changes.

## Stage and Commit Changes:
- Stage the changed files:
``git add .``
- Commit your changes with a meaningful message:
``git commit -m "Add new feature or fix issue"``

## Push Changes to GitHub:
- Push your changes to your fork on GitHub.
- Then refresh browser and you should see the changes on GitHub repository.
``git push origin``
