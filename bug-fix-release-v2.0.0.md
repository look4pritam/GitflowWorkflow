# Fix bug one from feature two on release-v2.0.0 branch.

### Checkout release-v2.0.0 branch.

```sh
git checkout release-v2.0.0
```

### Fix bug one from feature two.

Replace "feature two with two bugs" to "feature two with one bug" in DATA.md file.

```sh
git add DATA.md
```

### Commit changes to the local repository.

```sh
git commit -m 'bug one is fixed from feature two.'
```

### View status of GitflowWorkflow repository.

```sh
git status
```

### View the commit history.

```sh
git log --oneline --graph --all
```
