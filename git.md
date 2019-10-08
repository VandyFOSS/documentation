1. Check if git is installed by running `git --version` at command line. If not installed download it [here](https://git-scm.com/downloads).

1. Find an issue

1. Fork the project on GitHub.

1. Make a folder on your computer where you want to store the source code:
```
cd /path/to/parent/folder
mkdir $src_dir
cd $src_dir
```

5. Clone. You can find the URL by going to the repo on GitHub and clicking "Clone or download"
```
git clone https://github.com/$user/$repo.git
```

6. Branch:
```
git checkout -b fix-1234
```

7. Make changes to fix the issue, stage (add) all files changed, and commit:
```
git add file1 file2
git commit -m "describe changes"
```

8. Push:
```
git push origin fix-1234
```

9. Open a Pull Request on Github.
