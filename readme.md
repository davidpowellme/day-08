#Pragmatic Guide to Git - Travis
###Creation
- built in help for git
    + git help
    + open http://j.mp/gitdocs
- Configuration
    + username git config --global user.name
    + email git config --global user.email
    + Git is 100% a command line application
    + color git config --global color.ui auto
- Repository
    + A place that you keep all your stuff
    + tracks all the changes you made
- Commit
    + allows you to access history of files without constantly renaming
    + Commits make up repo
- Working Trees - you tree structure of files
- Clone - clone an existing repo to get a working tree of files

###Daily Work
- Tracking changes
    + git status
    + git add
    + git commit
    + git push
- Staging changes
    + staging area (index)
    + staging area is what you've worked on between commits
- Your should make commits in increments of changes
    + you can use index to break up your commits into those increments
- Remove a staged change
    + git reset HEAD README.rst
    + reset to last version in repo
- git mv README.rst like mv command
- git rm for remove
- send changes
    + use the github instructions
    + git push remote branch

###What is a branch?
- a branch just points to a git location
- branches give you the ability to do many things at once
    + one experiment while working on another
    + a/b testing while in iteration
- git branch
    + shows the current branch with "*"
    + shows all "ls" style
- **creating branches**: git branch new branch (name can be changed, not a command)
- **switching branches**: git checkout
- **merge branches**: checkout branch you want to merge into
    + git merge branchname

At this point, I stopped listening. Git is super useful, Travis knows A LOT about it.

I just don't really care that much today.

##Notes from Today
- Helpful link for grid layouts: [SitePoint Article](http://www.sitepoint.com/understanding-css-grid-systems/)
- Helpful link on typefaces: [A List Apart](http://alistapart.com/article/on-web-typography)