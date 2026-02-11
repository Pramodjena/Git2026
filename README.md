# Git2026

# All about Git and GitHub 

## Steps need to follow :

## Git installation :

## Stages :
- Untracked 
- Added or Staged 
- Committed 

## Commands you need to know :
- `git status -s` => to know current status of staged or unstaged files 
- `git log --oneline` => to know current status of saved points 


## Managing your own projects :
- Making git available in your projects 
- Making a check point or saved point 

        - Adding file 
        - Staging them 
        - Committing them 

## Going back some previous saved points 
        - Logging everything 
        - Reverting back to the previous saved points(git reset --hard HEAD~1)

## Git configuration :

- `git config --global user.name "Username"`
- `git config --global user.email "user@gmail.com"`

- `git config --global core.editor "code --wait" `(Default code editor)
- `git config --global core.autocrlf "input"` (Optimized line ending)
- `git config --global -e` (for edit)
- `git config --global --list `
- `git log --oneline --graph`
- `git branch` (Check all branch)
- `git branch feature/navbar `(create branch) * means we are in that branch
- `git switch feature/navbar`(to switch)
- `git switch -C feature/home` (create and switch)
- `git merge feature/navbar` (for merging with main)
- `git branch -d feature/navbar`(for delete) do it in live 
- Deleted branch feature/home (was 4aa9d23).

## Merging techniques :
- Fast forward merge 
- Three way merge 
- Squash merging 
- Recursive strategy merge 
- Rebase and merge 

## Stashing 

- `git stash `(for storing stash)
- `git stash apply` (for apply stash in any branch)
- `git stash clear` (to clear the stash)

- `git branch -d feature/navbar`(for delete)


## Collaboration :

### Common steps need to follow :
- Tl will create folder and initial files 
- Create a repo in github 
- Add collaborator 
- Clone that repo in your local machine 
- Create your own branch (vvvIP) before writing any code 
- Write your code in your branch only 
- Commit after completion 
- Inform to teammate after commit 
- Tl will fetch and merge then re-push 
- Tl `git fetch` then check the branch using `git branch`
- Branches will show you up 
- Then switch to that branch 
- Then if code is fine and correct then merge it with main branch (`git merge`) 
- Then team-mates switch to main branch(`git switch main`) then `git fetch` then `git pull`or directly `git pull`