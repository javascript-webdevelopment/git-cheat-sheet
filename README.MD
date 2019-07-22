# Git

Git is the version control tools that we can use in our command line to interact with our Github.

## Git Clone

First you need to copy the url for the github repo that you wish to clone down to your local machine then navigate to the directory that you want to clone the repo into. Once you are in the correct directory run:

```bash
git clone "url for github repo"
```

## Git Status

`git status` is the command you can run to check what stage of the process you are on to push your code to github.

run:
```bash
git status
```

## Git Add

`git add .` is the command you can run to start the process of pushing your code to github. `git add .` will stage all files that have any changes being tracked.

run:
```bash
git add .
```

## Git Commit

After staging your code using `git add .` we now need to commit our changes. This is the final step we will take before pushing our code to github. Think about commits as check points or save points in your code. You will need to provide a message about the commit using the `-m` flag.

run:
```bash
git commit -m 'message about your changes'
```

## Git Push

After staging and commiting your code, it is now ready to be pushed up to github. When your code is ready to be pushed, run:

```bash
git push origin master
```