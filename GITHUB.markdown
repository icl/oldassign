To upload your first assignment you will need to do the following:

1. Sign up for a [free Github account](https://github.com/signup/free). Git is a version control system that you will use to submit your assignments.  

2. Set up Git on your computer http://help.github.com/set-up-git-redirect

3. Fork the assignment at https://github.com/icl/COGS187A_Portfolio which is a repository containing files that will be the starting point for you first assignment.



First make a Fork of the repository by clicking the "Fork" button in the top right hand corner. This will make your very own copy of the git repository that you can work on. The page in github will look largely the same, but note that it now will say yourname/COGS187A\_Portfolio in the top left corner, and forked from "icl/COGS187A\_Portfolio"

Now open up a Terminal, or the Git-Bash shell if you are using windows.

Enter the following, replacing "[your username here]" with your github account name:

Please note we will use $ as a marker to show what you should enter in the command line. You should not enter the $. Any lines without the $ should be read as expected output

```bash
$ git clone git@github.com:[your username here]/COGS187A_Portfolio.git
```
This will create a folder on your computer called "COGS187A\_Portfolio" with the project files in it.

now go to that directory in terminal

```bash
$ cd COGS187A_Portfolio
```

####FIX
Take a while to look over the files there. README.markdown and GITHUB.markdown 
####FIX

In terminal, type `git status`
if everything up to this point has worked you should see:

```bash
$ git status
# On branch master
nothing to commit (working directory clean)
```
