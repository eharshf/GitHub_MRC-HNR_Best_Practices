GitHub_MRC-HNR_Best_Practices
=============================

Introduction to using Git for scientists
----------------------------------------

Git and GitHub are two different things. Git has a lot of functionality and is used as a version control system that is flexible enough to handle many people working on the same documents all at once. The basic unit of Git is the repository. It is a directory that contains the code, the history of all changes to code, and can contain different off-shoots from the main source code. The off-shoots from the main source code are called branches.

GitHub is a website that has been optimized to store, share, and merge collaborators Git repositories. For the most part our job as owners/admin is to do the merging and provide stable source code that anyone with access can hack away at without destroying the source code. At first you will want to simply know how to pull down the source code you want to run on your local machine. As you get more comfortable and start to make changes to your own copy you may think that some of the changes you have made could be included in the source code. Things like documentation, papers, and example data or figures are essential to good scientific source code! Throw them our way!

First we are going to use this repository itself to learn the basics about how to pull down the source repository and do some work with it. But first we need to set up Git on our local machine, the thing you are staring at right now.

On windows, go here: http://git-scm.com/ and download the latest version of git for your operating system. Use the installer to get everything up and running. On debian based linux you can just type the following in a terminal.

``` shell
sudo apt-get install git
```

On mac, you can get git by brew
``` shell
brew install git
```
