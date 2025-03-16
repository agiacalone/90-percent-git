### 90% of The Git Which You Will Actually Use 
##### (Dad jokes courtesy of ChatGPT)

# 🚀 Git Essentials for Absolute Beginners

## 👩‍💻 Getting Started
- **Initialize a new repository** *"Every journey begins with `git init`."*  
    ```bash
    git init
    ```

- **Clone an existing repository** *"It's dangerous to go alone! Take this clone."*  
    ```bash
    git clone <repository_url>
    ```

- **Check the current repo status** *"Don't Panic."*  
    ```bash
    git status
    ```

## ✏️ Making Changes
- **Add files to the staging area** *"One does not simply push without adding first."*  
    ```bash
    git add <file>
    ```

- **Commit changes with a message** *"With great power comes great commit messages."*  
    ```bash
    git commit -m "Your message here"
    ```

## 🚀 Syncing with Remote
- **Push changes to a remote repository** *"To infinity... and beyond!"*  
    ```bash
    git push origin <branch>
    ```

- **Pull latest changes from remote** *"I'll be back... with the latest changes."*  
    ```bash
    git pull origin <branch>
    ```

## 🌿 Working with Branches
- **List all branches** *"Know thy branch."*  
    ```bash
    git branch
    ```

- **Create a new branch** *"Another fork in the road."*  
    ```bash
    git branch <branch_name>
    ```

- **Switch to another branch** *"Beam me up, branchy!"*  
    ```bash
    git checkout <branch_name>
    ```

- **Merge a branch into the current branch** *"I am one with the branch. The branch is with me."*  
    ```bash
    git merge <branch_name>
    ```

## 🔄 Undoing Mistakes (Without Panic)
- **Undo the last commit (without losing changes)** *"I meant to do that!"*  
    ```bash
    git reset --soft HEAD~1
    ```

- **Stash changes for later** *"Hold my beer... I'll come back to this."*  
    ```bash
    git stash
    ```

- **Apply stashed changes** *"And we're back!"*  
    ```bash
    git stash pop
    ```

---

### ✅ Pro Tip: *"Commit early, commit often, for code abandoned is code lost."*
---

# 🏆 Advanced Git Commands for Power Users

## 🛠️ Reviewing History
- **Check commit history** *"Marty, we've gotta go back... to the commits!"*  
    ```bash
    git log
    ```

- **Show differences between commits** *"What's changed? EVERYTHING."*  
    ```bash
    git diff
    ```

- **View changes before committing** *"Measure twice, commit once."*  
    ```bash
    git diff --staged
    ```

## 🔀 Advanced Branching & Merging
- **View remote branches** *"Branches everywhere, but which one is mine?"*  
    ```bash
    git branch -r
    ```

- **Create and switch to a new branch immediately** *"One small step for dev, one giant leap for version control."*  
    ```bash
    git checkout -b <new_branch>
    ```

- **Rename a branch** *"New name, who dis?"*  
    ```bash
    git branch -m <new_name>
    ```

- **Delete a local branch** *"Hasta la vista, branch."*  
    ```bash
    git branch -d <branch_name>
    ```

- **Delete a remote branch** *"It's not you, it's me."*  
    ```bash
    git push origin --delete <branch_name>
    ```

## ⚠️ Undoing & Fixing Mistakes
- **Undo the last commit but keep the changes staged** *"Time travel without side effects."*  
    ```bash
    git reset --mixed HEAD~1
    ```

- **Undo the last commit and discard changes** *(DANGER! 🚨)*  
    ```bash
    git reset --hard HEAD~1
    ```

- **Revert a specific commit (without deleting history)** *"Oops, I did it again."*  
    ```bash
    git revert <commit_hash>
    ```

## 🎩 Rewriting History (Be Careful!)
- **Modify the last commit message** *"Whoops, let me fix that..."*  
    ```bash
    git commit --amend -m "New message"
    ```

- **Squash multiple commits into one** *"One ring to merge them all."*  
    ```bash
    git rebase -i HEAD~<number_of_commits>
    ```

## 🌍 Remote Management
- **View configured remotes** *"Show me what you got!"*  
    ```bash
    git remote -v
    ```

- **Change the URL of a remote repository** *"New repo, who dis?"*  
    ```bash
    git remote set-url origin <new_repository_url>
    ```

## 🤖 Configuration & Optimization
- **Set global username and email** *"Git me, maybe?"*  
    ```bash
    git config --global user.name "Your Name"
    git config --global user.email "your.email@example.com"
    ```

- **List all Git configurations** *"I have the power!"*  
    ```bash
    git config --list
    ```

---

### 🎯 Pro Tip: *"When in doubt, `git status` it out!"*

