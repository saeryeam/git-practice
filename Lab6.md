# **Git Command Note**
##### 202334469 박세렴
　
　　
### **About 'Git'**
---
**Git :** Git is a distributed version control system (DVCS) that is widely used for tracking changes in source code during software development. It allows multiple developers to work on a project simultaneously, keeping track of changes, and collaborating efficiently.

**Git Commit :** A commit is a snapshot of the project's current state. Each commit has a unique identifier (SHA-1 hash) and contains changes made since the previous commit.

　
　**Snapshot (Centralized) Version Control**
 - In a snapshot (or centralized) version control system, there is a central repository that stores the entire history of the project.
 - Developers clone the project from the central repository and make changes locally.
 - To save changes, they commit them back to the central repository.
 - This approach is typically more suitable for projects with a small team and a single central location.
 
 **Distributed Version Control**
 - In a distributed version control system like Git, each developer has their own complete copy of the project repository, including its history.
- Developers can work independently on their local repositories, committing changes as needed.
- Changes can be shared and merged between repositories, allowing multiple contributors to collaborate seamlessly.
- his approach is well-suited for larger projects and teams distributed across different locations.


### **Git command**
---
| command | explain |
|---|---|
|git config|Global configuration settings are applied to all Git repositories on your system. You can use the 'git config --global' command to set global settings like your name and email address.|
|git init|'git init' is a Git command used to initialize a new Git repository in a directory. When you run 'git init' in a directory, Git creates a hidden subfolder within that directory, which contains all the necessary files and subdirectories to start tracking changes in your project.|
|git status|'git status' is a Git command used to display the status of your working directory and staging area. It provides information about which files are untracked, modified, or staged for the next commit.|
|git add[file_name]|'git add[file_name]' is used when you want to upload a particular file to the staging area==Ready to commit)|
|git add.|'git add' is a Git command used to stage changes for the next commit. It tells Git to start tracking new files or stage modifications to existing files. You can specify which files or directories to add, or you can use 'git add' . to add all changes in the current directory and its subdirectories.|
|git rm --catched[file_name]|'git rm --cached [file_name]'' is a Git command used to unstage a file that was previously staged for the next commit. This command removes the file from the staging area, but it does not delete the file from your local filesystem or your Git repository's history. It's useful when you've accidentally added a file to the staging area and want to undo that action.|

### **Ignoring a file**
---
**. gitignore :** '. git ignore' is not a command. Git serves to prevent files from being tracked, and you can create a 'gitignore' directory to store and use files that you want to ignore tracking in it.


