## Objective

My objective is to master basic Git by purely using the command line on my terminal. I have successfully created everything shown on this repo by using the command line only.

## Steps to Create a New Project

- 1. Open terminal
- 2. Navigate to directory where I want to create a new folder by using the change director command:
```Git
cd Desktop
```
- 3. Create a new folder by using the make directory command:
```Git
mkdir projectExample
```
- 4. Change directories into the new folder:
```Git
cd projectExample
```
- 5. Create any necessary files (ex: HTML, CSS & JS) by using the touch command:
```Git
touch index.html
touch styles.css
touch script.js
```
- 6. Check and see if the folders were made in the appropriate location with the specified files. Then, begin work onto VS Code.

## Steps to Initialize a Git Repository

- 1. Initialize an empty Git repo into the new folder:
```Git
git init
```
- 2. Verify changes:
```Git
git status
```
- 3. Add all files in the folder to the staging area:
```Git
git add .
```
- 4. Commit changes with a message:
```Git
git commit -m "Initial Commit"
```
- 5. Create a README file into current directory:
```Git
touch README.md
```
- 6. Add the README.md into the staging area:
```Git
git add README.md
```
- 7. Commit the README file with a message:
```Git
git commit -m "Added README file"
```

## Steps to push the repo to GitHub

- 1. Create a new repo on GitHub
- 2. Copy the local clone SSH key of my GitHub repo 
- 3. Link my local Git repo to my GitHub repo:
```Git
git remote add origin git@github.com:username/project-name.git
```
- 4. Push local chnages to the remote repo:
```Git
git push -u origin main
```

## Note

I like to always verify every step of the way by using git status. It is peace of mind!


## Done!

It is really that simple. Of course at first glance, it was difficult to grasp basic Git. I was even terrified of touching the Terminal and especially messing some command lines. But I persisted and successfully learned basic Git all thanks to The Odin Project (TOP)! I am now comfortable to be using Git as a normal practice in my programming journey. I am excited to implement this new skill!

## Acknowledgements

I like to give thanks to TOP for providing the help and resources of making Git understandable. I have looked everywhere on the web to search how Git works and TOP is by far the best resource to not only learning Git but also learning full stack web development.