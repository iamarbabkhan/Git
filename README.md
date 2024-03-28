### Source Code Management: A Guide to Version Control Systems
In the world of software development, keeping track of changes made to source code is not just good practice; it's essential. This is where Version Control Systems (VCS) come into play. VCS allows developers to efficiently manage and track changes to their codebase over time, facilitating collaboration, experimentation, and ensuring project integrity. In this article, we'll delve into the realm of Source Code Management, exploring its types, key terminologies, and the prominent player - Git.

### Understanding Version Control Systems
Types of version control system:
1. **Centralised version control system (cvcs)**
* **Tool:** SVN (Subversion)
* In CVCS, there's a central server that stores all versions of files and enables users to check out the latest version, make changes, and commit them back to the central repository.
* **Advantage:** User-friendly interface.
* **Disadvantage:** Requires constant internet access for operations.

2. **Distributed Version Control System (DVCS)**
* **Tool:** Git
* DVCS differs from CVCS by not relying solely on a central server. Instead, each user has their local repository, allowing them to work offline and then synchronize changes with remote repositories.
* **Advantage:** Offers both online and offline access.
* **Disadvantage:** Might have a steeper learning curve for beginners.

### Git Architecture:
![git architecture](https://phoenixnap.com/kb/wp-content/uploads/2021/09/git-workflow.png)
#### Cvcs: 
* Ws/pc - remote repository
* Its push mechanism
* Advantage: user friendly
* Disadvantage: only access through internet
#### Dvcs: 
* Ws/pc - staging area - local repository - remote repository
* Its pull mechanism
* Advantage: access online and offline
* Disadvantage: difficult for beginner


### Term used:
1. **Repository/repo:** storage to save code or file 
2. **Commit:** changes of code 
3. **Snapshot:** incremental backup
4. **Pull request:** fetching changes from remote repo to clocal repo
5. **Push request:** send changes from local repo to remote repo
6. **Fork:** creating a personal copy of someone repo in github
7. **Origin:** default name of remote repo
