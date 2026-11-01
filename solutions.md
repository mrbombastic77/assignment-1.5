Step-by-Step Completion Guide
Step 1: GitHub Account
Log in to your existing GitHub account (or sign up at github.com if needed).

Step 2: Create a New Public Repository
Go to GitHub and click the + icon in the top-right corner, then select New repository.

Give your repository a name (e.g., web-dev-assignment or cse-assignment).

Select Public.

Leave all checkboxes unchecked (Do not add a README, .gitignore, or license, as you are linking an existing local repository).

Click Create repository.

Step 3: Connect Local Repository to Remote
Open your terminal or command prompt inside your project folder (e.g., where your Assignment 1 files are located) and run the following commands. Replace YOUR_USERNAME and REPOSITORY_NAME with your actual GitHub details:

Bash
git init
git add .
git commit -m "Initial commit: Add assignment files"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/REPOSITORY_NAME.git
Step 4: Upload Files Using git push
Push your files to the remote repository for the first time:

Bash
git push -u origin main
Step 5: Add a New File and Push the Second Commit
To satisfy the requirement of adding a new file and making a second commit:

Create a new file in your project folder (for example, a README.md file or an extra text file).

Run the following commands in your terminal:

Bash
git add .
git commit -m "Second commit: Add new file / README"
git push
Step 6: Verify Commit History
Go to your repository page on GitHub in your browser.

Click on the Commits link (near the top, showing something like "2 commits").

Verify that both of your commits appear in the history.

Submission
Copy your public repository URL (it will look like [https://github.com/YOUR_USERNAME/REPOSITORY_NAME](https://github.com/YOUR_USERNAME/REPOSITORY_NAME)) and submit it for your assignment.