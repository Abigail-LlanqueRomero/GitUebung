# Git Branches

Branches in Git allow you to create separate lines of development within a repository. This is especially useful when working on new features, bug fixes, or experiments without affecting the main codebase. The default branch in most repositories is called `main`.

By using branches, you can work independently and later merge your changes back into the main branch or other branches.

## How to Use Branches

Here are commands for working with branches in Git:

```bash
# List all branches in the repository
git branch

# Create a new branch
git branch <branch-name>

# Switch to a different branch
git checkout <branch-name>

# Create a new branch and switch to it
git checkout -b <branch-name>

# Merge changes from one branch into the current branch
git merge <branch-name>

# Delete a branch
git branch -d <branch-name>
```

## Branching Workflow

A common workflow involves creating a new branch for each feature or bug fix. Once the work is complete, you merge the branch back into main. This helps keep the main codebase stable and allows for smoother integration.

You can also create multiple branches for different tasks, such as:
- **Feature branches**: Used for developing new features.
- **Bugfix branches**: For fixing specific bugs.
- **Release branches**: For preparing the codebase for a new release.
- **Hotfix branches**: Used for emergency fixes to the production code.

After finishing the task on a branch, it’s common to create a pull request (PR) to merge the branch into main. This ensures the changes are reviewed before being merged.

## Visualizing Git Branches

![Git Branches](https://i2.wp.com/digitalvarys.com/wp-content/uploads/2019/06/GIT-Branchand-its-Operations.png?fit=1921%2C1057&ssl=1)

[Video: What Are Git Branches?](https://youtu.be/Q1kHG842HoI)

## Best Practices for Using Branches

1. **Keep branches focused**: Each branch should represent a single purpose (e.g., a feature, a bug fix, etc.).
2. **Regularly update your branches**: If the main branch gets updated, it's a good practice to merge those updates into your feature branches.
3. **Delete unused branches**: Once a branch has been merged, delete it to keep the repository clean.
4. **Use descriptive names for branches**: Naming branches clearly helps others understand the purpose of the branch. For example, use feature/login-form or bugfix/fix-header.

