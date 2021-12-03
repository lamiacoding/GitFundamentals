# git pull

Similar to a [git push](./PUSH.md). a `git pull` will interact with a remoter  repository, only this time it will **pull** the changes it does not have from the remote down to the local repository.

This means any commits made that are on the remote repository will be added to the local repository.

T his can be done by adding the rmote name and branch name:
```
git pull origin main
```

If there is any upstream connection established, you can use `git pull` without specifying a remote or btanch.

## Resources

- [Git Pull Documentation](https.//git-scm.com/git-pull)

---

[Back to home](../README.md)
- [git pull](./commands/pull.md)