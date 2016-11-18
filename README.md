# Reference
Program reference

## How to use git to upload project to github

### Normal Process
0. Create a remote repo on github
1. `$ git add .` : add files all you want into version control
2. `$ git commit -m "Initial commit"` : commit your files into local repo's version control
3. `$ git remote -v`: check whether there is any remote repo
4. `$ git remote add origin YOURRepoPath` : create a remote
5. `$ git push origin master` : push you local repo onto certain branch of the remote's repo

That's all, :sparkles::sparkling_heart:

### Some useful command

`$ git pull origin master` : when you come across collision, you must use this command to get the remote newest files

`$ git remote set-url origin https://username:password@gitPath` : when you behind proxy environment, chances are you need to set
username and password so that you can push your project
