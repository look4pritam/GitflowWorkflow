# Merge feature-one branch into develop branch.

### Checkout develop branch.

```sh
git checkout develop
```

### Merge feature-one branch into develop branch.

Use --no-ff option to create a merge commit.

```sh
git merge --no-ff feature-one
```

### Delete feature-one branch.

```sh
git branch -d feature-one
```

OR

```sh
git branch -D feature-one
```

### Push changes to the remote repository.

```sh
git push origin develop
```


