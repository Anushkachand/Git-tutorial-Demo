# Basic GitHub Concepts

- Repository (Repo): A folder that contains project files.
- Git: Tool used to track file changes.
- Commit: Saves changes to the repository.
- Branch: A separate version of the project.
-Push: Uploads code to GitHub.
- Pull: Downloads latest code from GitHub.
- Clone: Copies a repository to your computer.


# Basic Git Commands (Code)

1. Configure Git (First Time)
 ```
   git config --global user.name "Your Name"
   git config --global user.email "youremail@gmail.com"
```

2. Create a New Repository
 ```
    git init
```

3. Check File Status
```
  git status
```
4. Add Files to Git
```
   git add .
```
5. Commit Changes
```
git commit -m "Initial commit"
```
6. Connect to GitHub Repository
```
git remote add origin https://github.com/username/repository-name.git
```
7. Push Code to GitHub
```
git push origin main
```

8. Clone a Repository
```
   git clone https://github.com/username/repository-name.git
```
9. Pull Latest Changes
 ```
git pull origin main
```

## Steps to Push Code to GitHub:
- Initialize Git Repository
```
git init
```
- Add Files to Staging Area
```
git add .
```
### Commit the Changes
- git commit -m "Added project files"
#### Connect Local Repository to GitHub
- git remote add origin https://github.com/username/repository-name.git
  ## Push Code to GitHub
- git push origin main

##  Create Folder & File Directly on GitHub Website (Easy)
🔹 Create a Folder
- Open your GitHub repository
- Click Add file → Create new file
- In the filename box, type:
```
   01_basics/01_variables.js
```
👉 GitHub automatically creates the folder when you use /

 #### Add your code/content
- Scroll down → Commit changes
✔ Folder 01_basics
✔ File 01_variables.js
