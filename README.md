// initialize git repo in the folder where you store the workshop files
git init
// add all files
git add -A 
// commit the files
git commit -m "first commit"
// change the branch name to main
git branch -M main
// configure the remote/github url
git remote add origin 'your-github-repo'
// upload it to github
git push -u origin main
