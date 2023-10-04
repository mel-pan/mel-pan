# Tutorial On Github/Git/Webstorm
## Step 1: Download Webstorm
1. Download WebStorm from the official website: https://www.jetbrains.com/webstorm/download/#section=mac
2. Follow instructions based on operating system

##Step 2:Configure Git in WebStorm
Open WebStorm.

Go to File > Settings (on Windows) or WebStorm > Preferences (on macOS).

In the left pane, expand Version Control, and select Git.

In the right pane, ensure that the Path to Git executable points to the Git executable on your system. If Git is not installed, you can download it from Git Downloads.

Click OK to save your settings.

## Step 3: Create or Open a Project
Create a new project or open an existing one in WebStorm.

Ensure that your project is in a directory that is not already a Git repository. If it is, you can skip the next step.

## Step 4: Initialize a Git Repository
Open the terminal within WebStorm by going to View > Tool Windows > Terminal.

Navigate to your project directory using the cd command. For example:

bash
Copy code
cd /path/to/your/project
Initialize a new Git repository by running:


git init
## Step 5: Create, Edit, and Save Files
1. You can now create or edit files in your project.

Save your changes.

## Step 6: Stage and Commit Changes
1. Open the Git tool window by going to View > Tool Windows > Git.

2. In the Git tool window, you will see a list of untracked and modified files. Right-click on a file or directory and select Add to VCS to stage it.

3. Enter a commit message in the "Commit Message" box.

4. Click the green checkmark icon or use the keyboard shortcut Ctrl+Enter (Windows) or Cmd+Enter (macOS) to commit your changes.

## Step 7: Push to GitHub
1. Create a GitHub account if you don't have one: [GitHub Sign-Up.](https://github.com/join)

2. Create a new repository on GitHub: [Creating a New Repository.](https://docs.github.com/en/get-started/quickstart/create-a-repo)

3. In the terminal, add your GitHub repository as a remote:

4. Replace <repository-url> with your GitHub repository's URL.

5. Push your local repository to GitHub



**Branch:** A separate line of development within a Git repository.

**Clone:** To make a copy of a repository, including all its history and files, on your local machine.

**Commit:** A Git command used to save changes to the local repository.

**Fetch:** A Git command used to download changes from a remote repository but does not automatically merge them into your local branch.

**GIT:** A distributed version control system used for tracking changes in source code during software development.

**GitHub:** A web-based platform for hosting and collaborating on Git repositories.

**Merge:** To combine changes from one branch into another.

**Merge Conflict:** Occurs when Git cannot automatically merge changes, and manual intervention is required.

**Push:** A Git command used to upload local changes to a remote repository.

**Pull:** A Git command used to fetch and merge changes from a remote repository into the current branch.

**Remote:** A reference to a Git repository on a server, typically on GitHub or another hosting service.

**Repository:** A storage location for a Git project, including all its files and version history.


References:
