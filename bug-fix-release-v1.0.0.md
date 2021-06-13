# Fix one bug from feature one on release-v1.0.0 branch.

### Checkout release-v1.0.0 branch.

```sh
git checkout release-v1.0.0
```

### Fix one bug from feature one.

Replace "feature one with two bugs" to "feature one with one bug" in DATA.md file.

```sh
git add DATA.md
```

### Commit changes to the local repository.

```sh
git commit -m 'one bug is fixed from feature one.'
```

### View status of GitflowWorkflow repository.

```sh
git status
```

### View the commit history.

```sh
git log --oneline --graph --all
```
