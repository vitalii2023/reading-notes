# Pair Programming - Creat a fork / pull request / Merge.

These are notes to remind me how to create a fork to duplicate someone elses project / repository.  
From this I can clone it to my local machine and open it in VScode.  
I can then make changes to the project. Important to note at this stage I am just changing the copy of the project I put on my github and my local machine.  
I can then git add . , git commit - m "message", git push the changes to git hub.  
This is so the copy I have created now has the updates I have made saved.  
From this I can create a pull request.  
Now once the pull request is done, the person who ownes the original project can review the changes I made and merge the changes I made to the origional project.  
If this was a live website the live website would be updated so the users of the websites would see the most upto date version with the changes I made.  


## Work Flow. 

##### Person 1. 
Log into git hub and navigates to the project we want person 2 to update.  
If person 1 has been working on the repository make sure to have it upto date using ACP.  
Once in the repository on github person 1 can copy the url from the browser and send this to person 2.  

##### Person 2. 
Person 2 can now click the url person 1 sent to get to the project.  
On github go to fork and create a new fork. 
Change the name of the Repository to be simalar to the origional. Example we changed about-me to about-me-chris.  
Click create fork. 
Now person 2 has a fork (copy) of person 1's repository.  
Click the code button (big green button) on the repositiory (about-me-chris) and copy the https link.  
In the terminal navigate to where you want to store the project:  
Example: user/vitali/projects/coursers/102-code. 
Enter command git clone <and paste the link you copied> Example: git clone https://github.com/vitalii2023/about-me-chris.git. 
Next in the terminal change directory to the repository you just cloned:  
Example: cd about-me-chris. 
Then open the project in the terminal using command code .  
Now you can make changes to the project. In the example we just went through we made a change to the index.html file by deleting a word in a paragraph.  
Once we have made the change we need to update the project using ACP:  
  
git status
  
git add .
  
git status
  
git commit -m "removed surname from paragraph in index.html"
  
git status
  
git push

In git hub you should be able to see the updated with the commit message.  
on git hub click pull requests. 
Click new pull request. 
Click create pull request. 

##### Person 1. 
Go to github and go to the repository (in this example the about-me repository).  
Go to pull requests and click on the request.  
Click merge pull request.  
Click confirm merge.  

In the terminal navigate to the project. Example: user/chris cd into projects then cd into about-me. 
Now you are in the project directory on the terminal enter command git pull. 














