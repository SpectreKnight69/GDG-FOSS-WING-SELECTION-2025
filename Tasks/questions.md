### Answer the following questions in you own words.

> It's not necessary that you havee to know and answer all the questions. Just answer the ones
> you know and write in your own words.

1. Give the difference between the remotes - upstream and origin - with an example.

You answer: origin is my fork of the original repo where I push changes, whereas upstream is the original repo that you forked from.

2. You have two branches A and B and you have currently made some changes in branch A.
You want to move into branch B but do not want to commit the current changes in branch A.
What will you do?

You answer: I would use "git checkout -f B", this would switch the branch to B without commiting the changes in A, but the changes made by you in branch A will also not be saved.

3. You were assigned a work to implement a feature and create a PR to your organization's remote repository.
For this you made a branch (say A) and made some changes and commited them. Now you moved to some other branch 
(say B) to do some other assigned work. But later you realisd that have to complete the task assigned earlier 
first and commited some changes in branch B which are meant for branch A. How will you use git to bring the 
changes from branch B to branch A?

You answer:

3. What is the difference between fetching changes and pulling changes?

Your answer: If I am working on a repo and the main branch has some changes then if I use git fetch, then it will show the changes on my local repo without merging them directly so that I can review the changes first. But if I did git pull, then the changes will be automatically merged into my local repo and the code will be updated.

4. What does -i flag stand for? What is it's significance in git?

You answer:

5. You are working in an organization that follows very strict guidelines for PRs and commits.
You made three commits in your PR and the maintainer says you were supposed to make a single commit.
What will you do in this case?

You answer: I would close the PR first, then again clone the repo, make all the changes and then make a single commit and raise a PR again.

6. Explain `git merge` and `git rebase` with example(s).

You answer: when we use git merge, it merges two branches from that point onwards and creates a merge commit, so the past commit history of both branches will stay as it is, but in git rebase, one branche's commits will be moved on top of the other branches, hence a single line history will be maintained. 

7. Write the flow how you create a repository and push changes to it. Also mention the commands used at each step.

You answer:
- First create a new repository in Github and name it (eg. new_repo). Copy the url of the repo which will be used later.
- Now in your device's folder, initialize a repo using "git init".
- Now use "git remote add origin <your repo's url>, this will connect your local repo to the remote repo you created.
- Now create files and make changes as you want, then use "git add ." this stages all the files for commit.
- Then use "git commit -m "commit message"" this saves your changes with a proper message.
- Then use "git push -u origin main" this will push the your local main branch to the remote origin.

8. How would you prevent a file or folder from getting tracked by git?

Your answer:

9. You did not implement the step you mentioned in question 8 and now you have committed and pushed your database's
secret key to the github. How will you remove the key from your git's commit history to avoid any misuse?

You answer: 

---