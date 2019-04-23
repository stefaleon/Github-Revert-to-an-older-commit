# Github: Revert to an older commit

First clone the repo to local disk, then start a git bash and

1. `git log` -> copy the commit hash you want to revert to
2. `git checkout <commit hash>`
3. `git push origin <commit hash>:master -f` 