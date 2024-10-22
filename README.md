# __git-tutorials__


a tutorial for demonstrating git usage and lecturing.


first exercise (stage 1):
    1. fork origin repository to my account
    2. git clone myself repository to local
    3. fix something on local file
    4. sumbit changes
    5. push the changes to my github repository
    6. pull request

# audience

* university students
* fresh graduated 

LET ME COMMIT.hahaha


discard original codes to comply with the newest version


## What is Git?
Git is a distributed version control system designed to track changes in source code during software development. It is primarily used for coordinating work among programmers, but it can also be used to track changes in any set of files.   

## Why use Git?
- **Tracking changes:** Keep a history of all changes made to your code.
- **Collaboration:** Work on projects with multiple people simultaneously.
- **Branching:** Create different versions of your project to experiment or work on different features.
- **Reverting:** Easily revert to a previous version of your code.

## Basic Commands
**Initialize a Git repository:**
## bash
```
git init
```

**Add a file to staging:**
```
git add <filename>
```

**Commit changes:**
```
git commit -m "Your commit message"
```

**Check status:**
```
git status
```

**View commit history:**
```
git log
```

**Branching:**
```
git branch <branch-name>  # Create a new branch
git checkout <branch-name>  # Switch to a branch
git merge <branch-name>  # Merge a branch into the current branch
```

**Remote repositories:**
```
git remote add origin <remote-url>  # Add a remote repository
git push origin <branch-name>  # Push changes to the remote
git pull origin <branch-name>  # Pull changes from the remote
```
**Additional Commands**
```git clone <url>```: Clone an existing repository.
```git diff```: Show the difference between commits, commit and working tree, etc.
```git reset --hard <commit-hash>```: Reset your current HEAD to the specified commit.
```git branch -d <branch-name>```: Delete a branch.

## Advanced Topics
- .gitignore: Specify intentionally untracked files.
- Tags: Mark specific points in the project history.
- Stashing: Temporarily save uncommitted changes.

## Best Practices
- Write clear and concise commit messages.
- Commit frequently.
- Use branches effectively.
- Leverage features like git rebase and git cherry-pick for more advanced workflows.

## Example Workflow
1. Clone a repository.
2. Create a new branch for your feature.
3. Make changes and commit them.
4. Push your changes to the remote branch.
5. Create a pull request to merge your changes into the main branch.

## Remember:

- Git is powerful. Use it to your advantage.
- Practice makes perfect. The more you use Git, the more comfortable you'll become.
- There's always more to learn. Explore the vast resources available online.
- Need more help? Feel free to ask!

