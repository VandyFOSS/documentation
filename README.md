# Using git

# Contributing to Kubernetes
* Sign the CLA: https://github.com/kubernetes/community/blob/master/CLA.md
* Install go
* Find an issue
* Follow this workflow, except fork from VandyFOSS/kubernetes: https://github.com/kubernetes/community/blob/master/contributors/guide/github-workflow.md

```
fork
go get -d github.com/mkenigs/kubernetes
git remote add upstream https://github.com/kubernetes/kubernetes.git
git remote set-url --push upstream no_push
git fetch upstream
git checkout master
git rebase upstream/master
git checkout -b pkg-api-testing

```
* Go to github.com/VandyFOSS/documentation
* Click fork in top right
* Select your username
* Should redirect you to the new fork. If not, go to github.com/username then click documentation
* Go to the file you want to change. Press the pencil. Make a change. Select create a new branch.
* Click compare across fork. You should have:
base fork: VandyFOSS/documentation
base: master
head fork: username/documentation
compare: patchname

* Click create pull request
* Write a message
* Click create pull request
