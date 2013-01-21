Game
====

Hello Team Team!

So, you've forked this, and now what? Well, heres the low down.

The first thing you need to do is get the git-gui. You probably downloaded it when you made the account. 
Add this repo to it, then clone it to your machine. When you clone it, all the data on the site will come to your computer.

Make the unity directory that you work in the same as this one. git is set to ignore temp/ and library/ because those
are not commitable. Unity will make it for you.

Work in the branch with your name on it. Anything you add to the game will be relfected in your local branch. When
you want to push it to the "master" branch, simply do a commit. It'll ask for a commit message, then it'll commit.

Press the sync button. Once it's committed, go to the github website. Press "pull request" on your branch. I'll add it 
on to the master, and then everyone else has to rebase their own branches.

The easy way to do this is to select your branch, press the tools, press open shell here and type:

git rebase master

It'll update your brach, then you sync it and your branch will be the same as the master.

Why are we using this? Well, say Alice draws some stuff. She imports it into unity, does a commit, I merge it, rebase,
and boom, I can freely use those drawings. 

Say I fix a bug that had been fucking up some puzzle Anthony was trying to make. I commit the change, he can download it 
instantly and viola.

Version control means we can all work on our own thing and review eachothers work, and if something ROALLY fucks up, 
it only fucks up LOCALLY. 

I'll show you guys how to do it irl if this isnt working for you.
