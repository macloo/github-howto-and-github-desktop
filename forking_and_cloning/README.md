# Forking and Cloning with GitHub

Before you read this, please make sure you are familiar with the [basics of GitHub](../github_basics).

## Forking a repo

This is how you make a copy of someone else’s repo for yourself. Make sure you're *signed in* at GitHub first.

A repo can contain lots of files and folders, or few, or none (that would be an empty repo). Each GitHub user can have unlimited repos. As many as you want.

### Why do we fork?

To get a complete copy of a repo that we can work with, edit, or add to &mdash; and then, usually, contribute back to, with a pull request.

### When should you just download instead?

If you don't intend to contribute to a repo, there’s no need to fork it. Just download a zipped copy using the “Clone or download” button at GitHub.

<img src="../images/download.png" alt="GitHub's Clone or download button" width=434>

*From the “Clone or download” button, you can either fork the repo &mdash; “Open in Desktop,” &mdash; or download a zipped folder &mdash; “Download ZIP.”*

### How to fork

Find the button that says “Fork” near the top of the page, right side, at GitHub.com. WAIT BEFORE YOU CLICK IT. This makes a new, independent copy of the entire repo under YOUR GitHub username. You will have your own copy. As soon as you click “Fork,” you'll be *on YOUR COPY.* Look at the URL in the browser address bar, and you’ll see **your own username** there.

**Fork:** Your repo (the forked copy) will not be changed when the original owner changes the original. Likewise, you can *change* your copy, and it will not affect the original. In most cases, you will only fork ONCE for one repo. (There is a way to update so that yours matches any changes made to the original, but let’s leave that aside for now.)

The original URL:

<img src="../images/url1.png" alt="Original URL for a repo" width=537>

The new URL will contain your username:

<img src="../images/url2.png" alt="New URL for the forked copy" width=582>

**After forking:** The repo does not exist on your computer YET.

Only FORK a repo ONCE. After you have forked it, it exists as a repo on YOUR GitHub.com site, online.

## Cloning a repo

**IMPORTANT NOTE:** Before you CLONE a repo, *make sure* you are on **your own** GitHub.com page for that repo.​ The one you FORKED. Do not clone it from another user’s GitHub page, where the URL includes THEIR username. Clone it from *your own* GitHub, where the URL includes YOUR username.

Find the button that says “**Clone or download**” (right side, below the Fork button”). Click it.

Click “Open in Desktop,” and your copy of the repo will appear in your GitHub Desktop app. If you are asked to “Launch Application,” do so, even if it’s already open.

<img src="../images/clone.png" alt="GitHub's Clone or download button" width=440>

**You will be asked to choose a place on your hard drive for this repo.** Put it inside the exact folder you want it to be in. DO NOT put it on your Desktop! You shouldn’t move it later. DO NOT change the repo name.

**Clone** uses your app (GitHub Desktop) to make a copy of the entire repo on your hard drive, and this copy is *tethered* to the version on the GitHub.com site. You *might* clone a repo more than once, in some circumstances.

If you get an error message, double-check that you have followed the steps above correctly.

## What you should have now

At GitHub.com, when you go to your user page/profile, you’ll see a link to your new repo (click it to view the repo). If you were on the **Repositories** tab, you'll need to **reload** the page to see the new repo.

On your hard drive, you’ll see a folder with the *same name* as that repo. *Do not change the name!* (These two are tethered together, thanks to Git.) Where is that folder? It is where you told it to be saved, when you cloned it.

You could now edit files in the repo on your computer &mdash; *but wait!* If you intend to contribute back to the original, you’ll need to create a **branch** first.

Next: [Git Branches](../git_branches)
