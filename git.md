| Command | Description |
|---------|------------|  
| `git clone http://someserver/someuser/somerepo.git` | Copies the entire repository onto your local machine. | 
| `git checkout -b foo` | Creates a new local branch named `foo`. |
| `git checkout foo` | Switches to extant branch `foo`, fails if that branch doesn't already exist. |
| `git add somefile.ext` | Stages file to be committed. |
| `git commit -m 'Some commit message'` | Commits all stages files to local repository. |
| `git rebase foo` | Merges changes from _remote_ branch `foo` to current local branch; alters history to appear as if current branch was just made off of master. |
| `git rebase --continue` | Issued after all merge conflicts are addressed. |
| `git push origin foo` | Pushes all changes made to local remote since last clone or pull to remote branch. | 
| `git push origin foo --force` | Unconditionally overwrites remote branch with local branch; strongly discouraged if other committers are working on branch. |