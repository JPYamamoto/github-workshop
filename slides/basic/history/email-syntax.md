**Similar a un correo electrónico**

```txt
Permite la descarga de arhivos Markdown

Anteriormente el sistema sólo permitía la descarga de 
las tarjetas como archivos PDF. Debido a la necesidad 
de los usuarios de compartir notas, era necesario 
permitir la descarga de estas como archivos Markdown.

Para lograrlo, construimos un archivo de texto en memoria,
lo entregamos por el servidor HTTP, y desechamos el objeto
una vez servida la solicitud.
```

Note:
- 1st line is like an email _subject_
- rest is like an email _body_
- Fun fact, `git` supports sending changes by email
    - where this convention comes from
    - how `git` and the Linux kernel are still worked on
