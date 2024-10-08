# DataDiveFa24

## Steps When Logging On

1. **Check Current Branch**
   - Determine which branch you are currently on:
     ```bash
     git branch  # or use git status
     ```

2. **Switch to Main Branch**
   - If you're not on the `main` branch, switch to it:
     ```bash
     git checkout main
     ```

3. **Pull Latest Changes**
   - Fetch and merge the latest changes from the remote `main` branch:
     ```bash
     git pull origin main
     ```

4. **Switch to Your Branch**
   - Now, switch back to your working branch:
     ```bash
     git checkout <branch-name>
     ```

5. **Merge Changes into Your Branch**
   - Merge any changes from `main` into your branch:
     ```bash
     git merge main
     ```

## Make Your Changes
- Edit your files in your code editor as needed.

## Check Status
- Before committing, check the status of your changes:
  ```bash
  git status
  ```

## Stage Changes
- Stage files you want to commit:
  ```bash
  git add <file_name> # or git add -A to add all changes
  ```
- Commit changes:
  ```bash
  git commit -m "Add a detailed message of your changes here"
  ```
- Push your changes:
  ```bash
  git push
  ```

  ## Pull Request Process

- When making a pull request, be sure to:

  1. Ensure your branch is up to date with the `main` branch.

  2. Add detailed information about the changes you've made.

  3. **Add Isaac as a reviewer to the pull request.**
  
  4. I'll approve it or make comments and have you keep working on your feature.