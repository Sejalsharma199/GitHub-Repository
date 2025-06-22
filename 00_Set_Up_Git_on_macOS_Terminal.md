🧩 1. Install Git on Windows
1. Go to https://git-scm.com
2. Download the Windows installer
3. Run the installer:

a) Keep default settings
b) Choose Git Bash as default terminal (recommended)

After installation, open Git Bash and run:
git --version

2. Set Up Git (Configure user info)   //After downloading congigure it
Open Git Bash and run:
git config --global user.name "Git repository Name"
git config --global user.email "you@example.com"

You can check config with: git config --list

🧠 3. Link Git with VS Code
1. Install VS Code
2. Open VS Code → Go to Extensions → Install "GitHub Pull Requests and Issues" (optional)
3. VS Code will automatically detect Git if it's installed.

Now you can:
a)See a "Source Control" tab
b)Use Git inside the editor (commit, push, etc.)
