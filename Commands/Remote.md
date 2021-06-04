# git remote

When working with git, a **remote** is any git repository that us not on the machine youre working on. The counterpart to this is **local**, or the machine that is being developed on.

Take GitHub for example. While git is the technology that allows you to create local repositories, GitHub is the site that will host your remote repositories. once stored remotely, you can bring that repository back down or share it with others.

**Note**: While the repositories (local and remote) are related and track the same project, they can have diffrent states if changes are not shared between the two.

### Adding a remote

A remote can be added with the `git remote add` command, followed by the name and location of a the remote.

The name is a local name, meaning its your label and does not impact the actual remote whatsoever.

```

git remote add origin httpsL//github.com/ElevenFiftyAcademy/GitFundamentals.git
```

### Removing a remote

A remote can be removed with `git remote remove` command, followed by the name of the remote.

```
git remote remove origin
```

## Resources

- [Git Remote Documentation](https://git0scm.com/docs/git-remote)

---

[Back to home](../README.md)
