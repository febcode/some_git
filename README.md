## **IMP Commands for GIT**

**Adding a local repository to GitHub using Git**
- Before you can add your local repository to GitHub using Git, you must authenticate to GitHub on the command line. For more information, see About authentication to GitHub.
- Create a new repository on GitHub. To avoid errors, do not initialize the new repository with README, license, or gitignore files. You can add these files after your project has been pushed to GitHub. 
- At the top of your repository on GitHub's Quick Setup page, click  to copy the remote repository URL.
- Open Git Bash.
- Change the current working directory to your local project.
- To add the URL for the remote repository where your local repository will be pushed, run the following command. Replace REMOTE-URL with the repository's full URL on GitHub.
```
git remote add origin REMOTE-URL
```
- For more information, see Managing remote repositories.
- To verify that you set the remote URL correctly, run the following command.
```
git remote -v
```
- To push the changes in your local repository to GitHub, run the following command.
```
git push origin main
```
- If your default branch is not named "main," replace "main" with the name of your default branch eg master

**Git Tagging**:


    > git tag -a v1.0.0 -m "Stable version with angular version 8.2" (Create tag with version name and commented)
    > git tag (Create tag)
    > git push origin --tags (to Push all tag to remote)
    > git push origin <tag name> (to push all tags by name)
    
**Git Branching**:
    
     > git init (To initialize git repo)
     > git ls-remote origin (When remote branch not visible)
     > git branch  (To check branch on local)
     > git branch -r  (To check remote branches)
     > git branch -a (To  check all local branches )
     > git checkout -b ＜new-branch＞ (To create and switch branch )
     > git push origin ＜new-branch＞  (To Push branch to  remote )
     > git checkout -b Dev origin/Dev (create new branch on local from existing branch on remote)
     > git checkout -b ＜new-branch＞ ＜existing-branch＞(create new branch from existing )
     

**Cherry picking**:

    > git cherry-pick ＜commit1＞ ＜commit2＞ 
