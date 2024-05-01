






















































1. installing the GIT
➢ Download Git: Go to https://git-scm.com/download/win and get the Git installer for
Windows.
➢ Run Installer: Double-click the downloaded file to start the installation process.
➢ Follow Instructions: The installer will guide you through the process with simple
prompts. Just click "Next" or "Install" as appropriate.
➢ Choose Options: During installation, select "Use Git from the Windows Command
Prompt" so you can run Git commands from the Command Prompt or PowerShell
easily.
➢ Finish Installation: Once the installation completes, click "Finish".
➢ Check Installation: Open Command Prompt or Git Bash and type git --version to make
sure Git is installed correctly. You should see the installed version displayed.

3. manage public and private repository
➢ Create a Repository: If you haven't already, create a repository on GitHub. Sign in to
your GitHub account, click on the "+" icon in the top right corner, and choose "New
repository". Fill in the necessary details like repository name, description, etc., and click
"Create repository".
➢ Access Repository Settings: Once your repository is created, navigate to its main page.
You'll see options like "Code", "Issues", "Pull requests", etc. Click on the "Settings" tab
located near the top-right corner of the repository page.
➢ Change Repository Visibility: In the Settings page, scroll down until you find the
"Danger Zone" section.
➢ Under "Danger Zone", you'll find the "Change repository visibility" option.
➢ Click on "Change repository visibility" and select "Private" from the dropdown menu.
➢ Confirm Changes: After selecting "Private", GitHub will prompt you to confirm the
change. You might need to provide your GitHub password or re-enter your account
credentials to confirm the action.
➢ Save Changes: Once confirmed, click on the "Make private" button to save your
changes.
➢ Verify Repository Status: After making the repository private, its visibility will be
updated accordingly. You'll notice a lock icon next to the repository name, indicating
that it's now private.
4. Write and execute the commands to set up and configure git on your local machine.
   ![image](https://github.com/davidrobo2636/ASSIGNPUB/assets/153589442/c98606be-3ed2-4959-84c7-510a13febc52)
   ![image](https://github.com/davidrobo2636/ASSIGNPUB/assets/153589442/056e6f2f-0346-44bf-8590-47cfe298b722)
   ![image](https://github.com/davidrobo2636/ASSIGNPUB/assets/153589442/cd80f850-a3cb-4aa9-946c-c146910012b3)
4.performing basic operations in Git.
   ![image](https://github.com/davidrobo2636/ASSIGNPUB/assets/153589442/567ce8bb-a8d3-491a-bdc1-9a5624e34bb1)

6. Write and execute the three important steps of version control.
   ![image](https://github.com/davidrobo2636/ASSIGNPUB/assets/153589442/d6c61c14-a49b-4599-abb3-03a2180867c6)

8. execute git add, git commit, git push, git pull, git status.
   ![image](https://github.com/davidrobo2636/ASSIGNPUB/assets/153589442/64cff08c-1cf6-476f-bedc-aaecd3415995)
   ![image](https://github.com/davidrobo2636/ASSIGNPUB/assets/153589442/03373184-a0d2-405f-95d3-036fea5f8eba)

10. Explain and execute how to create branches and merging branches.
Creating branches
To keep track of changes to this file using git, you need to:
1. Clone the repository.
2. Move into the cloned repository
3. Create a new branch using the command (replace feature-branch with
your desired branchname).
git checkout -b feature-branch
4. Make modifications to files in your project.
5. Use git add to add the changes to the staging area
6. Commit the changes with a meaningful message
Merging branches
To keep track of changes to this file using git, you need to:
1. Switch back to the main branch.
git checkout main
2. Merge the branch into the main branch
git merge feature-branch
3. Resolve conflicts (if necessary)
i. Open the conflicting files and resolve the conflicts manually.
ii. After resolving conflicts, add the changes to the staging area and commit:
git add .
git commit -m "Merge feature-branch into main"
4. Push changes to github using the following command.
git push origin main

8.Create and Address GitHub Issues
1. Create a new issue in your repository:
i. Go to your GitHub repository.
ii. Click on the "Issues" tab.
iii. Click the "New issue" button.
iv. Fill in the issue title and description.
v. Optionally, assign the issue to a collaborator, apply labels, and set milestones.
2. Assign the issue to a collaborator:
i. Within the issue, use the "Assignees" section to assign the issue to a
collaborator.
ii. The assigned collaborator will receive notifications about the issue.
3. Label the issue with appropriate tags:
i. Apply labels to categorize and prioritize issues.
ii. Create and use labels like "bug," "feature," or any relevant labels for your
project.
iii. Labels can be added when creating the issue or edited later.
4. Close the issue using a commit message:
i. Make changes to the codebase to address the issue.
ii. In your local repository, commit the changes with a commit message
that references theissue number:
git commit -m "Fix #1: Resolve issue with feature X"
Replace "1" with the actual issue number.
iii. Push the changes to GitHub:
git push origin main
The issue will be automatically closed when the commit is pushed.


![WhatsApp Image 2024-05-02 at 12 23 34 AM](https://github.com/davidrobo2636/ASSIGNPUB/assets/153589442/3df11022-1b4a-4e38-b3dd-30b508195e5e)
![Screenshot 2024-05-02 002244](https://github.com/davidrobo2636/ASSIGNPUB/assets/153589442/294a112d-e895-4863-966d-226c8ea99b67)
![Screenshot 2024-05-02 002231](https://github.com/davidrobo2636/ASSIGNPUB/assets/153589442/e731c0bb-6b1c-49ef-9941-a090187dff85)
