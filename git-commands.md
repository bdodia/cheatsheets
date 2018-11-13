## Create a branch
<code>git checkout -b WIP-some-branch</code> this will create a branch named <code>WIP-some-branch</code>
Use <code>git push</code> to get the command to create the branch in remote.

## Remove an unstagged change
<code>git checkout -- some-file</code>

## Reset a stagged change
<code>git reset some-file</code>
  
## Squash branch commits
<code>git merge --squash WIP-some-branch</code> this will squash all commits in the branch <code>WIP-some-branch</code>
and merge plus stage them for commit in your working branch

