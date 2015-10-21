# GitHub Tutorial

_by Maria Nieves_

---
## Git vs. GitHub
* What is Git ?
  * Git does not require GitHub 
  * Git "snapshots" your code (keeps track of changes made to your code)
* What is GitHub ?
 * GitHub requires Git. No Git, no GitHub!!
 * GitHub stores your code in a cloud 
 * GitHub is a visually tracks your changes
* What is the difference between Git and GitHub?
 * the difference betweeh git and github is Github needs Git in order to function
 * Git is responsible for keeping track of changes to content and can be shared with others and GitHub is a company that provides Git repository hosting.


---
## One Time Setup

Sign into [Cloud 9](http://www.c9.io) ...
  
 *  click on left right corner "Cloud 9"
 *  click on "Go To Your Dashboard"
 *  click on the gear icon 
 *  (on the left side bar) click on "SSH KEYS"
 *  copy the Default SSH key (command c) 
   
 
Go to [GitHub.com](http://www.github.com) 

  * sign up!
  
 Github account ...
 *  click on top right corner (profile )
 *  click on settings
 *  Under "Personal Settings" click on "SSH Keys"
 *  click on "Add SSH Key" 
 *  type your title of your project
 *  The "Key" box , paste your "SSH key" 
 *  press "Add key"

 





---
## Repository Setup

 * Setup in GitHub
1. In the top-right corner click the plus sign and click on **New Repository**  
2. Create a short repository name    
3. adding a description is optional
4. choose **public** repository
5. Select "**Initialize this repository with a README.md** 
6. Click **Create Repository**  
7. copy where it says "git remote add origin git @github.com:(...)"
8. paste this code in your cloud 9
9. type " yes "
10. copy where it says "git push -u origin master" 
11. paste this code in your cloud 9 

 
* In cloud 9 .....


 1. mkdir github-learning
 2. cd gitub-learning 
 3. mkdir "file name"
 4. cd "file name"
 5. pwd
 6. type git init
 7. PRESS ENTER 
 8. type " git config --global user.name "First Name, Last Name" "
 9. PRESS ENTER
 10. type " git config --global user.email "username@hstat.org"
 11. PRESS ENTER
 12. type " touch README.md " (capital letters, case sensitive)
 13. you may add code to the README.md
 14. type "git commit -m "(type a message here)" 
 15. type "git push "

 


  

---
## Workflow & Commands
* Workflow ~
   * In order to be able to add files in your directory.. type:    
  1. "cd (directory's name)" (this command gets you inside of the repository)
  2. "pwd" (this command shows you where you're at)
  3. "mkdir (files name)" (makes a new file)
  4. "cd (file's name) " (this command gets you into the new file/ file)
  5. make a "README.md" file --- touch "README.md" 
  6. open the README.md file
  7. you can write a messages here 
  8. git status 
  9. type "git commit -m "message" " (it records your snapshots into your history) 
  10. "git push "
   
 **Always remember to SAVE, ADD , COMMIT and PUSH**
  
  
 * Now _if you want_ to delete the README.md file...
   9. "pwd" (make sure you're at workspace)
   10. "ls" (this command lets you see the list of files that are in the repository)
   11. "rm -rf README" (this command deletes the README.md file) 
  



----

# Fork & Clonning 
1. search up on "GitHub Search" (example: games)
2. click on the game you are interested 
3. right side of the page, click on "Fork"
4. copy SSH clone URL
5. go to your cloud 9 account
6. make sure you are on workspace
7. type "git **clone** (url goes here)"
8. 
