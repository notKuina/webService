# Today we'll learn about github and its contributions
###
…or create a new repository on the command line
echo "# webService" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/notKuina/webService.git
git push -u origin main
### …or push an existing repository from the command line
git remote add origin https://github.com/notKuina/webService.git
git branch -M main
git push -u origin main