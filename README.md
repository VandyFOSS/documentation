# Using git

# Contributing to Kubernetes
* Sign the CLA: https://github.com/kubernetes/community/blob/master/CLA.md
* Install go
* Find an issue
* Follow this workflow, except fork from VandyFOSS/kubernetes: https://github.com/kubernetes/community/blob/master/contributors/guide/github-workflow.md

'''
export GOPATH=/home/matthew/go
export PATH=$PATH:$GOPATH/bin
working_dir=$GOPATH/src/k8s.io
mkdir -p $working_dir
cd $working_dir
git clone https://github.com/VandyFOSS/kubernetes
cd $working_dir/kubernetes
git remote add upstream https://github.com/kubernetes/kubernetes.git
git remote set-url --push upstream no_push
git remote -v
cd $working_dir/kubernetes
git fetch upstream
git checkout master
git rebase upstream/master
git checkout testfix

./hack/update-gofmt.sh
./hack/update-bazel.sh

git commit
git push origin testfix
'''
