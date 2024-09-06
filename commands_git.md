# Commands from Git


### Basic routine for commiting

That is how I save a snapshot/point
add files that you want to comit together.
```
git add <name of the file 1> <name of the file 2>
git commit -m "meaningful message"
```



### How to check the status of my files or directories in my git project

check if they are uncommited, unstaged, or untracked

`git status`

If you restore, you will delete your changes!!!

### How to know the timeline of commits and compare them
- check the timeline of commits
`git log   `
- check the last 5 commits
`git log -n 5` or `git log -5`
- check the short ID of the last 6 commits
`git log -n 5 --abbrev-commit`
- compare commit A and commit B
`git diff <commit ID A> <commit ID B>`
`git show <commit ID A> <commit ID B>`

From Marvelous: git is hard

I want to revert this...
