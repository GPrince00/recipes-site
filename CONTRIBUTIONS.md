# Contributing Guidelines

## Step 1 : Find an issue
- Take a look at the Existing Issues or create your **own** Issue!
- Wait for the Issue to be assigned to you after which you can start working on it.
- Note : Every change in this project should/must have an associated issue.

## Step 2 : Fork the Project
- Fork this Repository. This will create a Local Copy of this Repository on your Github Profile. Keep a reference to the original project in `upstream` remote.
```
$ git clone https://github.com/<your-username>/recipes-site
$ cd recipes-site
$ git remote add upstream https://github.com/<your-username>/recipes-site
```

- If you have already forked the project, update your copy before working.
```
$ git remote update
$ git checkout <branch-name>
$ git rebase upstream/<branch-name>
```
## Step 3 : Branch
Create a new branch. Use its name to identify the issue your addressing.
```
# It will create a new branch with name Branch_Name and switch to that branch 
$ git checkout -b branch_name
```
## Step 4 : Work on the issue assigned
- Work on the issue(s) assigned to you. 
- Add all the files/folders needed.
- After you've made changes or made your contribution to the project add changes to the branch you've just created by:
```
# To add all new files to branch Branch_Name
$ git add .
```
## Step 5 : Commit
- To commit give a descriptive message for the convenience of reveiwer by:
```
# This message get associated with all files you have changed
$ git commit -m 'message
```

## Step 6 : Work Remotely
- Now you are ready to your work to the remote repository.
- When your work is ready and complies with the project conventions, upload your changes to your fork:

```
# To push your work to your remote repository
$ git push -u origin Branch_Name
```

## Step 7 : Pull Request
- Go to your repository in browser and click on compare and pull requests. Then add a title and description to your pull request that explains your contribution.
