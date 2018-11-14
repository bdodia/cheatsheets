## Create a branch
<code>git checkout -b WIP-some-branch</code> this will create a branch named <code>WIP-some-branch</code>

To push the current branch and set the remote as upstream, use

<code>git push --set-upstream origin WIP-some-branch</code>

Use <code>git push</code> to push changes to remote


## Add files to stage
<code>git add some-file</code> to update/add a specific file for commit

<code>git add .</code> to update/add all files/folders in current working directory for committing

<code>git add -p</code> to interactively review and update/add individual changes in all files/folders in current working directory for committing

## Remove an unstaged change
<code>git checkout -- some-file</code> discard changes in working directory that are not yet staged

## Reset a staged change
<code>git reset some-file</code> Reset a mistake that has gone through to stage

## Commiting a change
<code>git commit -m "Some helpful commit log description"</code>

### Add changes to last commit without changing message
<code>git commit --amend --no-edit</code>

## Squash branch commits
<code>git merge --squash WIP-some-branch</code> this will squash all commits in the branch <code>WIP-some-branch</code>
and merge plus stage them for commit in your working branch

