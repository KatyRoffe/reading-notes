### Version Control

Allows a user to:
* revert a file/project back to a previous version
* track modifications
* compare changes

Types | Description
------ | -----
Local | One database on the hard disk
Centralized (CVCS) | Single server storing changes and file versions
Distributed (DVCS) | Allows for mirrored repositories for simultaneous workflows

# What is Git?

Git is a DVCS. Every time the user saves a change (a commit) a versions of their project, Git creates a snapshot of the file and stores it for future referencing. 

It mostly relies on local operations without the need of fetching information from a server. This allows a user to continue working on their projects without being online or requiring a VPN.

Because it tracks every change applied to a file, it can detect file corruption or loss of data. 

## States of Files

Type | Description
----- | -----
Committed | Data is saved: stored in a local database
Modified | File has been changed, but has not been committed
Staged | The changed version ready to be committed in a snapshot


# Customization 

Git can be downloaded directly from their [website](http://git-scm.com/downloads). It can also be installed on Windows are part of [GitHub](http://windows.github.com)

Once installed, certain variables can be configured. 

Users should set their user name and email to sign their Git Commit. 

### Identity Setting Commands
>`git config -- global user.name "The Doctor"`

>`git config -- global user.email "thedoctor@email.com"`

### Confirm Idendity Setting Commands
> `git config --global user.name (result should return as The Doctor)`

> `git config -- global user.email (result should return as thedoctor@email.com)`

### Help Commands
Use these to get information about certain commands

> git help *command*

> git *command* --help

> man git-*command*


# Workflow

The Git repository has three components

Component | Purpose
----- | -----
Working Directory | Where the actual file resides
Index | Area used for staging
Head | Points to the most recent commit

### Saving Changes
Working copies of project files are in one of two states.
* Tracked : These files can be modified, unmodified, or staged. 
* Untracked : These do not exist in the staging area. 

### Life Cycle
1. Edit a file - Git flags it as modified
2. Stage the modified file
3. Commit staged changes

## Commands

Name | Command | Purpose
----- | ----- | -----
**Add** | `git add "file_name_here"` | adds a file to the git repository
**Commit** | `git commit -m "notes"` | commits changes and adds notes regarding the edit
**Push** | `git push origin main` | pushes the changes to a remote repository
**Stash** | `git stash` | temporarily removes changes that don't want to be removed but aren't ready to commit
**Stash Apply** | `git stash apply` | retrieves the hidden changes 
**Git Status** | `git status` | determines the state of a file

[Return to Home Page](https://katyroffe.github.io/reading-notes/)