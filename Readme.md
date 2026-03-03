# Hands-On Git Commands Demo Repository 
This repository is a practical showcase of essential **Git & GitHub commands**. 
It demonstrates setup, configuration, branching, merging, staging, committing, undoing, resetting, pushing, pulling, and maintenance workflows. 
Perfect for learning, practicing, and demonstrating version control skills. 

## 🔧 Setup & Configuration
git --version 																			# Check installed Git version
git config --global user.name "Yuvaraj S"								# to set username
git config --global user.email "mail2yuvarajs@gmail.com" 	#to set useremail
git config --list																		# View all configuration settings

## 📂 Repository Management
git init 										# Initialize a new Git repository
git clone <remote url> 			# Clone an existing repository
git remote add origin <url>	# Link local repo to remote 
git remote -v 							# Show remote URLs

## 🌿 Branching & Merging
git branch                	 			# List branches
git branch <name>        			# Create a new branch
git checkout <name>				# Switch to a branch
git switch <name>          		# Modern way to switch branches
git merge <name>           		# Merge another branch into current
git branch -d <name>      	 	# Delete a branch

## ⏪ Undoing & Resetting
git reset <file> 						# Unstage a file 
git reset --hard 						# Reset working directory to last commit 
git revert <commit> 				# Create a new commit that undoes changes 
git checkout -- <file> 			# Discard changes in a file

## 📤 Pushing & Pulling
git push origin main 				# Push local commits to remote 
git pull origin main 					# Fetch + merge changes from remote
git fetch 									# Download changes without merging

##🧹 Cleaning & Maintenance
git log 										# Show commit history 
git diff 										# Show differences between commits 
git stash 									# Temporarily save changes without committing
git clean -f 								# Remove untracked files