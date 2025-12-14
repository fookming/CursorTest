# CursorTest
Cursor Test
This is to add another line
Hello World

## Troubleshooting

If pushes to GitHub appear to do nothing, check that a remote is configured. Run `git remote -v`; if no entries appear, add the GitHub URL (for example `git remote add origin https://github.com/USER/REPO.git`) before pushing.

### Current repository status
`git remote -v` currently shows no entries, which means this repository has no GitHub remote configured yet. To push changes, add your repository URL as a remote, for example:

```
git remote add origin https://github.com/USER/REPO.git
git push -u origin work
```
