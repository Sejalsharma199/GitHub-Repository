Resolving Merge Conflicts -
An event that takes place when Git is unable to automatically resolve differences in code between two commits

Step 1) Run
git merge feature-login

And Git says: Auto-merging index.html
CONFLICT (content): Merge conflict in index.html

🔹 Step-by-step:
1) Open the conflicted file (VS Code highlights it)
2) You’ll see the same markers:
<<<<<<< HEAD
Old text from main branch
=======
New text from feature-login branch
>>>>>>> feature-login

3)Manually edit and remove the conflict markers, then save
Eg : Final version you choose here

4)After fixing all files, mark them as resolved:
git add <file>

5)Then commit the merge:
git commit -m "Resolved merge conflict"

6)(Optional) Push to GitHub:
git push origin main


