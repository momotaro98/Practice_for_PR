# Practice_for_PR
This is repository for Pull Request Operation
## Hello PR!
How to merge the remote to local!?
```
$ git push origin <branch>
```
The <branch> means remote branch or local branch?


## Before Understanding git push/pull arguments
```
$ git push/push origin <source>:<destination>
```
when push, ommied source, and when pull, ommied destination?
I mean local branch is defaulted to current branch.

`git push origin master` means I push current branch to remote's master???  
and  
`git pull origin master` means I pull remote's master to current branch???  

## After Understanding git push/pull arguments (Maybee)
```
$ git push/pull origin X_place
```
above commnad.  
`X_place` is **source refference**.  
when push, X_place is local, otherwise, when pull, X_place is remote.  
So, in defualt, when push, remote master is default.
But, pull commnad means fetch + merge, so, pull commnad makes all branches merged???

## Hello issue???
### Difference between git pull and git pull --rebase
