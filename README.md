# 👥 Masai Group Collab – Contribution Guide

Welcome to the Masai Group Collab Team Repository!  
This is where we **solve problems**, **share logic**, and **learn together** 💻💡

---

## ✅ Prerequisites

Make sure you have:

- Git installed → [Download Git](https://git-scm.com/)
- A GitHub account
- VS Code (or any code editor)

---

## 🚀 How to Contribute (Step-by-Step)

### 1. Clone the Repo

Open terminal and run (better run in desktop directory i,e ~/Desktop/): 

```bash
git clone https://github.com/Govind-ravi/MasaiGroupCollab.git
```
```bash
cd MasaiGroupCollab
```

### 2️. Create a New Branch (don't work in main)
```bash
git branch your-branch-name
```
Example: git branch Alice

### 3. Switch to the branch created
```bash
git checkout your-branch-name
```
Example: git checkout Alice

### 4. Add Your Code
- Create a folder/file based on the problem you're solving.
- Let the name be meaningful, for e.g. reverseString.js
- Write your code, add proper comments to make sure other readable.
- Write your solution to existing files and comment your name saying you solved.

### 5. Stage and Commit the Changes
```bash
git add .
```
```bash
git commit -m "Added reverse string question"
```
Let the commit message be meaning full specifying added or solved
For e.g. Added reverse string question, or Solved reverse string question

### 6. Push to GitHub
```bash
git push origin your-branch-name
```

### 7. Create a Pull Request
- Go to: https://github.com/Govind-ravi/MasaiGroupCollab
- You’ll see a button saying “Compare & Pull Request”
- Add a message → click Create Pull Request

---

## 🔁 Next Time Before Starting:
Always pull latest code:
```bash
git checkout main
```
```bash
git pull origin main
```
Then again create a new branch and follow the steps from step 3 👆
