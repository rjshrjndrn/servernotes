1. Check the parent branch

```sh
git show-branch -a | grep \* | grep -v `git rev-parse --abbrev-ref HEAD` | head -n1 | sed 's/.*\[\(.*\)\].*/\1/'
```
