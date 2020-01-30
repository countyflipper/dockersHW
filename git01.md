
#How to install Git

1.	You will need to create a GitHub account at https://github.com.
![GitHub Logo](/images/Image1.png)
2.	You will need to install a terminal on your desktop to run commands in order to push/pull files from your desktop to your repository that is online via GitHub. https://github.com/docker/toolbox/releases
3.	Let’s create a repository. A repository is another name for folder.
4.	Within your GitHub account online, click on Repositories and type in a name for your new repositories.
5.	See image for setup.
![GitHub Logo](/images/Image2.png)
6.	Once setup, click on the repository and click on “Clone or download” to get the HTTPS link.
7.	Go back to your DOCKER terminal and run the following commands.
8.	Type in pwd to find your location that you are working in
	1.	pwd
9.	If you would like to change your directory, type in 
a.	cd /c/..[Folder Name]../ 
10.	Take the HTTPS link and type in the following command and then the link.
#Branch
11.	Type in git status to see what branch you are in.
	1.	git status
12.	Once the top list has been completed we can now start to learn branching and other concepts.

Branch?
1.	Branch is a copy of your repository that will isolate your changes without touching the original one such as from the Master. A branch is similar to a file directory. It will represent a working area where you can edit, stage, and commit once you ready to make live. It’s a way so the programmer can work on one thing while not interfering with another programmer when coding.
2.	Pull request is when you want to submit all your revision to the main project branch.

#Merge Conflicaster while you are still in the feature branch. This is when the merge conflict occured.
	2.	git branch <Name> - creates a new branch called Name
	3.	git branch -d <Name> - delete branch
	4.	git -b checkout branch_name – is a shortcut to create a new branch and commit to another line
#Merge Conflict
	1.	Merge conflict happens when programmers both make changes to the same line within a file or when a programmer is modifying a file that anther programmer had deleted. For example, when make changes to a file that is on a branch such as Master while you make another change using the same file on another branch such as feature. Once the changes had been made within the feature branch and you then merge the master while you are still in the feature branch. This is when the merge conflict occurred. 
	2.	There are different ways to avoid merging conflicts. First you can use the git difftool in which allow developers compare both files at the same time, side by side. Another way to prevent any conflicts is using the git Rebase.
	3.	Forking is exact replica of the repository where it allows developers to freely experiment such as changing coding without ever touching the original project. Basically forking resembles as a bridge connection between the copy and back to the original repository while utilizing the Pull Request.
	4.	Pull request notifies other developers concerning on any changes that someone had made towards a branch within GitHub.
	5.	Cloning on the other hand only works with GitHub where its clone remotely and synced such as one on GitHub and the other repository on your personal desktop computer.

