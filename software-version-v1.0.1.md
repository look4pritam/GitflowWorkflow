# Release software version v1.0.1.

### Checkout master branch.

```sh
git checkout master
```

### Merge hotfix-v1.0.0 branch into master branch.

Use --no-ff option to create a merge commit.

```sh
git merge --no-ff hotfix-v1.0.0
```

### Push changes to the remote repository.

```sh
git push origin master
```

### Create software version v1.0.1 tag.

```sh
git tag -a -m 'Software version v1.0.1 is released.' v1.0.1
```

### View tag information.

```sh
git show v1.0.1
```

### Push changes to the remote repository.

```sh
git push origin v1.0.1
```

### Checkout develop branch.

```sh
git checkout develop
```

### Merge hotfix-v1.0.0 branch into develop branch.

Use --no-ff option to create a merge commit.

```sh
git merge --no-ff hotfix-v1.0.0
```

### Push changes to the remote repository.

```sh
git push origin develop
```

### Delete hotfix-v1.0.0 branch.

```sh
git branch -d hotfix-v1.0.0
```

OR

```sh
git branch -D hotfix-v1.0.0
```






