git –version //This command to check the version 
 mkdir foldername eg: mkdir demo 
 cd demo  
 git init 
 git status 
 git add demo.txt 
 git commit -m “commiting text file” 
 git config user.name “ ”  
 git config user.email “ ” 
 git config --global user.name “ ” //To link with git hub account ,git hub username & password 
 git config –global user.email “ ” 
git branch feature-branch 
 git checkout feature-branch
git checkout master 
git merge feature-branch
git status //it will check the status 
git push origin master
git branch feature-branch2 
git status 
vi sample.txt 
git add sample.txt 
git checkout feature-branch2 
git log –oneline  
git stash 
git stash list 
git stash apply
git clone <repository-url>
git fetch origin 
git checkout feature-branch 
git rebase master/origin feature-branch 
git add <resolved-file>  
git rebase –continue 
git push -f origin feature-branch
git checkout master
git merge feature-branch
git commit –m “custom commit message”
git checkout master 
git tag v1.0 
git tag //it will show v1.0 
git tag –a v1.1 -m “tag for release ver 1.1” 
git show v1.0 
git tag –l “v1.*” 
git push origin v1.0 //push tags to origin
mkdir Git cherry picking 
cd Git cherry picking 
git init 
vi alpha.txt 
git add . | git commit –m “1st commit” 
vi beta.txt 
git add . | git commit –m “2st commit” 
vi gamma.txt 
git add . | git commit –m “3st commit” 
git reflog //It shows all commit history 
git add . 
git status 
git commit –m “all deleted” 
git reflog 
git cherry-pick id //----add commit history id eg:34946d4------ 
git log // it show all commit history with commit id
git log // it show all commit history with commit id 
git show commitId /
git log --author="shamsiya parveen " --after="2023-01-01" --before="2023-12-31" 
git log -n 5
Git revert “abc123” 
Git log –oneline // it shows commit history in oneline 
Git reset –hard head.1
