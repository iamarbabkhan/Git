# Source Code Management: A Guide to Version Control Systems
When it comes to software development, maintaining a history of changes made in source code is always considered important not just as best practice but this practices stands immensely crucial. This is where Version Control Systems (VCS) are in use. A VCS allows developers to keep track of what changes have been made over time and makes it easy for others people (or even a previous version of oneself) to experiment or collaborate without compromising the project. Source Code Management: An introductory guide and setup instructions for Git Source code management is an essential...

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

**CVCS Workflow**
* In CVCS, the workflow typically involves a workspace (WS) or personal computer (PC) interacting directly with the remote repository. Changes are pushed from the workspace to the central server.
* **Advantage:** Easy to use.
* **Disadvantage:** Requires constant internet connectivity.

**DVCS Workflow**
* DVCS introduces the concept of a staging area between the workspace and the local repository. Changes are committed to the local repository and then pushed to the remote repository.
* **Advantage:** Offers flexibility with online and offline access.
* **Disadvantage:** May pose challenges for beginners.

### Key Terminologies
1. **Repository/Repo:** A storage location where code and files are saved and managed.
2. **Commit:** A record of changes made to the codebase, creating a new version.
3. **Snapshot:** An incremental backup representing the state of the codebase at a specific point in time.
4. **Pull Request:** A request to fetch changes from a remote repository to a local repository, often used in collaborative environments.
5. **Push Request:** A request to send changes from a local repository to a remote repository, updating the shared codebase.
6. **Fork:** Creating a personal copy of someone else's repository on platforms like GitHub.
7. **Origin:** The default name often given to the remote repository.

### Conclusion
Version control systems play a fundamental role in modern software development, enabling teams to collaborate seamlessly, track changes efficiently, and maintain the integrity of their projects. While various VCS options exist, Git stands out as a powerful and widely adopted tool, offering a robust architecture and extensive features for managing code repositories. By mastering the concepts and workflows of VCS, developers can streamline their development processes and contribute effectively to projects of any scale.
