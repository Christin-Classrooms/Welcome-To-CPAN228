# 🚀 Springbrook Web Dev: The Assignment Workflow

Follow these steps every time you start a new assignment to ensure your code is organized and you are following professional industry standards.

## Phase 1: Preparation

Before you start coding, ensure your local environment is up-to-date with the "source of truth."

### 1. Switch to Main
Ensure you are on the stable branch.

```bash
git checkout main
```

### 2. Sync with Cloud
Download any new changes from the teacher or teammates.

```bash
git pull origin main
```

## Phase 2: Development

Create a "sandbox" to work on your assignment without affecting the main project.

### 1. Create your Assignment Branch
Replace `name` with the specific assignment (e.g., `assignment-01`).

```bash
git checkout -b assignment-name
```

### 2. Code and Save
As you work, save "snapshots" of your progress often.

```bash
git add .
git commit -m "Added the header and styling for assignment 1"
```

## Phase 3: Syncing & Conflict Check

Before you finish, make sure your work still plays nice with the latest version of the `main` branch.

### 1. Merge Main into your Branch

```bash
git fetch origin
git merge main
```

If GitHub says "Already up to date," you are good to go!

## Phase 4: Submission (The Pull Request)

This is how you "turn in" your code for review.

### 1. Push to GitHub
Upload your branch to the cloud.

```bash
git push origin assignment-name
```

### 2. Open a Pull Request (PR)

- Navigate to your repository on GitHub.com.
- Click the green "Compare & pull request" button that appears at the top.
- Add a title and a brief description of what you completed.
- Click "Create pull request."