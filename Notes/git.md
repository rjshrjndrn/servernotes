1. Check the parent branch

```sh
git show-branch -a | grep \* | grep -v `git rev-parse --abbrev-ref HEAD` | head -n1 | sed 's/.*\[\(.*\)\].*/\1/'
```

1. Create a git server on local
    1. Create a local user
    2. give the repo permission to that user
    3. add user ssh keys to that accout authorized_keys
    4. git config recieve.denyCurrentBranch ignore
