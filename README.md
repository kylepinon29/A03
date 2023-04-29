# AO3

Part 1 
1. First we need to install git into our machines in order to use Github and Webstorm. 
2. Install git at https://git-scm.com/downloads
3. Install Webstorm at https://www.jetbrains.com/student/ 
4. Setup a Github account at https://github.com/join 
5. Connect your Github account with Webstorm. 
   - In webstorm open system prefrences -> Select version control -> Git -> enter git.exe path 
6. On Github, create a repository. To do so click the + in the upper right corner
7. Make repository public and add a readme file
8. Import repository on Webstorm from Version Control 
9. Now we have everything set up, we can add files on our webstorm project. 
    - Choose File -> HTML file
10. In order to save our files and changes from Webstorm to Github we must:
    In the Terminal 
    - Add files using the command git add . 
    - Commit our changes using the command git commit -m "message"
    - Push changes to remote repository using the command git push origin main(or to which branch is needed)

Part 2
**Branch** - A branch is a parallel version of a repository. It is contained within the repository, but does not affect the primary or main branch allowing you to work freely without disrupting the "live" version. When you've made the changes you want to make, you can merge your branch back into the main branch to publish your changes. 

**Clone** - A clone is a copy of a repository that lives on your computer instead of on a website's server somewhere, or the act of making that copy. When you make a clone, you can edit the files in your preferred editor and use Git to keep track of your changes without having to be online. The repository you cloned is still connected to the remote version so that you can push your local changes to the remote to keep them synced when you're online.

**Commit** - A commit, or "revision", is an individual change to a file (or set of files). When you make a commit to save your work, Git creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of the specific changes committed along with who made them and when. Commits usually contain a commit message which is a brief description of what changes were made.

**Fetch** - When you use git fetch, you're adding changes from the remote repository to your local working branch without committing them. Unlike git pull, fetching allows you to review changes before committing them to your local branch.

**GIT** - Git is an open source program for tracking changes in text files. It was written by the author of the Linux operating system, and is the core technology that GitHub, the social and user interface, is built on top of.

**Github** - GitHub is an Internet hosting service for software development and version control using Git. It provides the distributed version control of Git plus access control, bug tracking, software feature requests, task management, continuous integration, and wikis for every project.

**Merge** - Merging takes the changes from one branch (in the same repository or from a fork), and applies them into another. This often happens as a "pull request" (which can be thought of as a request to merge), or via the command line. A merge can be done through a pull request via the GitHub.com web interface if there are no conflicting changes, or can always be done via the command line.

**Merge Conflict** - A difference that occurs between merged branches. Merge conflicts happen when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file. The merge conflict must be resolved before you can merge the branches.

**Push** - To push means to send your committed changes to a remote repository on GitHub.com. For instance, if you change something locally, you can push those changes so that others may access them. 

**Pull** - Pull refers to when you are fetching in changes and merging them. For instance, if someone has edited the remote file you're both working on, you'll want to pull in those changes to your local copy so that it's up to date. See also fetch.

**Remote** - This is the version of a repository or branch that is hosted on a server, most likely GitHub.com. Remote versions can be connected to local clones so that changes can be synced.

**Repository** - A repository is the most basic element of GitHub. They're easiest to imagine as a project's folder. A repository contains all of the project files (including documentation), and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private.



