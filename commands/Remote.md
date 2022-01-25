# git remote

When working with git, a **remote** is any git repository that is not on the machine that you're working on. The counterpart is to this is **local**, or the machine is being developed on.

Take GitHub for example. While git is technology that allows you to create local repositories, GitHub is a site that will host your remote repositories. Once stored remotely, you can bring that repository back down or share it with others. 

**Note**: While the repositories (local and remote) are relatedand track the same project, they can have different states if the changes are not shared between the two.

### Add a remote

A remote can be added with the `git remote add` command, followed by the name and location of the remote. 

The name is a local name, meaning it's your label and does not impact the actual remote whatsoever. 

```
git remote add origin https://github/ElevenFiftyAcademy/GitFundamentals.git
```

### Remove a remote 

A remote can be removed with the `git remove remote` command, followed by the name of the remote.

```
git remove remote origin
```

## Resources

- [Git Remote Documentation](https://git-scm.com/docs/git-remote)

--- 

[Back to home](../README.md)

