1. --global allows the application of Git configuration to all repositories for my user account. If I would leave it out, the setting would apply to only my current repository.
2. .git appeared in ls -a but not in ls. Since it is a hidden directory. .git contains git's repository information, such as configuration, history and other internal data.
3. Git was offering the files in the coding-cafe folder for tracking, including the 100+ number of files inside .venv. The .venv files were not written by me, these files belong to python virtual environment.
4. The .venv/ fies disappeared from the untracked files list because .venv/ was added to .gitignore.
5. It should be commmitted since .gitignore is part of the project and tells git which files and folders have to be ignored. So, this needs to be shared with the repository so Git knows what to ignore.
6. README.md moved from "Untracked files" to "Changes to be committed".It was moved from working tree stage to the staging area by git add README.md.
7. 4 files changed, 107 insertions(+). It said that 4 files changed.
8. The first seven characters of my commit are c5545ff. They are the abbreviated form of the commit's unique commit hash (SHA) and are used to identify that particular commit.
9. Edit the file, git add (stage), git commit and repeat for the next stage.
10. README.md gets a special name and location because it is the universal entry point for projects. Especially GitHub automatically find README.md in the root folder and displays it formatted right on the main project page. By convention, It signals anyone visiting the repository that this is the first file that they should read to understand about the details of the project.
11. gh auth login saved an authentication code locally in Git's credential helper, allowing Git to authenticate automatically without prompting for a password on future pushes.
12. The new repository coding-cafe is showing on the front page because pushing locally commits to GitHub successfully created and updated the remote repository.
13. No, running git log --oneline shows the same commit history of 3 (1617893, bc4747b, c5545ff), which confirms that pushing only uploaded the commits to GitHub without changing any local history. 
14. A private repository exists on GitHub's servers, storing commits and code securely so that only invited collaborators and I can view or access it. If a repository does not exist on GItHUb at all, the code only lives locally on device, that is, GitHub hosts no files and no one else can view or access it. 

