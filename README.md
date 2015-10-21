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
 *  click on top right corner (pink)
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
 
* In cloud 9 .....
 
 1. type git init
 2. PRESS ENTER 
 3. type " git config --global user.name "First Name, Last Name" "
 4. PRESS ENTER
 5. type " git config --global user.email "username@hstat.org"
 6. PRESS ENTER
 7. type " touch README.md " (capital letters, case sensitive)
 8. you may add code to the README.md
 9. type "git commit -m "(type a message here)" 
 10. 

 
 

 


  

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
  8. type "git commit -m "message" " (it records your snapshots into your history)   
  
 * Now if you want to delete the README.md file...
   9. "pwd" (make sure you're at workspace)
   10. "ls" (this command lets you see the list of files that are in the repository)
   11. "rm -rf README" (this command deletes the README.md file) 
  
 
 
