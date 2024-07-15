
# Task 1: Repository Setup

**1. GitHub Repository Creation**
- You can log in to your GitHub account.
- Create a new PLPBasicGitAssignment repository and initialize it with a README file.
  
# Task 2: Local Setup

**2. Local Folder Setup**
-Create a new folder on your local machine named PLPBasicGitAssignment.
- Open a terminal or command prompt and navigate to the created folder PS C:\Users\Sheila\OneDrive\Documents\PLPBasicGitAssignment> `cd C:\Users\Sheila\OneDrive\Documents\PLPBasicGitAssignment`

**3. Git Initialization**
- Initialize a new Git repository in your local folder:`git init`

**4. Connecting to GitHub**
- Link your local repository to the GitHub repository:`git remote add origin https://github.com/SheilaNgetich/PLPBasicGitAssignment.git`
- Rename the default branch to main: `git branch -M main`

# Task 3: Making Changes

**5. Create a File**
- Inside your local folder, create a new text file named hello.txt and add a simple text message: `echo Hello Git! >hello.txt`
  
**6. Committing Changes**
- Stage the changes: git add hello.txt
- Commit the changes: `git commit -m "Add hello.txt with a greeting"`
  
# Task 4: Pushing to GitHub

**7. Pushing to GitHub**
- Push the committed changes to your GitHub repository: git push -u origin main

