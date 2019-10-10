Run any commands in Terminal (Mac or Linux) or git-bash (Windows). Make sure to replace anything in braces.

1. Check if git is installed by running `git --version` in Terminal or look for git-bash on Windows. If not installed download it at [git-scm.com/downloads]( https://git-scm.com/downloads).

2. Find an issue
    - https://github.com/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+label%3Ahacktoberfest+
    - https://github.com/mungell/awesome-for-beginners

3. Fork the project on GitHub.

4. Make a folder on your computer where you want to store the source code. For example if you want a folder src in your user's home directory, use `~/src` for PATH:
```
cd {PATH}
mkdir {src}
cd {
```

5. Clone. You can find the URL by going to the repo on GitHub and clicking "Clone or download", then insert the URL into the following command in your terminal window:
```
git clone {LINK YOU COPIED}
cd {REPO NAME}
```

6. Branch:
```
git checkout -b fix-1234    # 1234 or issue number
```

7. Make changes to fix the issue, stage (add) all files changed, and commit:
```
git add {FILES YOU CHANGED} # I.e. git add main.c otherfile.h
git commit -m "{DESCRIBE YOUR CHANGES HERE}"  # i.e. "Fix double click issue in debug window"
```

8. Push:
```
git push origin fix-1234
```

9. Open a Pull Request on Github.
