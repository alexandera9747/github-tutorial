# GitHub Tutorial

_by Alexander Andria_

---
## Git vs. GitHub
**_What is Github?_** 
  * Github is a software that requires git in order to work. It gives programmers the abilty to collaborate on projects. It is also used to keep track of what you do, such as changes you make or code that you have added.   
**_What is Git?_**
  * Git is a program that runs in the command line. It is used to push projects to Github. It can also create snapshots also known as screenshots to keep track of your changes in your project.   

---
## Initial Setup
**_How do you Sign into Github?_**
* Firstly, you would need to create an account, including a username and password that you will remember. 
* Next, you would need to sign into your ide, by signing into your ide you now have the ability to make changes in files, create the, and more.   
  * When setting up your ide, you want to create an SSH key. Steps to doing this are liked here: https://github.com/hstatsep/ide50   
* We need the SSH key because it makes your account a remote, it also gives the programmer the ability to make changes to files and push them to their github repositories. Most importantly, it gives programmers the ability to collaborate on projects. 

---
## Repository Setup
* In your repository setup, there are many steps included in it too succesfully upload your changes. 
1. Firstly, you need to go into your certain repository or folder in order to start your setup. Once you are in your folder you type `git init` this basically activates git in your command line also know as hiring the photographer. 
2. Secondly, when you make changes to your file you would need to add those changes to the staging are and in order to do that you `git add .` this basically puts your changes into the frame or the stage and they are ready to be commited.
   * Tip: during this process `git status` is your best friend. It can tell you whether theres an error in code or in this case if your changes are added to the stage or not. If the change shows up in red it needs to be added if it shows up in green it is added and ready to be commited.
3. Thirdly, you would need to create a snapshot and create a record of that change. In order to do so, you need to type `git commit -m "custon message"`. When typing your commit message it ALWAYS has to be in present tense.
   * EX: `git commit -m "created changes to hotdog.txt` this is a bad commit message.
   * EX 2: `git commit -m "create changes to hotdog.txt` this is a good commit message.



---
## Workflow & Commands



---
## Rolling Back Changes