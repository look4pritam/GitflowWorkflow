# Release software version v1.0.0.

### Checkout master branch.

```sh
git checkout master
```

### Merge release-v1.0.0 branch into master branch.

Use --no-ff option to create a merge commit.

```sh
git merge --no-ff release-v1.0.0
```

### Push changes to the remote repository.

```sh
git push origin master
```

### Create software version v1.0.0 tag.

```sh
git tag -a -m 'Software version v1.0.0 is released.' v1.0.0
```

### View tag information.

```sh
git show v1.0.0
```

### Push changes to the remote repository.

```sh
git push origin v1.0.0
```

### Checkout develop branch.

```sh
git checkout develop
```

### Merge release-v1.0.0 branch into master branch.

Use --no-ff option to create a merge commit.

```sh
git merge --no-ff release-v1.0.0
```

### Push changes to the remote repository.

```sh
git push origin develop
```

### Delete release-v1.0.0 branch.

```sh
git branch -d release-v1.0.0
```

OR

```sh
git branch -D release-v1.0.0
```






