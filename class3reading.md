# All About GIT
### **Version Control**
> When a system records data down version-by-version in order to allow you to revisit prior versions and to revert back if necessary.

**CVCS Vs. DVCS**

> #### **CVCS:** is a Centralized version control system and it allows for multiple people to be able to access single files or groups of files together on a shared server system. 

> **DVCS:** the Distributed version control system is the similar to the CVCS in it's collabortation ability, but it is mirrored on multiple servers for redundancy on software. 

## _What is GIT?_
#### GIT is a distributed version control system that allows many features for software developers like:
> - _Snapshots_ : Snapshot of file is saved each time you commit and this gives us a snapshot to reference.
> - _Local Operations_ : Allowing us to work within our local hardware saving time from fetching data and allowing work without internet or VPN.
> - _Tracking Changes_ : All changes on GIT are tracked and we will be alerted if data is lost or corrupted in transit.
> - _More Secure Data_ : GIT's setup secures against loss of data and makes that scenario highly unlikely. 

## GIT States
#### Files in GIT are always in one of three states:

> 1. _Commited :_ Data of that file is stored (commited) to a database and information is secure. 
> 2. _Modified :_ Your file has been modified, but has not yet been securely stored to the database. 
> 3. _Staged  :_ When a changed file version is commited and ready for next snapshot.


## Using GIT: 

### **_Checking Settings_:** use `git config --list` command

### **_Getting Help_:** Three ways to get help include:
> 1. `git help COMMAND `
> 2. `git COMMAND --help`
> 3. `man git-command`

## Setting Up a GIT Repository!
#### 
> 1. **_Importing_** : follow steps within terminal
>> a. switch to target directory for the project being set up ` cd DIRECTORY_NAME ` 
>> 
>> b. use git init command! `git init`
>> 
>> c. start tracking repositories using initial GIT commit


> 2. **_GIT init_** : we shall use `git init` command and have now created a new subdirectory. 


> 3. **_Start Tracking_** :  we start the tracking by performing the following:
>> a. `git add *.c`
>> 
>> b. `git add license`
>> 
>> c. `git commit -m "any message here" `

## Cloning a GIT Repository
### Allows us to create a clone of an already existing repository from server.
> `git clone https://github.com/test`

## GIT Workflow

### Structure of local GIT Repository:

> 1. Working directory of all our files
> 2. Index area that we use to prepare and stage files
> 3. Head is our most recent commit

### Check File Status
#### utiize `git status` command


  
  



[<==== BACK !!!](README.md)
