# git-demo 

1>from visuals studio code pushing all the work to github-  git push origin main
2>for knowing the status of work and changes done in a work we can see it by-  git status
3>let take example if i am doing a work on index.html and putting a paragraph so the changes can be added by using-  git commit -m "Add new paragraph"
4>example let we make new file name index.html so to add that file we have to use- git add index.html

5>for making a new folder we can do it by certain fastermethod and go to its new folder path -step1:cd..  , step2:mkdir ramboo , step3: cd .\Ramboo\   (new folder ka name hai ramboo)
6>forinitialising anything we use- git init
7>if we make new file like index.html,style.css  so at first the git status will show it as untracked files,but after using function- (git add .) we can see these files are added


8>local git workflow is: githubrepo->clone->changes->add->commit->push

9>learn these formulas for futher help in git:
   git branch (to check branch)
   git branch -M main (To rename branch)
   git checkout <branch name> (navigate)
   git checkout -b <new branch name> (to create new branch)
   git branch -d <branch name> (to delete branch)


10>undoing changes
 case 1: staged changes (add)
        git reset <file name>
        git reset
 case 2:commited changes(one comit change)
        git reset HEAD-1
 case 3:commited changes(for many comit)
         git reset <comit hash>
         git reset --hard <-commit hash->
