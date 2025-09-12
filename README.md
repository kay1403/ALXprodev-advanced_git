# ALXprodev-advanced_git

This project demonstrates the setup and initialization of a Git repository using the **GitFlow** workflow.

## Objectives

- Initialize a Git repository with GitFlow.
- Create and push a `develop` branch.
- Set up project structure using standard GitFlow branches (`feature/`, `release/`, `hotfix/`).
- Create and commit a sample file (README).

## GitFlow Setup Steps

1. **Install git-flow**  
   ```bash
   sudo apt update
   sudo apt install git-flow -y
   ```

2. **Clone the repository**
    ```bash
    git clone https://github.com/kay1403/ALXprodev-advanced_git.git
    cd ALXprodev-advanced_git
    ```

3. **Create and push the develop branch**
    ```bash
    git checkout -b develop
    git push -u origin develop
    ```

4. **Initialize GitFlow with default settings**
    ```bash
    git flow init -d
    ```

5. **Create a README file**
    ```bash
    touch README.md
    git add README.md
    git commit -m "chore: add empty README.md"
    git push
    ```

6. **Branches**
    main – Stable production branch

    develop – Integration branch for development

    feature/* – Features under development

    release/* – Pre-release preparations

    hotfix/* – Critical production fixes

