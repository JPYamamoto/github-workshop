Ambas ramas cambiaron **las mismas** líneas

```md
# README: This is a practice `git` repository

<<<<<<< HEAD
I added this change in master, no conflicts here!
=======
I added this change in conflict, this is a conflict!
>>>>>>> conflict

```

<small>`git` nos ayuda a visualizar conflictos</small>

Note:
`git` **does not** presume which changes are right
`git` visualizes the merge conflicts
- HEAD is your current branch
- equal signs separate the two groups of 
- the greater-than signs indicate the target where the conflict came from
