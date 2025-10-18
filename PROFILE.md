## FreeCodeCamp - [Git for Professionals Tutorial - Tools & Concepts for Mastering Version Control with Git](https://www.youtube.com/watch?v=Uszj_k0DGsg)
- **How to write the perfect commit**: Write a good header and message, and make sure that the commit isn't too big. We need to break down commits into smaller parts so that each commit is only really doing one change or fix. This makes it so that it is easier for others or yourself to see in the future and understand what was changed each time, rather than having to read through a large change. If there is a large change, you can stage commits so that not everything is not committed at once.
- **Branching Strategies**: This needs to be created and followed by the team working on the project. For example, it could be of a mainline development format where there will be very few branches, and each branch is integrated into the main branch as the work gets completed. Or you could have different types of branches like state, release, and feature branches.
- **Pull Requests**: PRs are used to merge these branches into the main development branch. Other people can review your PR and see if there's anything wrong, conflicting, or anything that could potentially break the code. This is commonly used in open-source repositories since it makes it so that no one can just randomly merge their branches in a public open-source project. Instead, people can make pull requests and then one of the main contributors can review and agree to push your changes.
- **Merge Conflicts**: There are times where Git doesn't know which conflicting code to keep or discard; so it has to ask humans to pick which version to use. If the same line is edited in both the branches, or there are some other conflicts, Git will not know what to do, so human intervention is required here. Git marks the problem areas so it's easier to see.
- **Merge vs. Rebase**: When merging two branches, Git looks to merge 3 different commits - last common commit, and latest commits of both the branches. Git then creates a new merge commit that actually does the merging and wraps all the changes into it. The difference in rebasing is that it will take the latest commit of one of the branches and merge it with the main branch, then take the latest commit of the other branch and try to merge it with main.  

<hr>

## Corey Schafer - [Git Tutorial for Beginners: Command-Line Fundamentals](https://www.youtube.com/watch?v=HVsySz-h9r4)
- How to install Git and set global config variables.
- How to initialize a repository from existing local code.
- .git and .gitignore files.
- Working directory: All the files in the codebase directory.
- Staging Area: Organize what needs to be committed here. Can commit large file changes in small chunks.
- How to clone an existing repository, create branches, commit files (locally), and push changes (to the repository). TO push changes:
  - commit and push your branch
  - checkout to master branch
  - pull all changes from origin master
  - run `git merge <branch>` to merge your branch into master
  - push origin master to the repository
 
<hr>

## Max Rohowsky - [Using Git & GitHub in VSCode: Stage, Commit, and Push](https://www.youtube.com/watch?v=z5jZ9lrSpqk)
- **Git vs GitHub**: Git is just a verison control system, GitHub is a hub for Git repositories.
- Initialize a repository in VSCode.
- Once you create files/make changes, Source Control tab shows that you have uncommitted changes. You can see the changes you've made and you can commit these changes and add a message.
- Then we can publish the branch (may need to authorize and log into GitHub online first).
- If changes are made locally, we can push them so it reflects in the repository. If changes are made directly in the repository, then just pull the branch locally and can see the changes in VSCode.
- Can also stage changes in VSCode.

