# 90% of Git You Will Actually Use (humorous dad quotes courtesy of ChatGPT)

#### Clone a repo (first time) - "I've got a bad feeling about this."
git clone <repo_url>

#### Check the current repo status - "Don't Panic."
git status

#### Add all changes to the staging area - "Do or do not. There is no try."
git add .

#### Commit changes with a message - "I am altering the deal. Pray I don’t alter it any further."
git commit -m ""

#### Push changes to GitHub - "Off it goes! May the merge conflicts be ever in your favor."
git push origin main

#### Pull the latest changes from the remote repo - "Let’s see how bad the damage is before I add my own."
git pull origin main

#### Create a new branch - "It's dangerous to go alone! Take this."
git checkout -b feature-branch

#### Merge changes from a branch into main - "I know this ship like the back of my hand."
git checkout main
git merge feature-branch

#### Undo the last commit (soft reset) - "Great Scott!"
git reset --soft HEAD~1

#### Undo a commit completely (be careful!) - "I can’t let you do that, Dave."
git reset --hard HEAD~1

#### Always remember: "Commit early, commit often, for code abandoned is code lost."
