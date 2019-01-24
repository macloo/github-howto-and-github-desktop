# Publish or Push: Git Commit and Sync

You may *publish* or *push* files to a GitHub repo at any time. You can push again and again as you develop a project and add new files to it, or when you edit or delete files.

Each time you push, your new changes are noted and stored. Your previous versions of all files are still accessible to you. You can go back and view a previous version of any file.

Git (and GitHub) is a *version control* system.

## Commits, and commit messages

Before you can synchronize your local files (local repo) with GitHub (remote repo), you must **commit** your changes. Git requires this.

A commit is often described as a snapshot. The snapshot records what has changed in this project since your last commit. The list of all commits is a record of all the changes made to the project since it began.

The **commit message** is your description or explanation of those changes. These messages can be very helpful in collaborative projects. They might be less meaningful for small, solo projects &mdash; but you have to write them anyway.

You can view all commits in a project (shown below in the GitHub Desktop app) and even revert to a previous version. The **History** tab in the app reveals your past commits.

<img src="../images/commit_messages.png" alt="GitHub Desktop commit messages" width=960>

## How to commit

A good commit message for this case would be: “Completed assignment files.”

In the **Changes** area of the app, bottom left, type your commit message in the box that says “Summary.” You don’t need a description. Click the button that says “Commit to assignment-yourname.” **Note:** *assignment-yourname* is the name of your branch. If this says “Commit to master,” you have not been working in the correct branch!

<img src="../images/app-commit-field.png" alt="GitHub Desktop commit field" width=261>

**If you change anything** in your files after this, you will need to commit again. Same procedure, but you should write a different message, such as “fixed color error” — describe what you changed.

## How to sync, or push

Do this **after you commit.** You can make many commits, or one, before you push. In other words, you do not need to push every time you commit.

In the app, you'll find a “Push origin” button at the top. To push your changes up to GitHub.com, click the button. If the button says “Fetch origin,” you have not committed any changes.

**Note:** If you have not published this branch yet, the button will say “Publish branch,” not “Push origin.” Click that.

By pushing, you make your remote repo (at GitHub) match your local repo (on your hard drive), providing a backup for your work. By keeping local and remote repos synchronized, you can protect your work and also share it with other people.

Look at your repo on **github.com** and check to see that your files are there, in the *assignment-yourname* branch, in the *assignment* folder.

## Check the rubric

Make sure you have done everything listed in the [rubric](../rubric).

If so, submit the complete URL of your GitHub repo in Canvas.

If you need to change anything in your files: After changing and saving them in your text editor, re-follow the steps on this page to commit again and push.

**If you do not push, I will NOT see your changes.**
