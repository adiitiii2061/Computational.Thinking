# Computational.Thinking
# Identity Investigation

This project shows Python id() and Git commit immutability.

Author: Aditi Meena

## Nested List Observation

After copying the list using list(), both original and copied list changed.
This is because list() creates a shallow copy.

Inner lists are shared, so modifying one affects the other.

## Commit Immutability

When I used git commit --amend, Git did not modify the old commit.
Instead, it created a new commit with a new hash.

This shows that commits in Git are immutable.


