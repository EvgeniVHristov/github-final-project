

1
Final Project: Part 2 - Git CLI
Final Project: Part 2 - Git CLI

Estimated Time: 60 minutes

Important notice about this lab environment:
Please be aware that sessions for this lab environment are not persisted. Every time you connect to this lab, a new environment is created for you. Any data you may have saved in the earlier session would get lost. Plan to complete this lab in a single session, to avoid losing your data.

Scenario
Congratulations on starting the journey with your company by creating an open-source Simple Interest Calculator bash script on GitHub. Your changes have been accepted and merged and the company has created a new global repository for the teams to collaborate. Other developers have contributed to this repository over time. Your team has found a mistake in one of the markdown files. You are asked to fork this repository and fix the mistake by using Git CLI in the provided lab environment and open a pull request (PR).

Objectives
After completing this lab, you will be able to demonstrate that you can:

Fork the upstream repository into your own account.
Clone the code locally in the lab environment.
Create a branch in the repository.
Make changes in the branch and commit it.
Merge the branch back into the main branch.
Create a Pull Request from the forked repository to the upstream repository.
Revert a change that you made earlier.
Note: Throughout this lab, you will be prompted to copy and paste URLs into a notepad and save the notepad on your own device. These URLs will be uploaded for peer review in the Final Submission section of the course. You can use any notepad app to keep note of your URLs.

Task 1: Fork the repository
Fork the project's source repository.

Save the URL of your forked repository in a notepad to submit later for peer review.

Task 2: Fix the typo and merge with main
Clone the forked repository in the lab environment.

Create a branch named bug-fix-typo.

Change the footer in the main README.md file from

1
2022 XYZ, Inc.

Copied!

Wrap Toggled!
to

1
2023 XYZ, Inc.

Copied!

Wrap Toggled!
Add the file with your fix and commit it with a meaningful message.

Push your fix to the bug-fix-typo branch. In this step, you will need to generate a personal access token from GitHub.com to use as your password. Follow the instructions in the lab Generate GitHub personal access token.

Switch to the main branch. Merge the bug-fix-typo branch back into your main branch. Take a screenshot showing the current branch and successful merge operation with the file that has changed. Save the screenshot as merge_branches.png or merge_branches.jpg.

Task 3: Revert the typo and submit a pull request
Check the content of README.md in the main branch. The file should now read:

1
2023 XYZ, Inc.

Copied!

Wrap Toggled!
Create a new branch named bug-fix-revert.

Revert back the change you implemented in the previous task using the git revert command. The file should now read:

1
2022 XYZ, Inc.

Copied!

Wrap Toggled!
Push the revert to your repository in the bug-fix-revert branch. Please ensure you use the personal access token that you generated on Github for your account as the password (and not your actual git password), when prompted.

Go to the GitHub UI. Create a new pull request from the bug-fix-revert branch of your repository to the main branch of the original repository. This PR will be closed automatically. Note the URL of this PR in a notepad to submit later for peer review.

Task 4: Check the status of your branches
Navigate to the Branches section within the GitHub UI on your page. It will be in the following format:
1
https://github.com/<Your Github username>/jbbmo-Introduction-to-Git-and-GitHub/branches

Copied!

Wrap Toggled!
Within this section, you will find the branch names along with their current status.

Make a note of the URL of this page in a notepad to submit during peer review.

Checklist
After completing this part of the final project, you should have:

The forked repository URL.
The pull request URL.
The screenshot showing the merge operation of bug-fix-typo into main named merge_branches in png of jpg format.
The URL of the Branches page showing the branches of the repository and their status.
Summary
Congratulations! You have completed both parts of the final project. You have demonstrated that you know how to create an open-source project in Git, make changes to that project, and make it available to the community. You can fork a GitHub repository, clone it to your local system, make changes to the local repository, commit the changes locally, push it back to your GitHub fork, and create a pull request to add your update to the original repository.

Author(s)
Upkar Lidder

© IBM Corporation. All rights reserved.
