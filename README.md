# GitHub_CMD By TECHAUNG

# Install Git on ubuntu 
$sudo apt install git 

# Check version 
$git –version 

# Initialize Git ( cd to File Folder that you want to push first )
$git init  

# Check Git Status 
$git status

# Add File to Upload
$git add .

# Check Git Status Again
$git status

# Add Github Username & Emails
$git config --global user.email "binarytechteam@gmail.com"
$git config --global user.name "techaung7"

# Check Github Username & Emails
$git config user.email
$git config user.name

# Add Remote Repositories on Git 
$git remote add origin https://github.com/techaung7/Tahleeweb.git

# Check Remote URL
$git remote -v

# Remove Remote URL 
$git remote remove origin

# Git Commit 
$git commit -m "My First Push"

# Upload To Git
$git push -u origin master

# Uninstall git
$ sudo apt-get remove git

# Uninstall git and it's dependent packages
To remove the git package and any other dependant package which are no longer needed from Ubuntu Trusty.
$ sudo apt-get remove --auto-remove git

# Purging git
If you also want to delete configuration and/or data files of git from Ubuntu Trusty then this will work:
$ sudo apt-get purge git

# To delete configuration and/or data files of git and it's dependencies from Ubuntu Trusty then execute:
$ sudo apt-get purge --auto-remove git
