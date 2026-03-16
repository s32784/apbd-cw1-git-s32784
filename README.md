•	1. When does Git perform a fast-forward and when is a merge commit created? 
Git performs a fast-forward merge when the branches have not diverged, creating a linear history. 
A merge commit is created when the histories of the branches have diverged, explicitly joining the two lines of development
•	2. What is the practical difference between merge and rebase?
Git merge and rebase integrate changes, but merge preserves complete, chronological history with a new "merge commit", 
rebase rewrites history to create a clean, linear, non-branching timeline. 
Merge is safer for shared branches, rebase is better for maintaining a tidy, readable feature branch history. 
•	3. How was the conflict resolved in your repository?
By choosing one between two posiible variants of our code that we created.  
