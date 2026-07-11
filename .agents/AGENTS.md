# Workspace Rules for Horizon

## Automatic Git Push Rule

Whenever the agent modifies files in this workspace, the agent MUST automatically commit the changes and push them to the remote repository.

### Requirements:
1. After completing file modifications, run `git status` and `git diff` to review the changes.
2. Run `git add <files>` for the modified files.
3. Commit with a meaningful, descriptive commit message explaining the changes:
   ```bash
   git commit -m "feat/fix/chore: <description of changes>"
   ```
4. Push the changes to the remote repository:
   ```bash
   git push origin <current-branch>
   ```
5. Do this automatically at the end of the modification step before finishing the turn or starting another task.
