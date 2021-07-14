July 14, 2021

## Steps to push code to Github

- Create Folder for code
`mkdir nameOfFolder`
-  navigate into newly created folder
`cd nameOfFlolder`
- Create local Repository
`git init`
- Create code (files or folders)
`touch readme.md`   
// Creating a new file called readme.md
- REMEMBER TO SAVE YOUR CODE!!!
- Track/Stage/Watch all of the files/folder
```
git add .
git add -A    
//it's the same command with the above one.
```
- Commit our changes to our local git
```
    git commit -m "initial commit"
```
- Create a Github repo
```
create a new repo on Github

git remote add origin https://github.com/LILYHUANGPURSUIT/placeToPutReadme.git 
// the specific repository in GitHub

git push -u origin main
```?
