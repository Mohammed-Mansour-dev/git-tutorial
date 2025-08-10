How to Upload a  Project to GitHub Using Git:

1. Created the Project
2. Initialized a Git Repository
Inside the root folder of the project, I initialized Git: "git init"

3. Staged All Project Files
I added all files to the staging area using: "git add . " OR YOU CAN SPECIFY YOUT FILES 

Committed the Changes
I created my first commit with a message describing what was added:
"git commit -m "Add  PROJECT""

5. Created a GitHub Repository
I went to GitHub and created a new empty repository (without README, license, or .gitignore).


6. Connected the Local Repo to GitHub
In the terminal, I linked the local Git repo to the new GitHub repository:


git remote add origin https://github.com/Mohammed-Mansour-dev/git-tutorial


 7. Pushed the Project to GitHub
 I pushed the local project to the main branch of my GitHub repository:
"git branch -M main"
"git push -u origin main"


