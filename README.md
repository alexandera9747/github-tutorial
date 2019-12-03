# GitHub Tutorial

_By Alexander Andria_

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
  * When setting up your ide, you want to create an SSH key. Steps to doing this are linked here: https://github.com/hstatsep/ide50
* We need the SSH key because it makes your account a remote, it also gives the programmer the ability to make changes to files and push them to their github repositories. Most importantly, it gives programmers the ability to collaborate on projects.

---
## Repository Setup
**In your repository setup, there are many steps included in it too succesfully upload your changes.**
1. Firstly, you need to go into your certain repository or folder in order to start your setup `cd <the folder>`. Once you are in your folder you type `git init` this basically activates git in your command line also know as hiring the photographer. In doing so you now have access to git commands such as `git status` `git add .` and `git commit -m "---"`.
   * Tip: If you `git init` in the wrong directory (folder) you can do `rm -rf .git` it basically takes away git or "fires" the photographer. 
2. Secondly, when you make changes to your file `c9 <file name>` you would need to add those changes to the staging are and in order to do that you `git add .` this basically puts your changes into the frame or the stage and they are ready to be commited.
   * Tip: during this process `git status` is your best friend. It can tell you whether theres an error in code or in this case if your changes are added to the stage or not. If the change shows up in red it needs to be added if it shows up in green it is added and ready to be commited.
3. Thirdly, you would need to create a snapshot and create a record of that change. In order to do so, you need to type `git commit -m "custon message"`. When typing your commit message it ALWAYS has to be in present tense.
   * EX: `git commit -m "created changes to hotdog.txt` this is a bad commit message.
   * EX 2: `git commit -m "create changes to hotdog.txt` this is a good commit message.

* When creating a new repository on Github you need to make sure the name of it matches the folder you want to push. Also, you need to make sure you use an SSH key.
* Your remote is like the home of your repository, all of the folders you make are in the remote. Everything in the local gets sent  up to the remote.

---
## Workflow & Commands
**There are four types of ongoing workflows & commands. They consist of**  
 1.`git status`  
 2.`git add`  
 3.`git commit`  
 4.`git push`  
* `Git  status` we use this too see errors in your code or whether a change or a file has been added, overall it tells you the current state of your code.  
* `Git add` We use git add to add our files to the staging area. This basically means that our file is ready to have a snapshot of it and saved.   
* `Git commit` we use this code to take the snapshot of our change made to the file or in other words a picture of what you done. It also has a message and as said the message has to be in present-tense saying what was modified. 
* `Git push` this is used to bascically push the commits from your local, which is your ide to the remote, your repository in github.

---
## Rolling Back Changes
**Say you accidently commited, made an edit, added, or pushed and you didn't want too. There are codes that can reverse it and undo the changes you didnt mean to do.**  
* There are codes that you can use to undo these changes.
  * To undo a commit you simply type in `git reset --soft HEAD~` this will undo your most recent commit. 
  * If you accidently make an edit and you want to take it back you can simply use `git checkout <file name>` this will undo the change.
  * If you want to unstage a file you type `git reset HEAD file` this will turn the file read again. 
  * If you didn't mean to push a file you need to revert that file by `git revert` and type in after `git reset --hard <file code name>` and after `git push origin +master` this will undo your push.

---
## Collaboration 
 We _Collaborate_ to work on each others projects, make our version of it, and ask to make changes. 
 * Some ways to collaborate include forking, cloning, and pulling.
 * Forking is basically making our own copy of someone elses repository and making it ours, we can push changes to pur version without having to do a pull request.
 * `cloning` is similar to forking but not entirly. For example, cloning if you wanted to push changes that you have made, you cant without making a pull request because you didnt make the repository yours. 
 * Pull requests are basically askings for a change in your repository, you can either accpet it or decline it, up to you.
 * `pulling` is accepting a pull request and pulling those changes to your repository.  