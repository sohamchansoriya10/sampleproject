# sampleproject
sample project to test git functionality. I have learned the following commands which is git clone, git status, git branch

# how to work with Github project

first create a new repository on github.com.
Then go to repository and click on Code dropdown
Go to ssh tab and copy git@ repo path.
Then run the following commands locally
```
git clone <ssh>
git status
git branch --list

```

To create a new branch for making changes and committing changes run the following commands:
```
git branch <new branch name>
git checkout <new branch name>
git status
```

git status command should show you that you are on the new branch. make your changes and run the following commands to commit and push your changes to github:

```
git status
git add <files that you changed>
git commit -m "<messages>"
git push --set-upstream origin <new branch name>
```

then go to github.com and create a pull request. Review and merge your pull request. After merging delete the branch.