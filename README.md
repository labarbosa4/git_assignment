# Git Assignment - labarbosa4
a. What is an issue?

    An 'issue' is a tool used to transmit requirements, decisions, ideas, and more for a specific project. Additionally, issues allow the tracking of communications isolated within a specific project and keep them accessible to all collaborators involved.

b. What is a pull request?

    A 'Pull Request' is used to merge the changes made in a branch with the main and the original repository. Additionally if any changes were made and GitHub will check to make sure that there are no conflicts with the base branch.

c. Describe the steps to open a pull request?

    1. Make changes to the project
    2. Click on the "Pull Request" option
    3. Click on the "Compare & pull request" button
    4. Select the branches and repositories you want to merge into the pull request
    5. Review the changes displayed on the screen
    6. GitHub will check for conflicts between the base branch and the branch you are attempting to merge
    7. If there are merge conflicts, a pull request can still be created

d. Describe the steps to add a collaborator to a repository (share write permissions)

    1. Go to the repository.
    2. Click on the "Settings" option.
    3. In the left menu, select "Manage access."
    4. On the right side of the screen, click on the "Add people" button.
    5. A pop-up window titled "Add a collaborator to git-module" will open in GitHub.
    6. Start adding the name or email of the collaborator you would like to add.

    Note: Access does not have to be permanent. Collaborators can be removed at any time, and additional ones can be added whenever needed.

    Granting access to your repository will allow collaborators to make changes and push them to the repo without needing your constant permission. If push access is not granted, collaborators will need to fork the repo and create a pull request.

e. What is the difference between git and GitHub?

    Git: is a version control system that allows the tracking of changes made in a code

    GitHub: is a web-based platform that hosts Git reposd and allows collaboration tools, such as pull requests and issue tracking, to facilitate the teamwork on Git projects.

f. What does git diff do?

    The 'git diff' command is used to view detailed information about changes that have been made. It compares the contents of the working directory to those in the staging area. If changes have been made to the files without running 'git add', the comparison will be displayed. On the other hand, if there are no differences, nothing will be shown.


g. What is the main branch?

    The 'main branch' is the default branch in a Git repository where the source code is considered to be in a stable state. It is the branch where production-ready code is usually stored, and where features and changes are merged after being tested and reviewed. The main branch often serves as the primary line of development in a project.
    
h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?

    It is not recommended to push changes directly to the main branch, except for the initial commit. Instead, a better practice is to create a separate branch dedicated to store changes and then create a pull request or merge request to merge the changes made into the main branch after they have been reviewed and tested. This will help matain the stability of the main branch and allows a better teamwork and version control.