# Gophermaps Parent Repository
<!--- Fill description here --->
todo


# Submodule Links

## 🗃️ [Backend](https://github.com/ryan-roche/gophermaps-backend)
## 📱 [iOS](https://github.com/ryan-roche/gophermaps-ios)
## 🥔 [Android](https://github.com/ryan-roche/gophermaps-droid)


# Current Staff
<!--- Fill members here --->
todo


---


# Getting Started

Join the UMN social coding [Discord Server](https://www.socialcoding.net/discord) and (if you haven't already) introduce yourself in the project's channel to get added as a collaborator.

> [!TIP]
> You may want to read up on git submodules before you continue. A good resource is [this article](https://www.atlassian.com/git/tutorials/git-submodule) by Atlassian (makers of Jira and Bitbucket)

> [!IMPORTANT]
> If you're looking here because your submodules are out of date, run `git submodule update` in the directory for this repository

Clone the parent repository and its submodules with

```bash
git clone --recurse-submodules git@github.com:ryan-roche/gophermaps.git
```

`cd` into the appropriate submodule for what you're working on.


# Working Practices

The project repositories are configured with rules that revent pushing directly to the master branches. *This was done intentionally* in order to prevent untested/unvetted code from making it to the master branch, as we may adopt a CI/CD model in the future.

**Any additions to the master branches, merge or not, must be done through a Pull Request.**
