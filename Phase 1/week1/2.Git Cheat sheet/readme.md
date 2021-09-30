# A Summary When I'm Stuck

## 1.Configure tooling
| Command Line | Definition |
|---- |---- |
| `$ git config --global user.name "[name]"`| Sets the name you want attached to your commit transactions |
|`$ git config --global user.email "[email address]"`| Sets the email you want attached to your commit transactions|
|`$ git config --global color.ui auto` | Enables helpful colorization of command line output|

## 2.Create repositories
| Command Line | Definition |
|---- |---- |
|`$ git init` | Turn an existing directory into a git repository|
|`$ git clone [url]` | Clone (download) a repository that already exists on GitHub, including all of the files, branches,and commits|

## 3.Branches
| Command Line | Definition |
|---- |---- |
|`$ git branch [branch-name]` | Creates a new branch |
|`$ git checkout [branch-name]`|Switches to the specified branch and updates theworking directory|
|`$ git merge [branch]`|Combines the specified branch’s history into thecurrent branch. This is usually done in pull requests,but is an important Git operation.|
|`$ git branch -d [branch-name]`|Deletes the specified branch|

## 4.Synchronize changes
| Command Line | Definition |
|---- |---- |
|`$ git fetch`| Downloads all history from the remote tracking branches|
|`$ git merge` | Combines remote tracking branch into current local branch|
|`$ git push` | Uploads all local branch commits to GitHub|
|`$ git pull` | Updates your current local working branch with all newcommits from the corresponding remote branch on GitHub. git pull is a combination of git fetch and git merge|


# 5.Make changes
| Command Line | Definition |
|---- |---- |
|`$ git log`| Lists version history for the current branch|
|`$ git log --follow [file]` | Lists version history for a file, including renames|
|`$ git diff [first-branch]...[second-branch]` | Shows content differences between two branches|
|`$ git show [commit]` | Outputs metadata and content changes of the specified commit|
|`$ git add [file]` | Snapshots the file in preparation for versioning|
|`$ git commit -m "[descriptive message]"` | Records file snapshots permanently in version history|

## 6.Redo commits
| Command Line | Definition |
|---- |---- |
|`$ git reset [commit]` | Undoes all commits after [commit], preserving changes locall|
|`$ git reset --hard [commit]` | Discards all history and changes back to the specified comm|


_**CAUTION!**_ >Changing history can have nasty side effects. If you
need to change commits that exist on GitHub (the remote),
proceed with caution. If you need help, reach out at
github.community or contact support.
