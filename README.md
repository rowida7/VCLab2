git config --global user.name "Rowida"
git config --global user.email "rowidaabdelfatah@gmail.com"
git init
git add .
git commit -m "index&ReadMe Added"
git remote add origin git@github.com:rowida7/VCLab2.git
git push origin master

git checkout -b dev
git add .
git commit -m "added dev to devBranch"
git push origin dev

git checkout -b test
git add .
git commit -m "added test to testBranch"
git commit origin test 

**how to remove them locally and remotely**
git branch -d branchName --> delete locally
git push origin : branchName --> delete remotely

**how to checkout another branch without commit changes**
git stash
git checkout branchName
 
 **Create an annotated tag with tagname (v1.7) & push it in remote repository.**

git tag -a v1.7 -m "version1.7"  
git push origin v1.7

**how to list tags.**
git tag

**how to delete tag locally and remotely.**
git tag -d tagName --> locally
git push origin : tagNam --> remotly

** Add Image




![Image](/dazai.jpeg)




