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







