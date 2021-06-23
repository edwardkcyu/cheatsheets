# git cheatsheet

Delete local tags that do not exist in remote
```bash
git fetch --prune origin "+refs/tags/*:refs/tags/*"
```

Remove untracked files
```bash
git clean -f
```

Rename branch
```bash
git branch -m newname
```

Batch delete branches
```bash
git branch | grep '^feat/*' | xargs git branch -D
```

Show graph of all branches
```bash
git log --graph --pretty=oneline --abbrev-commit --all
```
