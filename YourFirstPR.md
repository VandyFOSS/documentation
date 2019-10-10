Run any commands in Terminal (Mac or Linux) or git-bash (Windows). Make sure to replace anything in braces.

1. Check if git is installed by running `git --version` in Terminal or look for git-bash on Windows. If not installed download it at [git-scm.com/downloads]( https://git-scm.com/downloads).

2. Find an issue:
    - Go to the issues tab of a project you think sounds interesting! Most repos have a label like good-first-issue.
    - Good list of projects you can filter by language: [codetriage.com](https://codetriage.com)
    - All open issues with hacktoberfest on Github: https://github.com/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+label%3Ahacktoberfest+
    - Another good list of projects: https://github.com/mungell/awesome-for-beginners

3. Fork the project on GitHub:
![git](https://user-images.githubusercontent.com/40775676/66588842-ef87a280-eb52-11e9-85be-0570b7622119.png)

4. Make a folder on your computer where you want to store the source code. For example if you want a folder src in your user's home directory, use `~` for PATH and `src` for FOLDER:
```
cd {PATH}
mkdir {FOLDER}
cd {FOLDER}
```

5. Clone. You can find the URL by going to your repo on GitHub and clicking "Clone or download", then insert the URL into the following command. Make sure you go to the repo your user owns (eg mkenigs) rather than the upstream one (eg VandyFOSS):
![clone](https://user-images.githubusercontent.com/40775676/66590204-d7fde900-eb55-11e9-82af-a2802a9b474c.png)
```
git clone {LINK YOU COPIED}
cd {REPO NAME}
```

6. Branch. You can name your branch whatever you want, but it's common to call it fix-1234 where 1234 is the issue number on GitHub:
```
git checkout -b {BRANCH}
```

7. Make changes to fix the issue using any IDE or text editor, stage (add) all files changed, and commit:
```
git add {FILES YOU CHANGED} # i.e. git add main.c otherfile.h
git commit -m "{DESCRIBE YOUR CHANGES HERE}"  # i.e. "Fix double click issue in debug window"
```

8. Push:
```
git push origin {BRANCH}
```

9. Open a Pull Request on Github. In your PR description, make sure to say your PR closes issue #1234.
![PR](https://user-images.githubusercontent.com/40775676/66595527-bc4c1000-eb60-11e9-9c22-3544951ca059.png)
