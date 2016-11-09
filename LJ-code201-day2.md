#LJ Code 201 - Day 2

Things learned:
- It is easiest for me to understand Git/GitHub if I relate it to REVIT. There is a main, remote repository that is stored on GitHub (like a central file in REVIT). You have to clone the repo to create a working local repo on your machine (like opening a local file in REVIT). You need to "add" changes and "commit" them to the staging area before "pushing" those changes (like syncing in REVIT) up to the main repository.
- There is not an exact parallel for Branches in REVIT. It is most similar to methodically saving before syncing with the central file. Branches allow you to batch changes in a larger group to later merge with master all at once.

- branching terminal commands:
$ git checkout branch-name (moves to that branch)
$ git checkout -b new-branch-name (creates new branch name and moves to that branch)
$ git add file-name
$ git commit -m "message"
$ git push remote-name(origin) branch-name

Then in GitHub, pull request, then merge with master

My other (somewhat obvious) revelation today:
Now that we are opening the code in a browser and are able to see the console, I understand what print to console means. Before, I wasn't really sure where this was showing up or what to print because I didn't know who was able to see it.
