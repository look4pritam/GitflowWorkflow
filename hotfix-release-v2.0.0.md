# Fix bug two from feature two on hotfix-v2.0.0 branch.

### Checkout hotfix-v2.0.0 branch.

```sh
git checkout hotfix-v2.0.0
```

### Fix bug two from feature two.

Replace "feature two with one bug" to "feature two" in DATA.md file.

```sh
git add DATA.md
```

### Commit changes to the local repository.

```sh
git commit -m 'bug two is hotfixed from feature two.'
```

### View status of GitflowWorkflow repository.

```sh
git status
```

### View the commit history.

```sh
git log --oneline --graph --all
```
