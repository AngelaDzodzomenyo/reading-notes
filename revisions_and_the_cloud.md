# VERSION CONTROL
  * This acts a a time machine that drops various breadcrumbs or time capsles that you can travel to a revisit at any moment to make changes to your work. 
  
  * This allows for things like mistakes to be corrected, notes to be compared with a team 
------------------------------------------------------------------------------------------------------------------------------------------------  
  ## Different Types of Version Control 
  
   |**Local Version Control | Centralized Version Control | Distributed Version Control |
   |  --------------------- | :--------------------------:| :-------------------------: |
   | 1 database             |             X                |              X
   | hard disk              |  single server               |              X
   | stores chages to file  |  stores all changes and files to server     | mirrored repositories
   |                        |  multiple access points     | forward and backward flow 
   |                        |                             | collaborative workflow

--------------------------------------------------------------------------------------------------------------------------------------------------

## WHAT IS GIT?
  
  **Definitions**
  >Snapshots - data saved in a filing system of *snapshots* of work when changes are saved(commit)
  >
  >Local Operations - works using local resources so time isn't wasted on retriving info from external server and work can be done offline
  >
  >Tracking Changes - every single change applied is tracked so easier to track down corruption or mistakes
  >
  >Loss of Data - virtually impossible since at any moment you can retrieve earlier work free of damage or loss
  >
  >States - There are 3 main states: Committed, Staged, Modified

--------------------------------------------------------------------------------------------------------------------------------------------------

## Some Git Configurations, Customizations and Settings You Should Know

**Identify Settings** :
  >git config --global user.name "Jane Smith.    git config --global user.email "example@email.com"

  Result: To confirm that you have the correct settings, enter the following command:
    > git config --global user.name (should return Jane Smith) git config --global user.email (should return example@email.com)

**Default Text Editor**
  >$ git config --global core.editor emacs

**Check Settings**
  >git config --list command

**Getting Help**
  >git help command

  >git command --help

  >man git-command

-----------------------------------------------------------------------------------------------------------------------------------------------


## Setting up a Git Repository

**Importing**
  1. $ cd test (cd = change directory)
  2. $ git init
  3. 
      * $ git add *.c
      * $ git add LICENSE
      * $ git commit -m “any message here”
      
**Cloning**
  * $ git clone https://github.com/test
  > To clone a repository into a directory with another name of your choosing, use the following command format:

    * $ git clone https://github.com/test mydirectory
