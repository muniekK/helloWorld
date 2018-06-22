# helloWorld
I'm rying to understand how github works
* [GitHub Guide](https://guides.github.com/)
	* [HelloWorld steps](https://guides.github.com/activities/hello-world/)
	* [Markdown syntaxe](https://guides.github.com/features/mastering-markdown/)
	* [Git handbook *(very useful)*](https://guides.github.com/introduction/git-handbook/)
	
	
#### Example 1: Contribute to an existing repository
>1. download a repository on GitHub.com to our machine
	*git clone https://github.com/me/repo.git*

>2. change into the `repo` directory
	*cd repo*

>3. create a new branch to store any new changes
	*git branch my-branch*

>4. switch to that branch (line of development)
	*git checkout my-branch*

>5. make changes, for example, edit `file1.md` and `file2.md` using the text editor

>6. stage the changed files
*git add file1.md file2.md*

>7. take a snapshot of the staging area (anything that's been added)
*git commit -m "my snapshot"*

>8. push changes to github
*git push --set-upstream origin my-branch*

#### Example 2: Start a new repository and publish it to GitHub

>1. create a new directory, and initialize it with git-specific functions
git init my-repo

>2. change into the `my-repo` directory
cd my-repo

>3. create the first file in the project
touch README.md

>4. git isn't aware of the file, stage it
git add README.md

>5. take a snapshot of the staging area
git commit -m "add README to initial commit"

>6. push changes to github
git push --set-upstream origin master

#### Example3: contribute to an existing branch on GitHub
>1. assumption: a project called `repo` already exists on the machine, and a new branch has been pushed to GitHub.com since the last time changes were made locally

>2. change into the `repo` directory
cd repo

>3. update all remote tracking branches, and the currently checked out branch
git pull

>4. change into the existing branch called `feature-a`
git checkout feature-a

>5. make changes, for example, edit `file1.md` using the text editor

>6. stage the changed file
git add file1.md

>7. take a snapshot of the staging area
git commit -m "edit file1"

>8. push changes to github
git push


***
- [x] task1
- [ ] task2
