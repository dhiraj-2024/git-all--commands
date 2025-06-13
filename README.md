# 🚀 Git Command Guide (Mac & Windows)  

A quick reference for **cloning, pushing, and managing Git repositories** in VS Code Terminal.  

---

## 📥 1. Clone a Repository  
```bash  
git clone https://github.com/username/repository-name.git

``` 
## 📂 2. Open Project in VS Code

```bash
cd repository-name  
code .  
```
## 🌿 3. Branch Management

-- Create & switch to a new branch (e.g., git checkout -b john-feature)
```bash
git checkout -b branch-name
```
-- List all branches
```bash
git branch	
```
-- Switch back to main branch
```bash
git checkout main
```

## ✏️ 4. Make Changes & Track Progress
```bash
# Check modified files  
git status  

# Stage all changes  
git add .  

# Commit changes  
git commit -m "Describe your changes here"  

```

## 📤 5. Push to GitHub
```bash
# Push your branch (first time)  
git push -u origin branch-name  

# Subsequent pushes  
git push  

```

## 🔄 6. Sync with Main Branch
```bash
# Pull latest changes from main  
git checkout main  
git pull origin main  

# Update your branch with main  
git checkout branch-name  
git merge main  

```
## 🛠 7. Resolve Merge Conflicts

-- Open conflicted files in VS Code.

-- Accept incoming (remote) or current (local) changes.

-- Save, then commit:

```bash
git add .  
git commit -m "Resolved merge conflicts"  
```




