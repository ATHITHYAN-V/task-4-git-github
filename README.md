# DevOps Project

## Overview
This is a sample DevOps project managed using Git best practices.

## Branching Strategy
- `main`: Production-ready code
- `dev`: Integration branch
- `feature/*`: Feature-specific development

## Technologies
- Git
- GitHub

## Step-1

- git init                          # Initialize local git repo
- git add README.md                # Stage the README.md file
- git commit -m "Git-Github-Task-4"    # First commit
- git branch -M main              # Rename current branch to 'main'
- git remote add origin https://github.com/ATHITHYAN-V/task-4-git-github.git  # Add GitHub repo as remote
- git push -u origin main         # Push to GitHub and set upstream


![dir](https://github.com/user-attachments/assets/0d309815-2db8-4bca-90dc-6ae814fe48bb)
![git init](https://github.com/user-attachments/assets/6b528c93-8b74-48d4-a7d3-9b492ca5c8ab)
![commit](https://github.com/user-attachments/assets/5395ddb5-1fce-4b77-a308-d11449d47e82)
![push](https://github.com/user-attachments/assets/33d59f72-c45d-47b2-ae64-c680318f35ad)

## Step-2

- git checkout -b dev
- git push -u origin dev

![dev](https://github.com/user-attachments/assets/34fb1133-64e0-480a-a009-2096481ad703)

## Step-3

- git checkout -b feature/task-4
- git push -u origin feature/task-4

![Screenshot 2025-04-11 204130](https://github.com/user-attachments/assets/e76721d7-e256-4185-988d-1ea3cf55e2b2)

## Step-4

## merging Dev from featureltask-4

![Screenshot 2025-04-12 091648](https://github.com/user-attachments/assets/20e1e0e9-0270-41e8-8dea-814e28c0ec58)

## Step-5

## merging main from Dev

![Screenshot 2025-04-12 092157](https://github.com/user-attachments/assets/9ceacdd6-1bbf-4693-a35c-3a993a5f451c)

## Step-6
## Tag Releases
- git tag -a v1.0 -m "Initial release"
- git push origin v1.0

![tag](https://github.com/user-attachments/assets/cd9d524e-5b25-4e61-b1a4-2d6cc2c28f71)

![image](https://github.com/user-attachments/assets/ad989aad-a716-42a9-a822-5aa581ecbaf9)












