# OOP Git Assessment
## **Questions**
1.	**List three major version control software for software engineering.**
- Local Version Control System.
- Centralized Version Control System.
- Distributed Version Control System.

2.	**What are the main advantages to using Git in your software development, and how is it useful for game developers.** <br>
Developers each get their own local repository containing a full history of commits, as opposed to a working copy. Having a complete local history enables Git to operate quickly, as it eliminates the necessity of a network connection when making commits, accessing previous file versions, and comparing changes.

3.	**Define the following terms in relation to Git. Branch, Pull, Push, repository, working copy, merge** <br>
A Git repository serves as a central storage location for managing and tracking changes in files and directories. 
The git pull command is utilized to retrieve and download content from a remote repository and promptly synchronize the local repository with that content. 
The git push command is employed to publish local repository content to a remote repository. 
In Git, a "working copy" is a directory containing files with a .git subdirectory, which is essentially equivalent to a local git repository. Merging in Git involves recombining a forked history. 
The git merge command consolidates the independent lines of development created by git branch into a single branch.

4.	**If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git.** <br>
To solve a problem with the least amount of code, commit code in small increments to reduce the chance of integration conflicts. By using branches, software development teams can make changes without impacting the main codebase. The entire history of changes is monitored in a branch, and when the code is prepared, it is incorporated into the main branch. Composing descriptive commit messages is just as crucial as the change itself. Begin your commit messages with a verb in the present tense in an imperative mood to clearly and succinctly convey the purpose of each commit. Seeking feedback from others is a great way to ensure the quality of the code. Code reviews are an effective approach to determine whether a proposed solution effectively addresses a problem.

5.	**Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts.** <br>
- gitk: graphical history viewer for Git.
- git-gui: allows users to modify repositories by creating new commits, amending existing ones, creating branches, performing local merges, and fetching/pushing to remote repositories.
- Vimdiff3: Each file has its own window for inspecting and moving changes between versions.
- KDiff3: Open-source file comparison tool for Windows, OSX, and Unix/Linux, with an intuitive GUI for comparing and merging files.
- XXdiff: Graphical browser for viewing differences between files or directories and creating a merged version.

6.	**In a merged source code file, how does Git let you know there is a conflict?** <br> 
Git utilizes the longest common subsequence algorithm to handle merges and identify merge conflicts in simple text files.
The basic function of Git is to identify the longest consecutive set of lines that exist in both your modified file and the shared ancestor.

7.	**What are the steps you can take to resolve Git conflicts?** <br>
To resolve a conflicted file, open it and make any necessary changes. 
After editing the file, we can use the Git add a command to stage the new merged content. 
The final step is to create a new commit with the help of the git commit command.
Git will then create a new merge commit to finalize the merge.

8.	**What does git revert do, and how can you use it?**
The git revert command allows you to undo changes in a forward-moving manner and provides a safe way of undoing changes without actually deleting them.
- Access your repository in VS Code.
- Choose Source Control from the sidebar.
- Go to the COMMITS section.
- Right-click on the commit you wish to revert.
- Select the Revert Commit option.

9.	**What does git reset do, and how can you use it?**
Git reset is a command with significant capabilities which is used for reverting local changes made to a Git repository's state.
Step 1: Retrieve the previous commit:
Step 2: Revert the repository to that commit.

10.	**What is the difference between git revert and git reset?**
Git revert creates a new commit to undo changes, while Git reset HEAD is for undoing uncommitted changes.
11.	**True or False: It is okay to commit broken code to the main branch.** <br>
False

12.	**True or False: You should commit related changes. For example, fixing two different bugs should produce two separate commits.**
True

13.	**Describe what is DevOps, how is it useful for game developers?** <br> DevOps streamlines game development by automating build, testing, and deployment of assets, allowing developers to focus on critical tasks, refine processes, and collaborate effectively. In this model, development and operations teams merge into a single unit, working across the entire application lifecycle.

14.	**List what tools can be used with DevOps. Give a brief description of each one. (at least 3)** <br>
- Git DevOps tools are easy to implement as they are compatible with most protocols including HTTP, SSH, and FTP. They are advantageous for non-linear shared-repository development projects, making them suitable for mission-critical software.
- Maven - Maven is one of the important DevOps tools for building projects. Unlike the ANT build system, Apache Maven is more than just an automation build framework. It is also designed to manage reporting, documentation, distribution, releases, and dependencies processes. Written in Java language, Maven can build and manage projects written in Java or C#, Ruby, Scala, and other languages using project object model (POM) plugins.
- Jenkins - Jenkins is an integration DevOps tool. For continuous integration (CI), Jenkins stands out as it is designed for both internal and plugin extensions. Jenkins is an open-source Java-based automation CI server that is supported by multiple operating systems including Windows, macOS, and other Unix OSs. Jenkins can also be deployed on cloud-based platforms. 

15.	**What is CI/CD and how can it be used to automate the game development process?**
CI/CD is a method of delivering apps to customers regularly by incorporating automation into the stages of app development. Continuous integration, continuous delivery, and continuous deployment are the three main concepts associated with CI/CD. CI/CD is a solution to the problems that new code integration can cause for development and operations teams.
