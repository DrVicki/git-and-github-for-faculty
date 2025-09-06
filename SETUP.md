# Set Up Git & GitHub

## Locating and Using the Terminal
**Windows**:
Option 1: Command Prompt
- Click on the "Start" button.
- Type cmd in the search bar and press Enter.
This will open the Command Prompt, which can be used for Git commands.

Option 2: Git Bash
- Git for Windows comes with a built-in terminal called Git Bash, which emulates a Linux-like command-line environment.
- After installing Git, click on the "Start" button.
- Type Git Bash in the search bar and press Enter.

Git Bash is now ready to use for running Git commands.

**macOS**:
Open the "Finder."

- Navigate to "Applications" > "Utilities."
- Double-click on "Terminal" to open it.

**Linux**:
- The terminal can usually be found in the "Applications" menu.
- Alternatively, you can press Ctrl + Alt + T to open the terminal quickly.

## Verify Git Installation
This command should return the installed version of Git, confirming the successful setup.

``git --version``

### Installing Git (If not installed)
Download and install Git from the official Git website.
- Follow the prompts for installation on the respective operating systems.
- After installation, open the terminal and type the following to verify Git is installed correctly:

``git --version``

## Creating a GitHub Account
- Visit GitHub, click on "Sign up," and create a free GitHub account.

## Configuring Git
It is important to configure Git with personal information to associate commits correctly with your GitHub account.

- In the terminal, set up the user name and email:

``git config --global user.name "Your Name"``
``git config --global user.email "your_email@example.com"``

These commands personalize the commits with your GitHub account details.
