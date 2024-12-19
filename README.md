git init 
git -branch main master
 git add * 
git commit -m "bundle1" 
git remote add origin https://github.com/ruzibizak/Git_Thegym.git 
git branch dev 
git checkout dev 
git branch test 
git branch -d test 
git add home.html 
git stash save "added home.html" 
git add about.html 
git stash save "added about.html" 
git add team.html 
git stash save "added team.html" 
git stash pop stash@{1} 
git commit -m "stach" 
git push -u dev git reset
