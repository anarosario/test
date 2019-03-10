#git tutorial
=======================
* Initiate repository:

    echo "# test" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git remote add origin https://github.com/anarosario/test.git
    git push -u origin master


* Create a new branch:
  git branch <newbranch>
  git checkout <newbranch>


* Commit to the newbranch:
  git push --set-upstream origin newbranch	

* Checkout master branch:
  git checkout master
  
* Check in which branch you are and modified files:
  git status

* Check differences wrt. comitted repository:
  git diff

* Push an existing repository from the command line:
  git remote add origin https://github.com/anarosario/test.git
  git push -u origin master # -u == --set-upstream


* Git push options: https://git-scm.com/docs/git-push