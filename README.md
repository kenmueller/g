# g commands for Git

**Install `git` [here](https://git-scm.com/downloads)**

**Create a `GitHub` account [here](https://github.com/join?source=header-home)**

## Functions

**Main functions**

| Function | Push & Commit | Pull | Init | Create | Clone | Commit | Push |
|---|---|---|---|---|---|---|---|
| **Description** | Commits all changes and pushes | Pulls changes from the remote | Initializes the folder from a blank repository | Creates a new folder and GitHub repository, linking them together | Clones an existing GitHub repository | Commits all your changes locally | Pushes your commited changes to the remote |
| **Inputs** | Commit message | | Remote URL or your username + project name | Your username + project name | Remote URL or the owner's username + project name | Commit message | |

**All functions**

1. `Push & Commit` (push {commit message}) or (push {filename} {commit message})
2. `Pull` (pull) or (pull {branchname})
3. `Initialize from a blank repository` (init {remote URL}) or (init {username} {project name})
4. `Create a new folder and repository` (create {username} {project name})
5. `Clone repository` (clone {remote URL}) or (clone {username} {project name})
6. `Commit locally` (commit {commit message}) or (commit {branchname} {commit message})
7. `Push to remote` (onlypush)
8. `New branch` (newbranch {branchname})
9. `Delete branch` (deletebranch {branchname})
10. `List all branches` (branchlist)
11. `Fetch` (fetch)
12. `Graph commit tree` (graph)
13. `Revert to previous commit` (revert {commit id})
14. `Git version` (version)
15. `Remove file from git` (remove {filename})

## Initialization

1. Click on `g.dmg` in the file list
2. On the top right, press `Download` (right next to `History`)
3. Download it, click on it, then open the file (look at your `Desktop`)
4. Double click on `g.command`
5. If it gives you an unauthorized warning, go to `System Preferences -> Security and Privacy -> Open anyway`
6. Press `Open`
7. Done!

## Examples

1. `push "added example.txt"`
2. `pull`
3. `init kenmueller g`
4. `create kenmueller g`
5. `clone kenmueller g`
6. `commit "added example.txt"`
7. `onlypush`