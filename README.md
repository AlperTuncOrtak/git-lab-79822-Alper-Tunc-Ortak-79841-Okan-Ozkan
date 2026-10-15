# Git Lab - Alper and Okan Collaboration

## Team

| Student ID | Name | GitHub |
|---|---|---|
| 79822 | Alper Tunç Ortak | @AlperTuncOrtak |
| 79841 | Okan Özkan | @the0kan |

## Okan

Okan's contribution.


## What We Practiced

| PR | Author | Reviewed & merged by | What it covered |
|---|---|---|---|
| #1 | Alper | Okan | Team table; first merge conflict, resolved with `git merge main` |
| #3 | Okan | Alper | Okan's first contribution |
| #4 | Alper | Okan | README title change (setup for the second conflict) |
| #5 | Okan | Alper | Second merge conflict, resolved with `git rebase origin/main` |

- **Repository setup:** Shared repository with both members as collaborators. `main` is protected by a ruleset that requires a pull request and one approval before merging.
- **Branching workflow:** Each change was made on its own branch, committed, pushed, and fetched/pulled by the other member.
- **Pull requests and reviews:** Every PR had a requested reviewer, line comments, and an approval before merging. Issue #2 was linked with `Closes #2` and closed automatically on merge.
- **Merge vs. rebase:** The first conflict was resolved with a merge, which kept both histories and created a merge commit. The second was resolved with a rebase and `git push --force-with-lease`, which kept the branch history linear.
- **Cleanup:** Merged branches were deleted locally and on GitHub (`git branch -d`, `git push origin --delete`, `git fetch --prune`).
- **Learn Git Branching:** Both members completed exercises on [learngitbranching.js.org](https://learngitbranching.js.org/) and reproduced the commands in this repository.
