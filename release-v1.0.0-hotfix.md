# Fix bug two from feature one on hotfix-v1.0.0 branch.

### Checkout hotfix-v1.0.0 branch.

```sh
git checkout hotfix-v1.0.0
```

### Fix bug two from feature one.

Replace "feature one with one bug" to "feature one" in DATA.md file.

```sh
git add DATA.md
```

### Commit changes to the local repository.

```sh
git commit -m 'bug two is hotfixed from feature one.'
```

### View status of GitflowWorkflow repository.

```sh
git status
```

### View the commit history.

```sh
git log --oneline --graph --all
```
