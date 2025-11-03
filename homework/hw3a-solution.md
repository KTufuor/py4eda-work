# HW3A Solution- Git and Version Control

## Part 1: Repository Cloning

I successfully cloned the class repository from `https://github.com/olearydj/INSY6500` to`~/insy6500/class_repo`.
 
### Key Commands Used
- `git clone <url>`- Create local copy of remote repository
- `git log`- View commit history
- `git remote-v`- Check remote repository connections
- `git init`- Intiliazing a directory as git repository
- `git commit`- commiting repositories

## Part 2: Portfolio Repository Creation
I created my personal course repository with:

- Professional README.md describing the project
- Proper .gitignore to exclude unnecessary files
- Organized directory structure for homework, projects, and notes
 
### Understanding Git Workflow

The three-stage workflow:

1. Working Directory: Where I edit files
2. Staging Area: Where I prepare commits with `git add`
3. Repository: Where commits are permanently stored with `git commit`


## Part 3: GitHub Publishing

Successfully published repository to GitHub:

- Used `git remote add origin` to connect local repo to GitHub
- Used `git push-u origin main` to upload commits
- Verified all files and commits are visible on GitHub
 
### The Remote Connection

My local repository is now connected to GitHub:

- `git remote-v` shows the remote URL
- `git push` will send my commits to GitHub
- `git pull` will get updates from GitHub (if changes are made on GitHub)
 
### Details

This section shows the details from the setup:

- Repository URL: https://github.com/KTufuor/py4eda-work

- Output of `git remote-v`:
 - origin  https://github.com/KTufuor/py4eda-work.git (fetch)
 - origin  https://github.com/KTufuor/py4eda-work.git (push)

- The output of `git log--oneline`:
 - 5aa284c (HEAD -> master, origin/master) Add hw3a solution document
 - 3b5ab96 Initial commit: Add README and .gitignore

## Questions

### Reflections

### Question 1: Git Workflow Benefits 

- I typically manage differnt versions of my work by saving them under different names when I make any changes to enable me differentiate them. 
Git offers a better approach in dealing with various versions of a particular work, it tracks every change made in a work and it is easy to go back to previous versions 
unlike what I used to do where I will have to look through alot files to get a specific version of my work. 
 - With Git you have great control of all versions of any work or project 
 - Git makes it easy to track changes with the commit history 
 - Collaborative work is easy when using Git, you will know when a change was mnade and the person who made that change
 
- The Git commit history would have played a crucial role with my excel datasets. I recently worked on a transportation safety data analysis assignment which involved updating the datasets
for analysis but not all changes made could be tracked. Git commit history would have given me that advantage to know all the updates I made with my analysis.

### Question 2: Repository Organization

- The class_repo serves as a reference guide to be used to make edits in my repo. When these two are put in same repository the original copy from the instructor is lost and any changes made to my repo 
will create confusion between personal work and the instructor's. This also makes it difficult to pull any updates from the class repo.

- Multiple repositories must be organized based on what it is to be used for and who can access it or make changes to it. 
 - For a group project a shared GitHub is the best to allow all members haveaccess to it and commit needed changes while tracking contributions
 - For individual assignmets, each assignment should have different repo for easy management
 - Reference materials can be a read-only repo to ensure the original materials are alwasy intact

### Question 3: Commit Message and History

- The " Add hw3a solution documenting Git workflow and repository structure" is more useful;specifically it describes what was changees had happen whiles the "update" does not.
Commit becomes useful again when explaining your work and you need to go back to see how things where done 

- I will decide to commit when a crutial update is made in my analysis. Thus the update address a specific analysis. This makes a good "unit of work" for a single commit

### Graduate Questions

### Question 1: Three Stage Model

- committing README.md and .gitignore sets te basis for the homework. The README.md provides the documentation for the homework and .gitignore shows which files should be excluded in the homework
These two represent a unit of work and therfore a single commit is best. hw3a-solution also reprensents a unique unit of work and needs to be committed separately.
If all where committed together it will be difficult to tell when the set up for the homework begun and when the actual work solutions begun making it hard to track changes.

- The code to load data, fixing a typo in a comment and update to the README will be committed now becaause they all represent a complete meaningful task
The half finished analysis will need to wait until it is all done to represent a complete task. Committing it now may create confusion with the next update.
Staging lets you choose exactly which changes to include the the commit; allowing you to review and organize the changes.

- git status gives a general update of you work from the last commit; what have been modified, added or deleted, which changes are staged and which are unstaged
It should be use more frequently in any workflow before staging and committing to verify which changes are about to be made.

### Question 2: Local Vs Remote Repositories

- Git is called a distributed version control system because every local repository is a copy of the entire project. That is to say one can view the history and also make other commits
Unlike google drive or dropbox that just stores current files without any history to any changes made. 

- This is valuable for developers because you can work on a project anywhere and at anytime and it gives control to what to share with others using git push after committing. 
This ensures collaborative workflows where developers work independently and combine their work later.

- git clone: this creates a complete local copy of a remote repository
  git pull: this is used to get updates from the remote repository 
  git push: this allows you to upload commits on local repository to the remote
- You can only pull from the class repo because it is a shared read only repo which allows you get updates to a local repo, my repo 
  You cannot push to the class repo because you do not have a write access to it.
- my repo supports both because it is the repository cloned from the class repo which makes you have access to both read and write. This lets you to be able to push your work to GitHub

### Question 3: Professional Portfolio  

- Before committing I will have to ensure that the changes represent a single unit of work which is meaningful. Creating branches to show progress including mistakes and iterations to show workflow and problem solving
and the main branch will be for presenting polished final products

- A README for a portfolio repository should highlight skills, projects with a clear explaination of how each works and accomplishments. This is more like centered on the developer; selling yourself
  A README for an open source project focuses on the technical aspect of a project that will help others understand and use your work or possibly contribute to it. This represents instructions 
and guidelines to a project

- It is necessary to frequently use Git and GitHub in various work or projects. This will show the progress and skills allowing employers or collaborators see your development overtime and the various 
projects. All projects need to have README files
