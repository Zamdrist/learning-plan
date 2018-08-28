# Git Flow

## My flow of work into Github

### This describes how I create initial projects, add them to Git and Github, and how I perform work

1. Create a new repository on Github here: [https://github.com/new](https://github.com/new)
    1. Blank Description (Optional)
    2. Public
    3. No .gitignore
    4. No Readme
    5. No License

    ![git-new-repo](/src/github-new-repo.png)

2. Copy https path to clipboard for use later.

    ![https-copy](/src/https-copy.png)

3. Open git-bash locally and create a folder for the project under your Development folder.
    1. mkdir my-repo
    2. git init
    3. Add a .gitignore [https://www.gitignore.io/](https://www.gitignore.io/) and a README file.
    4. git add .
    5. git commit -m "Initial commit"
    6. git remote add origin [https://github.com/Zamdrist/new-repo.git](https://github.com/Zamdrist/new-repo.git). This is the url you copied from step 2.
    7. git push origin master

        ![git-local](/src/git-local.png)