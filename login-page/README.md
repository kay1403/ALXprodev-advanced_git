ALXprodev-advanced_git
This project demonstrates the setup and initialization of a Git repository using the GitFlow workflow.

🚀 Objectives
Initialize a Git repository with GitFlow.
Create and push a develop branch.
Set up project structure using standard GitFlow branches (feature/, release/, hotfix/).
Create and commit a sample file (README).
🛠️ GitFlow Setup Steps
Install git-flow

sudo apt update
sudo apt install git-flow -y
Clone the repository

git clone https://github.com/your-username/ALXprodev-advanced_git.git
cd ALXprodev-advanced_git
Create and push the develop branch

git checkout -b develop
git push -u origin develop
Initialize GitFlow with default settings

git flow init -d
Create a README file

touch README.md
git add README.md
git commit -m "chore: add empty README.md"
git push
📚 Branches main – Stable production branch

develop – Integration branch for development

feature/* – Features under development

release/* – Pre-release preparations

hotfix/* – Critical production fixes
