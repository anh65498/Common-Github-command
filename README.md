# Common-Github-command

## How to clone a remote repo and make it my repo

1) Copy the git url of that remote repo 

2) In local machine, create a new directory with `mkdir`, `cd` into it and `$ git clone https://github.com/URLFromStep1`

3) Back to your Github, create a private/public repo. **Do not** initialize with README

4) Now in local machine, `cd` into the folder you cloned earlier. 

5) If needed, remove the remote called origin and add your own Github repo as the new remote
```
git remote remove origin`
git remote add origin https://github.com/MyOwnGithubURL
git push -u origin master
```
  
If you now run `git remote -v` you should no longer see the remote called origin like you saw before. 

6) Add Collaborator in online Github setting



## How to fork a repo
