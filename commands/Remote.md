# git remote

when working with git, a **remote** is any git repository that is not on the machine you're working on. The counterpart to this is **local**, or the machine that was developed on.

Take GitHub for example. While git is the local technology that allows you to create local repositories, GitHub is the site that will host you remote repositories. Once stored remotely,you can bring that repository back down or share it with others.

**Note**: While the repositories (local and remote) are related and track the same project, they can have different states if changes are not shared between the two.

### Adding a remote

A remota can be added with the `git remote add` command, followed by the name and location og the remote.

The name is local name, means it's your label and does not impact the actual remote whatsoever.

```
git remote add origin
https://github.com/ElevenfiftyAcademy/GitFundamentals.git
```
### Removing a remote

A remote can be removed with the `git remote remove` command, followed by the name of the remote.

```
git remote remove origin
```

## Resources

- [Git Remote Documentation](https://git-scm.com/docs/git-remote)

---

[Back to home](../README.md)