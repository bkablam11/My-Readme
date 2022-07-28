
## TOP 20 Commands : Git/GitHub Cheat Sheet


### Cheat Sheet

1. Command-1:  

```bash
  git init
```

This will create a .git repository in your project. A repository or “repo” is a collection of all the

changes you’ve made to your project over time and will build a history of these changes. This is

the first thing you want to do with a new project.



2. Command-2:

```bash
 git config --global user.name "Your Name"

 git config --global user.email "yourEmail@mail.com"

```

This sets up your information that is used every time you commit. This only needs to be done

once when you first install Git.



3. Command-3: 

```bash
git add filename.extension

```

Replace “filename.extension” to whatever file you are trying to add like “abc.txt”. 

This will add the file you specify to what is called a “staging area” or index. 

Think of the staging area like a section where things are getting set up to be moved to your

repository.

4. Command-4: 

```bash
git add .

```

If you want to add everything from the project folder to the staging area this command will do that instead of having to add each file one by one.



5. Command-5: 
```bash
git add *.txt

```


If you want to add all .txt files to your staging area this would be the command to use. The extension can be changed to whatever you want.



6. Command-6: 

```bash

git status

```
Shows what has already been added to the staging area and what files have been changed that need to be added to the staging area.



7. Command-7: 
```bash
git reset filename.extension

```

Removes specified file from the staging area.



8. Command-8: 
```bash
git rm --cached filename.extension

```


This will remove the file from the staging area and sets it to be untracked.



9. Command-9: 
```bash
git commit -m "Description of the commit details"

```

Takes the files from your staging area and commits them to your local repository.

10. Command-10: 
```bash
touch .gitignore

```

This will create a file called .gitignore. You can open that file with a text editor and write the

name of files or folders you want to be ignored from your repository. Ignored files won’t show

up when you run git status to prevent you from committing files you’ve previously said you 

don’t want to commit or even know about their changes.



11. Command-11: 

```bash
git branch branchName

```


Creates a branch which is a direct copy of your codebase from your previous branch(in most

cases your master branch).



12. Command-12: 

```bash
git branch -d branch_name

```

You can delete the branch if something goes wrong or you decide you don’t need that feature or

bug fix any longer.



13. Command-13: 
```bash
git merge branchName


```

While inside Master branch you can use this command to take the commits from the branch

currently you were working in and merge them together with the main repository.



14. Command-14: 
```bash
git remote add origin https://github.com/userName/projectName.git

```

This adds the location of your remote repository. Everything up until now has been on your

 local repository on your computer. 



15. Command-15: 

```bash
git remote

```

List of your remote repositories that all are associated with your project.



16. Command-16: 

```bash
git push -u origin main

```

This will push your local repository to your remote repository.



17. Command-17: 
```bash
git clone https://github.com/userName/projectName.git 

```


This will allow you to clone (or download) the entire project into your working directory.



18. Command-18: 

```bash
git pull

```

If you are working on the same codebase with other people, this command will allow you to pull

the latest version from the remote repository and update your local version so you can work 

with the latest updates as their changes enter the codebase.



19. Command-19: 

```bash
git show HEAD

```

To show the history of recent commit in current checkout branch.



20. Command-20: 
```bash
Git diff HEAD~commitId1 HEAD~commitId2

```

To show the difference between different HEAD.


21. Command-21: 
```bash
git log

```
show all commits in the current branch’s history


THANKS!!


