Hey guys, sorry for getting this out so late. This is our work environment. I have set it up so that we will each create our own branches to work in prior to merging with the `testing` branch and into the `master` branch. Please do not commit anything to the `master` branch before we determine that there are no bugs in `testing`. 

Please do **NOT** push anything to eachother's personal repos. Feel free to pull.

We are going to be using what is called [GitFlow](https://datasift.github.io/gitflow/IntroducingGitFlow.html) to help with organized development.

You should all be able to individually sign up for a student GitHub account at: https://education.github.com/pack This allows you to use some cool stuff and free private repositories (repos). 

If you decide to use GitHub from a CLI, like me, here are some good websites for setting things up. [Great Guide](https://www.atlassian.com/git/tutorials/setting-up-a-repository) and [Another Guide](https://www.linux.com/learn/beginning-git-and-github-linux-users)

Basically you setup by making a directory, initializing the repo, and cloning the repo into the directory. 

To do this make a directory:		`mkdir <directory>`
	initialize the repo:			`git init`
	clone the repo:					`git clone <url found on 'green clone' button on the github page>`

##		Credentials     

1. To set a global username:		`git config --global user.name <name>`
	- ex: Has a local flag (--local)
2. To configure a global email:	`git config --global user.email <email>`
	- ex: Has a local flag (--local)
3. To cache your login credentials for say 15 mins:	`git config --global cridential.helper `cache --timeout=7200``
	- ex: Has a local flag (--local)

##		Aliases      

1. To set a command alias: `git config --global alias.<alias-name> <git-command>`
	- ex: Has a local flag (--local)
	- ex: create an alias for `git commit`:	`git config --global alias.ci commit`
	- ex: create an alias for `git pull`:		`git config --global alias.pu pull`

##		Branches      

1. To see what branch you are in:		`git status`
2. To create a new branch:				`git checkout -b <branch>`
3. To change between branches:			`git checkout <branch>`

##		Push, Pulling, and Committing Files    

1. To add a file to your LOCAL repo:								`git add <file>`
2. To add every file (in current dir) to your LOCAL repo:			`git add .`
3. To commit a file to preapre for pushing:			`git commit <file>`
	- ex `git commit -m <file>`
4. To add every file (in current dir) & commit them:	`git commit -am "<commit message>"`

5. To undo commits: `git checkout -- <file>`

6. To push your (commits) to your branch github repo:	`git push <repo>`
	- ex:`git push <testing>` 

7. To push commits to a certain branch:				`git push <local repo> <branch>`
	- ex: `git push mazegame testing`
8. To pull the upstream changes into your local repo:	`git pull <remote> <branch>`
	- ex for me it is `git pull mazegame <branch>`
9. To rebase (similiar to pull):						`git pull --rebase <remote>`

10. Pull vs Rebase: [Great Explaniation](https://www.derekgourlay.com/blog/git-when-to-merge-vs-when-to-rebase/)

11. Remove file from git:	`git rm <file>`
12. Tip
	- git only takes the changes that you commit when you do a push



If you need to get ahold of me you can reach me, Emily (Bryson), at 650-336-8024, or at my NAU email: bso26@nau.edu. I prefer to go by 'Emily' when not in class. I look forward to working with you guys. I feel like our team can work well together.
