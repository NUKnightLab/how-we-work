# Navigating Github 

Two challenges developers face are keeping track of code changes and collaborating with other developers. In programming, we have a concept called version control that addresses these two challenges. Not only does version control make it easy to keep track of changes, it also enables other developers to work off the same codebase in real time, thereby encouraging collaboration. 

## Enter Git
Git is a distributed version control system—which means you can use it offline. Git keeps track of your revisions through "commits". Instead of renaming and accumulating multiple file versions, git allows you to track a file's history by "committing" them to git. These commits make up a project's history and have meta information like date, time and message associated with a commit. This is useful so that you can view the trajectory of your project and revert or "roll back" changes.

## Wait, so what's Github?
  > GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.
  --<cite>Github</cite>

Github is an online repository for hosting projects that are version controlled with git.

## So, which do I use?
Both! Git runs locally on your machine and you commit changes to your project as you go. Github is the online repository that you "push" your code to and from which you "pull" in changes made to the codebase.

## Using Github

### Step 0: Create an account
If you haven't already, create an account on [github](https://github.com/). Be sure to choose a username that is readable and easily identifiable since your github username will be used on projects and contributions.

### Step 1: Create an example repository
A repository is what github calls a place where your project will live and can contain anything from images to data sets in addition to your source code. 

1. In the upper right hand corner of your page, click on the + button next to your avatar and select `New Repository`
2. Name the repo, something like `example-project` works, add a description (this is optional) and click the green button `Create Repository`.

### Step 2: Set up git on your local machi
As described earlier, github is an online hub for open source code. Github uses Git, which is a version control system that allows you to manage the history of your contributions to a project.
Github is therefore a webpage where you can publish and view your git repositories.

#### Step 2a: Install git 
To install git on your local machine, [follow these instructions](https://git-scm.com/book/en/v1/Getting-Started-Installing-Git). If you have homebrew installed, you can run `brew install git` in your terminal.

#### Step2b: Set up your git configurations
Set up your username and email address, this is super important because this is what git will use as metadata for a commit.

`git config --global user.name "Jane Doe"`
`git config --global user.email "user@email.com"`

Another thing to consider setting up is your default editor, this will be what git uses when prompting you to type a message or organize your git log. Vim is a popular text editor, but you are free to use whatever you are most comfortable with.

`git config --global core.editor vim`

To check your local configurations, type `git config --list`.

#### Step 2c: Syncing your local git to your github account.
This step is a little more complicated, so take your time to do this. Connecting to github requires authentication and you can do so via HTTPS or SSH. Instructions for either of those methods can be found [here](https://help.github.com/articles/set-up-git/). The key difference is that when you use HTTPS, git will prompt you for a password each time you push or pull from github, whereas with SSH, you don't have to type in a password but you do have to generate public and private SSH keys.

### Step 3: Making a commit
Once you have git set up on your local machine and a github account created, you can now make your first commit!
Navigate to your example repo that you created earlier. You should see a list of instructions on quick setup.

#### Step 3a: Initialize Git
In your project directory, initialize git by typing `git init`

#### Step 3b: Add a readme
Create an empty readme file by typing `touch README.md` and then `git add README.md` in your terminal.

#### Step 3c: Create a commit message
Type in a commit message but typing `git commit -m "Initial Commit"`.

#### Step 3d: Connect your local repository to your remote github repository
Copy and paste the url git generates for you and prepend it with `git remote add origin`
This will look something like this `git remote add origin https://github.com/NUKnightLab/example.git`

#### Step 3e: Push to github
Type in `git push -u origin master` to push your local git repo to remote.
Congrats on your first git commit!!! 🎉 

## Useful github commands to know 
`git status`
Lists all modified or new files in your git repository.

`git diff`
Shows you unstaged changes, aka exact file changes you've made to your git repository that you have yet to commit.

`git branch`
Lists all branches in your repository.

`git branch [branch-name]`
Creates a new branch based off the current branch you are on.

`git checkout [branch-name]`
Switches to another branch.

`git log`
Shows your commit history for a given branch in your repository.

For more git commands, check out the [github cheatsheet](https://services.github.com/kit/downloads/github-git-cheat-sheet.pdf)
