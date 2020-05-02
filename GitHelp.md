# Git Help

1. Signup for GitHub account
2. Create Github repository in browser
3. Get git installed your machine
4. Work with created repo through clone
`git clone <repo name>`

`git clone 'https://github.com/rk4github/dev-env-setup.git'`

 Push changes to github repository
---
`git init`
`git add README.md`
`git commit -m "first commit"`
`git remote add origin https://github.com/rk4github/dev-env-setup.git`
`git push -u origin master`

Add a File to Commit
---
git add \<filename>  
`git add myfile.md`

Commit Changes
---
git commit -m \<commit comment>
git commit -m `my changes description`

Push local changes to master repository
---
`git push -u origin master`