# Git
Git can be thought of as a timeline management utility, which stores snapshots of our repository at different points of time, depending upon we committing to it, so that, we can go back and see the changes we made or if we need to go back to the previous code.

### Initialize git
To initialize git repository in the repository that you want to track just do  - git init

### Commit changes 
example create a file a.txt - to commit that change do - git add a.txt +Enter, then, git commit -m "commit message" +Enter.

### Different git commands
git status - to check git status like what changes we have made and not committed or if did then it shows that.
git log - log all the git commits till date.


# Github
 GitHub is just a social media platform for sharing and looking at the git repository for collaboration with other people or for showing to public, that's it.
 
## Creating our own repostory
In this case we do - git remote add origin repostory_link (here remote means that remote repository public github repo and origin is the variable for referring to the link, our repository will always be reffered as origin, it's a naming convention.

### push changes to github repo
command - git push origin master (we should always create a diffenet branch for adding some feature or resolving some bug, then that branch should get merged to the main branch, but here master is the main branch)


### Error while pushing in the main branch
when our local repo is not with sync with the remote repo, means remote repo has some changes that our repo doesn't then we can't push it to main branch, we need to create a diffrent branch.
But to resolve it we can do command - git fetch origin + Enter, then, git pull origin master

### create a different branch
command - git branch branch_name
git checkout branch_name - now the branch is changed or shifted to branch_name from master.

## Cloning some other repo
First fork it then clone it command - git clone repo_link_from your forked version
Initialize git in that repo, then always whatever you want to push do it by creating a different branch, Ok

