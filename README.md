1.a)Why do we need git?

     Git is a widely used distributed version control system that provides a reliable and efficient way to track changes in files and collaborate on software development projects.
 
 b)Branch

     In Git, branches are used to create separate lines of development within a project. They allow developers to work on different features, bug fixes, or experiments independently without directly affecting the main codebase. Each branch represents a distinct snapshot of the project's code and its commit history.
        To create a new branch, you can use the command “git branch <branch-name>”.
        The command “git checkout <branch-name>” allows you to switch to a different branch.
        While working on a branch, we can make changes to files and use the “git add” and “git commit” commands to record those changes.
        After working on a branch and completing your changes, you can merge it back into another branch, typically the main branch, using the “git merge” command. 
         
  c)Commit

     A commit is a change that the developers made in the local repository and bring it to the remote repository or vice versa. Github monitors this commit periodically. Commits are the building blocks of version control in Git and play a crucial role in tracking the history of your project.
Commits in Git provide a comprehensive history of changes made to a project over time. They enable you to review and compare different versions of your codebase, revert to previous states, and understand the evolution of the project. Git's distributed nature allows developers to create and commit changes locally, maintaining a complete history even when working offline. When ready, commits can be pushed to a central repository or shared with collaborators.

d)log
   
In Git, the "log" command is used to display the commit history of a repository. It shows a detailed list of commits, including their unique identifiers (commit hashes), author information, timestamps, and commit messages. The log provides an overview of the changes made to the codebase, allowing you to track the project's history and understand its evolution.

Syntax
git log

e)Versions    
     In Git, versions refer to different snapshots of a project's codebase at specific points in time. Each version represents a distinct state of the project, including the files, directories, and their contents. Git allows you to track and manage these versions effectively.
Commands
  1.Status
          git status
 2.Pull
         git pull
3.Push
         git push <remote> <branch>
 4.Checkout
        The git checkout command allows you to switch to a different branch or a specific commit, updating your working directory to reflect the state of the selected branch or commit.
        git checkout <branch-name or commit-hash>

5.Commit
        Stage change
           Staging allows you to selectively choose which modified files or changes you want to include.
         git add <file1> <file2> …
        Provide a commit message
           After staging the changes, you need to provide a descriptive commit message that explains the purpose or summary of the changes.
         git commit -m "Your commit message"

        Execute the commit
         Once you have staged changes and provided the commit message, you can execute the commit using the following command:
        git commit

6.Log
      To view the commit history and logs in Git, you can use the git log command.
         1)Navigate to the directory of your Git repository using the cd command.
               cd /path/to/repository
          2)Run the git log command
               git log
