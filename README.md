# testsite

[Good explanation of git:](https://stackoverflow.com/questions/2745076/what-are-the-differences-between-git-commit-and-git-push)

and the outstanding picture from there:

![git commands][MgaV9.png]

## Original content ##

### …or create a new repository on the command line ### 

echo "# x" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/patricos/x.git
git push -u origin master

###  …or push an existing repository from the command line ### 

git remote add origin https://github.com/patricos/x.git
git push -u origin master

### …or import code from another repository ### 

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
