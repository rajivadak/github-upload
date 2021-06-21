We can create a global repository to our projects in github.
# Pre-requisite
* git should be installed in our machine and global configuration should be done to it.
* Should have github account
# Downloading

[Download Link](https://git-scm.com/downloads)

# Verify

To check whether git is installed properly or not use command prompt and type "git". If you can see all the available commands in it then installation is done properly.

# Global Configuration

```$git config --global user.name "<username>"```

Example: git config --global user.name "Sirishakrishna"

```$git config --global user.email <email-id>```

Example: git config --global user.email sirisha.velampalli@gmail.com

# Navigate
Navigate to the location where your project to be uploaded to github repository is located.

Then run the following commands
```git init```  \\Creates an empty repository
```git add .``` \\ Make all the files available for next commit
```git commit -m "<message>" ```
# Uploading Project on Github
Login to github account
```https://github.com/new```
Give the name of the repository. After you logic you can see sample lines as below:
```
echo "# basic-java-programs" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/Sirishakrishna/basic-java-programs.git
git push -u origin master
```

Run the command 
```git remote add origin https://github.com/Sirishakrishna/basic-java-programs.git```
available in sample.
Above command link local machine project to git repository.
Run ```git push -u origin master``` which also also available in sample
Above command pushes project from local machine to git.

Finally you can see project in the github repository.

#Check status
```git status```
By using above command we can see any changes done to our project
# Commit details
```git log```
#  Creating Branch
The following commands need to be run in order to create branch.

```
git checkout -b "<message>"
git branch: To check whether branch is created or not
git add .
git commit -m "<message"
git push origin "<message>"
```






