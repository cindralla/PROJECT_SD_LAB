# PROJECT-SD-LAB
## Project Report

Firstly I started understanding github through the github desktop platform which was my IDE for git.And also creating a **public repository**.In my project repository named as _PROJECT-SD-LAB_.This repository was created for performing the **system design lab** project using git.I started my project using _terminal and commands_ to access github and my repository.The following steps are follows:

**1. Installing git**

I need to install Git on my system first.I didn't face any issue while installing git.

**2. Initialize**

In this step,first i create a folder in linux.I named that folder as _project_.After creating the folder,I'm goes to redirecting the prompt to newly created folder _project_ and also using the command **git init**.Using this command my repository was initialized in corresponding folder.I didn't face any issue in this step.

**3. Create a git repository named project in github via IDE**


After creating git repository,invite my teams as collaborators.

**4. Setting the git configurations in terminal**

```
git config --global user.name Rehna.
git config --global user.email rehnam2014123@gmail.com.
git config --global core.edit gedit.
```
Using the above commands I successfully set to git configurations.

**5. Adding a file in my git initialized folder to staging area**

Using the **git add** command I'm successfully adding the file to staging area.I'm adding a file named as fx.Then i follows the syntax to add a file that is,**git add fx.txt**.After adding a file,we can see both tracked and untracked files  using the command **git status**.

**6. Commit**

Successfully commit the added file using the command **git commit -m "type any message"**.

**7. Cloning the github repository**

Using the **git clone https://github.com/PROJECT-SD-LAB/project.git** command successfully clone the entire github repository.

**8. Pushing my commited file to my github repository**

To perform this step,before we pull the file and then push.The following command are used.

```
git pull https://github.com/PROJECT-SD-LAB/project.git
git push https://github.com/PROJECT-SD-LAB/project.git master
```
**9. Creating a new branch and their operations**

Use the following commands is to perform a branch.

```
git checkout -b rehna
git branch
git pull https://github.com/PROJECT-SD-LAB/project.git
git push https://github.com/PROJECT-SD-LAB/project.git rehna
```
In the above case,is to create a new branch name as rehna.Then to pull the changes and finally is to push the commited file to new branch.

**10. Merging the branch to master branch**

To merge the branch to our master branch,use following commands.

```
git checkout master
git merge rehna
git pull https://github.com/PROJECT-SD-LAB/project.git
git push https://github.com/PROJECT-SD-LAB/project.git master
```

These are the major steps to perform this project.During the pushing step i felt a difficulty.I doesn't access a username and password during pushing.Then I'm changed to use another system.And to again perform first step to final stage.Then more time was needed.And also difficult to finding the commands.After facing many problems,the project eventually became complete.


