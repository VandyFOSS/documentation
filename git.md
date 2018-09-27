'''
user=mkenigs
src_dir=/home/matthew/src
repo=documentation
owner=VandyFOSS
mkdir $src_dir
cd $src_dir
git clone https://github.com/$user/$repo
cd documentation
git remote add upstream https://github.com/$owner/$repo.git
git fetch upstream
git checkout master
git rebase upstream/master
git checkout -b mybranch
//make changes
git add sandbox.md
git commit
git push origin mybranch
'''
