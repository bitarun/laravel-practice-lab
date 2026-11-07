# laravel-practice-lab



A practice repository for Laravel exercises.

Each exercise lives on its own branch.



\## Git cheatsheet



1\) `git revert <commit>` creates a new commit that undoes the changes of that commit only. The old commit stays in history, so it is safe on shared branches.

\- `git reset <commit>` moves the branch back to that commit, so the later commits are removed from the branch history. It rewrites history, so use it only on local commits that are not pushed.

2\) By default, `reset` keeps your files unchanged. With `--hard`, it also changes the files and discards uncommitted work.

