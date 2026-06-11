🚀 Project Description



This project demonstrates basic and advanced Git operations such as repository creation, commits, branching, merging, rebasing, and stashing.

It is part of a DevOps learning assignment to understand version control workflows.



📁 Project Structure

vcs-task/

│

├── script1.sh

├── script2.sh

├── screenshots/

│   ├── git-init.png

│   ├── git-commit.png

│   ├── git-push.png

│   ├── merge.png

│   ├── rebase.png

│   └── stash.png

│

└── README.md

⚙️ Steps Performed

1️⃣ Git Setup

Installed Git

Configured username and email

Initialized local repository

git init

git config --global user.name "Akshaya"

git config --global user.email "your-email@example.com"

2️⃣ File Creation



Created shell scripts:



script1.sh

script2.sh

echo "Hello from Script 1" > script1.sh

echo "Hello from Script 2" > script2.sh

3️⃣ Initial Commit

git add .

git commit -m "Initial commit"

4️⃣ GitHub Connection



Connected local repo to GitHub:



git remote add origin <repo-url>

git branch -M main

git push -u origin main

5️⃣ Branching \& Merge

git checkout -b feature-branch

echo "Feature update" >> script1.sh

git add .

git commit -m "Feature update"

git checkout main

git merge feature-branch

6️⃣ Rebase Operation

git checkout -b rebase-branch

echo "Rebase change" >> script2.sh

git add .

git commit -m "Rebase commit"

git checkout main

git rebase rebase-branch

7️⃣ Stash Operation

echo "Temporary change" >> script1.sh

git stash

git stash list

git stash pop

📸 Screenshots



All command outputs and GitHub repository proof are added in the screenshots/ folder.

