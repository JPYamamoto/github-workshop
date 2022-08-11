`git rebase [remote]/[branch]` incorpora<br/>los cambios
que no tienes

<small>**no** olvides la `/`</small>

Note:
- why would you **not** use a merge to do this?
- rebase does not make a new commit
- bad idea to merge back into your same branch
    - makes your history ugly and hard to read
    - **will** frustrate you
- `git fetch` **first**
