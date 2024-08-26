# Git Assignment - <Parisaghotbi>

a. What is an issue?

Github Issues is a powerful feature to do project management on a software team. We can define tasks, steps or problems and track requested changes in a software project. Github provides this opportunity that everyone in the team is able to take a look at any faced issue.

b. What is a pull request?

A GitHub Pull Request (PR) is a feature that facilitates collaboration and code review in a Git version-controlled project. It allows developers to propose changes to a codebase, review those changes, discuss potential improvements, and finally merge them into the main project.

c. Describe the steps to open a pull request?

Opening a pull request (PR) on GitHub involves a series of steps  
1. Create a Branch: git checkout -b branch_name  
2. Make Changes and Commit Them: git add -A and git commit -m "Description of changes"  
3. Push the Branch to GitHub: git push origin branch_name  
4. Go to GitHub Repository  
5. Start a New Pull Request: GitHub might automatically suggest opening a pull request after pushing a new branch. If so, click on the “Compare & pull request” button.
If not, go to the "Pull requests" tab in my repository and click the "New pull request" button  
6. Fill Out the Pull Request Form: Title and Description  
7. Review the Pull Request: see a comparison of the changes between the main branch and my feature branch  
8. Submit the Pull Request: Click the "Create pull request" button  
9. Participate in the Review Process: The pull request is now open for review. Collaborators can comment on my changes, request modifications, or approve the PR  
10. Merge the Pull Request: Once the pull request has been reviewed and approved, it can be merged into the base branch, by clicking the "Merge pull request" button

d. Describe the steps to add a collaborator to a repository (share write permissions)  
1. Navigate to My Repository  
2. In the Repository Settings  
3. Click on Collaborators  
4. Add a Collaborator by clicking on "Add People"
5. After clicking "Add collaborator," GitHub will send an invitation to the selected user  
6. Collaborator accepts the invitation  
7. Confirm the collaborator has write access  

e. What is the difference between git and GitHub?

Git is the tool that developers use on their local machines to manage code and version control. It tracks changes, manages branches, and keeps a history of the codebase.  
GitHub is a platform that hosts Git repositories online, enabling developers to collaborate, manage projects, and share code with others. It adds features like pull requests, issue tracking, and social networking for developers.

f. What does git diff do?

The git diff command in Git is used to show the differences between various states of a repository. It displays the changes between two commits, the changes between your working directory and the staging area, or the changes between the staging area and the last commit.   

g. What is the main branch?

The main branch is the primary branch in a Git repository that holds the stable, production-ready code. It is the default branch created when initializing a new repository and serves as the central integration point for new features and bug fixes. 


h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?

No, we should not push changes directly to the main branch, especially in a collaborative or production environment. Instead, we should create separate branches for new features, bug fixes, or any other changes. 