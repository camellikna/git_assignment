# Git Assignment - <Your GitHub Username>
a. What is an issue?
when a project manager or anyone face an Issue , he can open an issue in Github , after that we can link Repository to any issue to link solution to problem

b. What is a pull request?
When you change some code , you should make a pull request to check and merge with main code

c. Describe the steps to open a pull request?
open pull request , request the pull , submit

d. Describe the steps to add a collaborator to a repository (share write permissions)
Navigate to Your Repository:
Go to your GitHub profile and click on the repository where you want to add a collaborator.
Go to the "Settings" Tab:
On the repository's page, click the Settings tab located at the top, typically next to the "Security" tab.
Access the "Collaborators and Teams" Section:
Scroll down on the left sidebar and click on Collaborators and Teams under the "Access" section.
Invite a Collaborator:
In the "Collaborators" section, click on the Add People button.
Enter the username, full name, or email address of the person you want to add as a collaborator.
Select the correct user from the search results.
Send the Invitation:
Click on the Invite button to send an invitation. The person will receive an email notification and will need to accept the invitation to gain write access to the repository.
Wait for Acceptance:
Once the collaborator accepts the invitation, they will have write access to your repository.

e. What is the difference between git and GitHub?
Git is the tool used for version control, while GitHub is a service that hosts Git repositories and provides a collaborative environment.

f. What does git diff do?
The git diff command shows the differences between changes in your working directory, staging area, and the latest commit. Specifically, it compares:
Unstaged Changes: The differences between files in your working directory and the latest commit.
Staged Changes: The differences between the staging area and the latest commit (when used with the --staged option).
Essentially, it helps you see what modifications have been made but not yet committed.


g. What is the main branch?
The main branch (formerly called master) is the default branch in a Git repository where the stable and production-ready code usually resides.
When you initialize a Git repository, the main branch is automatically created.
It typically reflects the latest working version of the project.
Developers often create feature branches from main, and once the feature is complete and reviewed, it is merged back into the main branch.


h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?

It is generally not recommended to push changes directly to the main branch, especially in collaborative environments. Instead, the best practice is to use feature branches and pull requests to ensure that code is properly reviewed and tested before being merged into the main branch.