# Git training basic

Contains the sheets used in the Git training for beginners. 

Purpose of the training is to get familiar with the basic commands of Git and to understand the basic concepts of Git. We do this in three steps:

Step 1: Provide background information about the history of Git and its motives.
Step 2: Explain the data model (commit / SHA / DAG) that Git uses.
Step 3: Explain the basic commands of Git.

- git init
- git add (with information about the index)
- git commit
- git status  
- explain .gitignore
- git reset
- git log
- gitk
- git diff
- git branch
- git checkout
- git merge
- git push  
The current branch is pushed to the corresponding upstream branch, but as a safety measure, the push is aborted if the upstream branch does not have the same name as the local one.

- git pull  
(Incorporates changes from a remote repository into the current branch. If the current branch is behind the remote, then by default it will fast-forward the current branch to match the remote. If the current branch and the remote have diverged, the user needs to specify how to reconcile the divergent branches with --rebase or --no-rebase (or the corresponding configuration option in pull.rebase).)  
Met voorbeelden demonstreren hoe zo'n git pull werkt namelijk door eventueel een merge te doen om de graphs passend op elkaar te krijgen.
