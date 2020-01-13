Using Git as a Team

Create a git branch and make it public

Select the collaborators tab on the left and invite the team with their github user names

Get the SSH key and git clone the repo

The git master should make a new branch and other contributors should then clone the repo

A pull request fetches and merges

A fetch request should be completed by the team, so the branches are fetched

<hr>

Then `gco development` to go onto the development branch from master

Make a feature branch 



Open Atom `atom .`

Git add . git commit `git add .`---`git commit -m "commit comment"`

Chnage to the development branch `gco development`

Pull the development branch down `git pull origin development`

Chnage to the feature branch `gco feature-branch`

Merge the development branch `git merge development`

Change to the development branch `gco development`

Merge the feature branch to the development branch `git merge feature-branch`

Push to the development branch`git push origin development`

<hr>

`gco -b feature-branch-2`

`atom .`

Add in code!

`git add .`---`git commit -m "commit comment"`

`gco development`

`git pull origin development`

`gco feature-branch-2`

`git merge development`

resolve conflicts by clicking on the ..., to keep all code, clikc `dismiss` and delete the code which was placed to show which code came from which branch

`git add .`---`git commit -m "merge conflict resolved"`

`gco development`

`git merge feature-branch-2` 

`git push origin development`

<hr>

If you have been working on the development branch, as long as you havn't committed

`gco -b new-branch`

Once this branch has been made, all the code will be brought into the new branch

If you have commited, soft reset by one commitgit 