1. --global allows the application of Git configuration to all repositories for my user account. If I would leave it out, the setting would apply to only my current repository.
2. .git appeared in ls -a but not in ls. Since it is a hidden directory. .git contains git's repository information, such as configuration, history and other internal data.
3. Git was offering the files in the coding-cafe folder for tracking, including the large number of files inside .venv. The .venv files were not written by me, these files belong to python virtual environment.
4. The .venv/ fies disappeared from the untracked files list because .venv/ was added to .gitignore.
5. It should be commmitted since .gitignore is part of the project anf tells git which files and folders have to be ignored. SO, this needs to be shared with the repository so Git knws what to ignore.
6. README.md moved from "Untracked files" to "Changes to be committed".It was moved from working tree stage to the staging area by git add README.md.
7. 4 files changed, 107 insertions(+). It said that 4 files changed.
8. The first seven characters of my commit are c5545ff. THey are the abbreviated form of the commit's unique commit hash (SHA) and are used to identify that particular commit.

