**Similar a un correo electrónico**

```txt
fix: discrepancia entre `theorem` y `example`

Cuando el tipo de un `example` es una proposición, deberíamos
expandirlos como hacemos con los teoremas. Esto es de particular
importancia para ejemplos que utilizados en material educativo.

...

La motivación es que la prueba de un teorema no debe influir en
cómo se enuncia. Sin embargo, antes de este commit, este no era el
caso para los ejemplos cuando su tipo era una proposición.
Esta discrepancia solía confundir a los usuarios.

...

Resuelve el error #4398
```

<small class="fragment">Commit <a href="https://github.com/leanprover/lean4/commit/e3578c2f36c2d4fa9cc55584a7671c0c81c70ed9">e3578c2</a> con autoría de <a href="https://github.com/leodemoura">@leomoura</a></small>

Note:

-   1st line is like an email _subject_
-   rest is like an email _body_
-   Fun fact, `git` supports sending changes by email
    -   where this convention comes from
    -   how `git` and the Linux kernel are still worked on
