# Basic Git Commands

## Initializing a Repository
- Create a new directory and initialize a Git repository.
  - Open a new terminal window.
  - Type;

```
mkdir my-workshop-repo
cd my-workshop-repo
git init
```
**Explanation**
 ``mkdir my-workshop-repo``
**What it does**: This command creates a new directory (folder) named ``my-workshop-repo``.
**Purpose**: It is used to organize files and projects. In this case, you're creating a folder where your workshop repository will be stored.
**Key points**:
``mkdir`` stands for "make directory."
After running this command, you'll have a new folder named ``my-workshop-repo`` in your current location.
"In your current location": When you run this command in a terminal or command prompt, it creates the new folder in the directory you're currently navigating. Every terminal session has a "current working directory," which you can think of as the folder you're currently "inside" in a file explorer.
Result: After executing the command, you'll have a new folder named "my-workshop-repo" in this current working directory. You can change your working context (change directory) to this new folder using a command like cd my-workshop-repo, allowing you to work within it, such as initializing a Git repository or creating files.
cd my-workshop-repo
What it does: This command changes your current working directory to the newly created my-workshop-repo folder.
Purpose: It allows you to navigate into the folder so you can work inside it (e.g., adding files, initializing a Git repository, etc.).
Key points:
cd stands for "change directory."
After running this command, your terminal or command-line interface will now be inside the my-workshop-repo folder.
git init
What it does: This command initializes a new Git repository in the current directory (my-workshop-repo).
Purpose: It sets up version control for the folder, allowing you to track changes to files, collaborate with others, and manage your project using Git.
Key points:
git init creates a hidden .git folder inside the directory, which contains all the metadata and configuration files needed for Git to track changes.
After running this command, your folder is now a Git repository, and you can start using Git commands like git add, git commit, etc.
Summary
These commands are commonly used when starting a new project:
You create a folder (mkdir) to store your project files.
You navigate into that folder (cd) to work inside it.
You initialize Git (git init) to enable version control and start tracking changes in your project.

## Making and Staging Changes
- Create a new file and add some content:
``echo "Hello, Git!" > hello.txt``
- Stage the file for committing:
``git add hello.txt``

## Committing Changes
- Commit the changes with a meaningful message:
``git commit -m "Add greeting file"``

### Exploring Commit History
- Display the commit history:
``git log``
- Use ``q`` to exit the log view.