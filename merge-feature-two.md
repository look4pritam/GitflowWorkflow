# Merge feature-two branch into develop branch.

### Checkout develop branch.

```sh
git checkout develop
```

### Merge feature-two branch into develop branch.

Use --no-ff option to create a merge commit.

```sh
git merge --no-ff feature-two
```

### Delete feature-two branch.

```sh
git branch -d feature-two
```

OR

```sh
git branch -D feature-two
```

### Push changes to the remote repository.

```sh
git push origin develop
```


