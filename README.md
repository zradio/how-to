# Tutorial

Aqui encontrareis toda la informacion para empezar a trabajar en la web de ZRadio. 

Si teneis alguna pregunta o alguna duda, no dudeis en preguntarla aqui: [https://github.com/zradio/how-to/issues](https://github.com/zradio/how-to/issues).

## Cuenta GitHub

Si podeis leer esto, significa que ya teneis una cuenta GitHub y que ya sois miembros de la organizacion ZRadio. Si no es el caso, por favor de crear una cuenta en [GitHub](https://github.com) y de enviar vuestro nombre de usuario en el grupo Whatsapp "Web Radio".

GitHub esta basado en el programa `git`, que permite, entre otras cosas, colaborar entre programadores y guardar un historial de todas las modificaciones (un poco como Google Drive, pero especialmente pensado para la programacion). Si algun dia quereis trabajar en informatica, teneis que saber usar `git` (o cualquier equivalente como Mercurial)!

## Instalar Git

Lo primero que teneis que hacer es instalar `git`: [https://git-scm.com/downloads](https://git-scm.com/downloads). 
Podeis verificar que `git` esta bien instalado abriendo una terminal (en Windows es `cmd`, en macOS puede ser cualquier aplicacion de terminal como Terminal o iTerm, y en Linux ... pues si teneis Linux ya sabeis lo que es un terminal!) y entrar lo siguiente:
```
$ git --version
```
(sin el simbolo '$', eso solo significa que tiene que ser en una terminal!)

Si la terminal os responde algo como `git version 2.7.4 (Apple Git-66)` es que todo esta bien! :)

`git` es muy interesante y bastante complejo, pero si quereis aprender un poco mas de lo que voy a explicar, podeis leer el guia siguiente (que ademas esta en Español!): [https://git-scm.com/book/es/v1](https://git-scm.com/book/es/v1)

## Instalar un editor de texto

Como buenos programadores, vamos a usar editores de textos (de preferencia libres y/o gratuitos) que no sean el Bloc Note ...
Hay varias posibilidades en el mercado, pero personalmente os recomiendo cualquira de los siguientes:
- [Sublime Text](https://www.sublimetext.com/)
- [VS Code](https://code.visualstudio.com/)
- [Atom](https://atom.io/)

## Usar GitHub

Experimentar al maximo, no hay nada que este mal, y no hay nada que no se pueda deshacer!

### Crear un nuevo repositorio

Lo ideal para entrenaros seria que crearais un repositorio en vuestra cuenta GitHub. Para eso, clicar en el signo '+' en la pantalla arriba a la derecha, y seleccionar 'New Repository'. Ahi, elegir un nombre para vuestro nuevo repositorio.

Si quereis que GitHub cree una pagina web estatica desde un repositorio, elegire el nombre siguiente: `<nombre-de-usuario>.github.io`. Por ejemplo, si mi nombre de usuario es AntonioVdlC, crearia un repositorio con el nombre `antoniovdlc.github.io`. Vuestra pagina web estara accesible en `antoniovdlc.github.io` simpre y cuando tenga un fichero `index.html` valido.

Una vez el repositorio creado, podeis clonarlo a vuestro ordenador (en el que ya esta instalado `git`) siguiendo las instrucciones en la pantalla y añadir cuantos ficheros os guste.

### Contribuir codigo en GitHub

Para contribuir codigo en GitHub, simplemente crear un dosier en vuestro ordenador, initializar `git` desde una terminal llendo al dosier que habeis creado (unsando `$ cd <direcion-absoluta-del-dosier>`) y entrando `$ git init`. Ahora podeis editar ficheros con vuestro editor de texto. Cuando querais salvar vuestros cambios, simplemente usar `$ git add -A` y luego `$ git commit -m "<description-de-los-cambios>"`.

Para subir vuestras modificaciones a GitHub, primero teneis que decir a `git` cual es vuestro repositorio usando `$ git remote add origin https://github.com/<nombre-usuario>/<nombre-repositorio>.git`. Una vez el repositorio configurado, simplemente usar `$ git push -u origin master` la primer vez que se contribuye codigo al dicho repositorio, y luego simplemente `$ git push` cada vez que hayas hecho cambios (y `commit`eado esos cambios).

> Si ya teneis codigo que os gustario subir a GitHub, hacer lo siguiente
- Abrir una terminal y navegar hasta el dosier en donde esta el codigo (usando `$ cd <direcion-absoluta-del-dosier>`).
- Initializar `git` usando `$ git init`.
- Añadir los ficheros y hacer un commit (`$ git add -A` y luego `$ git commit -m "Initial commit"`).
- Añadir vuestro repositorio GitHub `$ git remote add origin https://github.com/<nombre-usuario>/<nombre-usuario>.github.io.git`.
- Subir los cambios a GitHub con `$ git push -u origin master` (puede que os pida introducir vuestra contraseña).
- Ahora podeis ver los ficheros en vuestra cuenta GitHub, y si habeis llamado vuestro repositorio `<nombre-de-usuario>.github.io` y teneis un fichero `index.html` valido, podeis ver vuestra pagina web on-line! 

Si quereis aberiguar mas sobre GitHub, os invito a leer los diferentes guias oficiales o ver la videos oficiales (en Ingles) aqui: [https://guides.github.com/](https://guides.github.com/). 

Tambien podeis preguntarme cualquier cosa! :)
