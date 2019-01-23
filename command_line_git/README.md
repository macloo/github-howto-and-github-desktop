# Command–Line Git

Anything you can do in GitHub Desktop can be done on the command line instead. If you’re new to coding, you might want to wait until you have more experience to start using git commands. There’s nothing wrong with using GitHub Desktop to manage your repos.

Here’s the [official reference](https://git-scm.com/docs) for git commands.

Here’s a brief cheat sheet:

```
git clone <url>
```
Assuming a git repository at that URL, e.g. at GitHub, this copies the complete repo to your computer.

```
git add myfile.html
```
Now that file (which must already exist) is being tracked by git. Use `git add *` to add all files in the repo.

```
git commit -m "My commit message"
```
Commit everything that’s been added. A message is required.

```
git status
```
Tells you whether there are uncommitted files (changed or new files).

```
git push
```
Push (upload) all committed files to the online repo (e.g. at GitHub).

```
git pull
```
Bring any changes made to the remote repo down to your local machine.
