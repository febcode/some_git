## **IMP Commands for GIT **

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
     

**Cherry picking **:

    > git cherry-pick ＜commit1＞ ＜commit2＞ 
