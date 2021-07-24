# What is Git?

Gits is a DVCS (Distributed Version Control). Before DVCS there was Centralized Version Control or CVCS. But first, what is Version Control? Version Control is a system that records changes to a single or set of files over time so that later you can recall a specific version of that file. 

### CVCS
* CVCS is a single server that stores all changes and file versions that can accessed by different clients streamlining collaboration. 
* CVCS had a flaw though, sense it was a single point, if it failed no one is able to collaborate on their project and can only access what is on their local disk.

### DVCS 
* DVCS allows mulitipl mirrored repositories to be created to prevent any loss.
* Programmers can work together, but in different ways and at the same time. 

### Git
* Git relies on **local operations**. This allows for faster processing because it's stored on a local disk. Enabling you to also work offline. 
* You can **track changes**. All changes made to a file or directory that are saveds is tracked by Git. Git will always track if there are any loss or corruption in the file and or directories. 
* Git makes it very hard to lose data.

There are 3 main states of files in Git:
1. **Committed**: the data is stored securely in a local database
2. **Modified**: file is changed but not saved or committed to the database
3. **Staged**: flagged file's changed version to be committed in the next snapshot. 

**Snapshot** is basically like a picture taken of what your code looks like at that given moment. 

### Structure of a Repository
A repository is what is created to track all changes that are made. You are able to go back and review a timeline of these changes. A repository is structured as follows:
1. **Working Directory:** Actual files are located here
2. **Index:** used for staging
3. **Head:** directs you to the most recent commit made. 

#### Set up a Repository
1. Change the directory: ```cd [name of directory]```
2. Use ```git init``` (this initializes or starts the file/directory.
3. Begin tracking the repository file and initial commit: ```git add *.c``` 
 ```git add LICENSE```
 ```git commit -m "Message goes here"``` (you will press enter after each command).
 
 * There are tracked and untracked files. *Tracked* will be modified, unmodified or staged in the most recent snapshot. *Untracked* changes ere not in the last snapshot or in the staging area. 

### Remote Repositories
Remote repositories are online allowing for teams to work together on a single project giving them the ability to push and pull data. 

### Git Commands

* ```git commit -m "message here"``` saves a project or changes to a project. Creating a snapshot of the file and creates a reference. 
* ```git commit -a``` saves all files. 
* ``` git clone [URL]``` creates a copy of a repository. **_Note_** Cloned repositories automatically give the anme origin from the server that you cloned from and "master" on your local branch. 
* ```git status``` checks file status.
* ```git add [filename]``` tracks and stage a single file.
* ```git add *``` tracks and stages all files.
* ```git push origin master``` pushes from local master branch to remote repository called origin.
* ``` git stash``` allows you to hide changes you are not ready to commit just yet.
* ``` git stash apply``` brings back the hidden changes if you are ready to work on them again. 
* ```git remote``` allows you to view the short names of all specified remote handles.
* ```git remote -v``` view all URLs that correspond to their short names
* ```git remote add shortname URL``` creates a git remote repository with a short name. 
* ```git fetch [remote-name]``` to fetch or pull data you don't have from the remote project. 
* ```git fetch origin``` to get cloned repositories. *_Note_* Fetch only pulls new data to the local repository. It does not merge or modify with your local work. 
* ```git push [remote-name] [branch-name]``` pushes changes to the origin repository from your local master branch.
* ```git remote rename``` renames the remotes short name. Example: ``` git remote [oldname] [newname]```
* ```git remote rm``` removes a remote.

