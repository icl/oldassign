To upload your first assignment you will need to do the following:

1. Sign up for a [free Github account](https://github.com/signup/free). Git is a version control system that you will use to submit your assignments.  

2. Set up Git on your computer http://help.github.com/set-up-git-redirect

3. Go to Github at https://github.com/icl/COGS187A_Portfolio You will find there a bunch of directories you can add to, such as images, stylesheets.  You can also just edit the index file - yes it is exclusively yours - but that is probably a bad idea since the editor us lousy. 

4. Before you can actually take ownership of this directory exclusively you need to have github know where your files come from.  This is called forking because Github creates a new path with your identity, separating your files from others.  If you are part of a team it will keep track of your team's files and who made what changes.  To cause Github keep a copy of your files that you can periodically write to (thereby updating the latest files but also keeping a record of previous files) you have to hit the FORK button on the Github page for this assignment (ie https://github.com/icl/COGS187A_Portfolio).  The FORK button is at the top along with WATCH ...  Click it and you will now create a directory with your name and a subdirectory for this assignment.  You can see that in the url.  




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
