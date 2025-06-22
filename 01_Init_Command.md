🔰 1. git init
✅ Purpose: Initializes a new local Git repository
This is the first command you run when you want to start using Git in a project folder

eg - git init

🔰 2. git remote add origin <URL>
✅ Purpose: Connects your local Git repo to a remote repo on GitHub

eg - git remote add origin https://github.com/username/repo.git

🔰 3. git remote -v
✅ Purpose: Shows the linked remote repositories

eg - Output
output : origin  https://github.com/username/repo.git (fetch)
origin  https://github.com/username/repo.git (push)

🔰 4. git branch
✅ Purpose: Shows all branches in your local repo

🔰 5. git branch -M main
✅ Purpose: Renames the current branch to main

🔰 6. git push origin main
✅ Purpose: Uploads your local code to GitHub
eg - git push -u origin main 
(So next time we don't have to use whole line and can only write git push )

typical flow to push a new project to GitHub:
git init                                 # Step 1: Start Git in the project
git add .                                # Step 2: Stage all files
git commit -m "First commit"             # Step 3: Commit with a message
git remote add origin <repo-url>         # Step 4: Link to GitHub
git branch -M main                       # Step 5: Rename to 'main'
git push -u origin main                  # Step 6: Push code to GitHub

