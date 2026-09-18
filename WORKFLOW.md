# Git Team Sync Workflow

## 1. Why was the push rejected, and what did the error mean?

The push was rejected because the remote feature branch contained commits that were not present in my local branch. Git rejected the push because updating the remote would have caused a non-fast-forward update and could overwrite other work.

## 2. What was the actual difference between merge and rebase?

A merge combines two lines of development by creating a merge commit with both histories as parents. A rebase moves my local commits on top of the updated remote branch, creating a more linear history. In this activity, I used merge in Clone B and rebase in Clone A.

## 3. What one habit would avoid both rejected pushes?

I would regularly fetch the remote branch before starting new work or pushing changes. This helps me know whether other commits have been added to the shared branch.

## 4. Which approach would you default to on a shared team branch, and why?

I would generally use merge when integrating changes on a shared team branch because it preserves the existing commit history and does not rewrite commits that other team members may already have.
