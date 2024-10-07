If you would like to contribute to this Wiki there are a few ways to do so which will be covered here, but first an introduction to how it works.

# How it works

I am using 3 pieces of software:
- [Obsidian](https://obsidian.md/)
	- allows us to create a wiki style collection of notes that can be linked together
- [quartz](https://quartz.jzhao.xyz/)
	- takes that obsidian "vault" and converts it into HTML
- [git](https://en.wikipedia.org/wiki/Git)
	- allows for version control and the ability to collaborate 

And 1 service:
- [GitHub](https://github.com/)
	- a place to host the remote repository (so that we can collaborate with git) as well as host the HTML on the internet

# Getting started

## GitHub Desktop
GitHub Desktop is by no means the only way to use git it is the easiest in my experience.

### Installation
An installation guide can be found [here](https://docs.github.com/en/desktop/installing-and-authenticating-to-github-desktop/installing-github-desktop#downloading-and-installing-github-desktop)

### Sign In
Sign in to GitHub on GitHub Desktop when prompted (if you haven't already you will need to create an account)

Additionally send me your GitHub username so I can give you rights to edit without having to jump through a bunch of hoops.

### Clone Repository 
Cloning is just a fancy way of saying make a copy of everything in the repository (the source code for the wiki) that is linked to the repository on GitHub so that they can stay in sync. 

A guide can be found [here](https://docs.github.com/en/desktop/adding-and-cloning-repositories/cloning-a-repository-from-github-to-github-desktop)

The repository for this lore wiki can be found [here](https://github.com/nbgibbs/lorewiki) (this is what you want to clone)

## Obsidian
While the software is not strictly required to contribute as most of the files are [markdown](https://en.wikipedia.org/wiki/Markdown) files that can be edited with for example notepad.exe, none of the links will work without it and it will over all be a little harder.
### Installation
An installation guide can be found [here](https://help.obsidian.md/Getting+started/Download+and+install+Obsidian) though it is as easy and download and install same as anything else.

### Open folder as vault
Now as with the guide [here](https://help.obsidian.md/Getting+started/Create+a+vault#Open+existing+folder) you will open the folder named "content" inside of the folder you just cloned.


# Using Your Setup
You are all ready to go now and now I will show you how to use your setup. 

## Key concepts

- Commits
	- commits are like save files that record all changes that are made


## Lets Do It!
fetch any changes that on GitHub (this won't actually apply any changes that are found, just checks for them) If changes are found it will prompt you to "pull" them or apply those changes. 

Make changes to the content in Obsidian. GitHub Desktop will track all of the changes that are made.

![[Screenshot 2024-10-07 003300.png]]

When you are finished, you must commit the changes you have made by typing a summary of your changes in the box (not the best practice but half of the time I just put "update") the more info you put here the easier it is to keep track of everything, but don't sweat it. Click commit to v4 (v4 being the main branch we are using)

![[Screenshot 2024-10-07 010222.png]]

At this point the changes are tracked by git but they are still only on your local computer. You will need to "push" the changes to GitHub.

![[Screenshot 2024-10-07 010518.png]]