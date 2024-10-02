> To make patch level changes
`git checkout -p branch-name -- file_on_branch_to_review.file`
- then
press `e` to make edits

> To make overwrite changes
`git checkout branch-name -- file_to_merge`
> then run `git add file_to_merge` and `git commit -m "overwrite file on main"`

`git diff main..branch-name -- file_to_review`

> remove a file from the stage
`git restore --staged <filename>`

> reset entire project to a previous commit `git reset --hard <commit-hash>`

> checkout a previous commit `git checkout <commit-hash>`

> show a file from a previous commit `git show <abc123>:path/to/file.txt`