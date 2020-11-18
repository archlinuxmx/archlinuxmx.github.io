# Contribuyendo al sitio de la comunidad Mexicana de Arch Linux

Antes que nada, gracias por considerar contribuir con Arch Linux México. Son las personas como tú las que hacen que Arch Linux México sea una comunidad tan genial.  

Te damos la bienvenida! Lee las siguientes secciones para saber cómo involucrarte en el desarrollo de este proyecto.

### ¿Para qué debería leer esta guía?
Seguir estas guías ayuda a comunicar que tú respetas el tiempo de las y los desarrolladores que están manejando y desarrollando este proyecto de codigo abierto. A cambio, ellas y ellos deberían de forma reciproca dirigirse a tu issue, revisar los cambios y ayudarte a finalizar tus pull requests.  

### ¿Qué tipo de contribuciones buscamos?  
**Arch Linux México** es una comunidad de Software Lire y de Código Abierto y nos encanta recibir contribuciones de nuestra comunidad, de tí! 

Hay muchas formas de contribuir, desde escribir tutoriales o publicaciones en blogs, mejorar la documentación, generar reportes de bugs y solicitudes de mejoras, participar en las salas de chat o escribir código que pueda ser incorporado en este sitio web como tal.  

**Por favor**, No uses el panel de issues para [preguntas de soporte]. 

En su lugar, únete el canal de IRC [#archlinux-mx](ircs://chat.freenode.net/archlinux-mx) en Freenode o en el [grupo de chat en Telegram](https://t.me/archlinux) y ahí te ayudaremos con tu issue. 


# Reglas principales
Responsabilidades  
* Asegurate de la compatibilidad entre versiones de [Hugo](https://gohugo.io/) para cada cambio en el que estarás trabajando.
* Crea issues para cualquier cambio mayor y mejora que desearias hacer. Discute las cosas de manera transparente y obtén los comentarios de la comunidad. 
* Manten el versionamiento de nuevas caracteristicas tan cortas como sea posible.  
* Se amable con las y los recién llegados y apoya la diversidad de nuevas y nuevos contribuidores de todo tipo de antecedente.


# Tu primera contribución
¿Aún no sabes cómo empezar a contribuir con Arch Linux México? 

Puedes empezar revisando los issues con etiquetas principiante (beginner), se-necesita-ayuda (help-wanted) y feature/mejora (enhancement):
* Beginner (principiante) - los issues con esta etiqueta deberían de requerir unicamente unas pocas lineas de código y uno o dos tests.

* Help wanted (se necesita ayuda) - Estos son issues que pueden ser un poco más complicados que los issues de principiantes.  
Ambas listas de issues están ordenadas por la cantidad de comentarios que tienen. Aunque no es perfecto, la cantidad de comentarios es un proxy rasonable para saber el impacto que tendrá el cambio.  

* Feature/mejora (enhancement) - Este tipo de issue nos ayuda a organizar el trabajo futuro o alguna mejora que se tenga que realizar.

### Recursos para quienes nunca han contribuido anteriormente en algún proyecto Open Source.  

* http://makeapullrequest.com/
* http://www.firsttimersonly.com/  

Trabajando en tu primer Pull Request? Puedes aprender como en esta *free* series, [Cómo contribuir a un proyecto de Código abierto en GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github).

En este punto, ya estas preparada o preparado para hacer cambios! Sientete libre de pedir ayuda; todos fuimos principiantes una vez :smile_cat:

Si un maintainer te pide que hagas un "rebase" al PR, ellos se refieren a que muchisimo código a cambiado y que deberías actualizar la rama para que sea más facil unirla al resto del código.

# Empezando

1. Crea tu propio fork del repositorio
2. Haz los cambios en tu fork
3. Si te gusta el cambio y crees que el proyecto podría utilizarlo:  
    * Envia un pull request

Pequeñas contribuciones como errores de ortografía, donde el contenido es lo suficientemente pequeño como para no considerado propiedad intelectual, puede ser agregado como un patch de contribuidor.  

Como regla de oro, los cambios pueden ser considerados "correcciones obvias" si estos no introducen una nueva funcionalidad o pensamiento creativo. Media vez el cambio no afecte la funcionalidad, algunos ejemplos incluyen los siguientes:  
* Correcciones de Ortografía / Gramática  
* Corrección de un error en la escritura de una palabra, espacios en blanco y cambios de formato  
* Limpieza de comentarios
* Corrección de Bugs que cambian los valores que se retornan o códigos de error guardados en constantes 
* Agregar mensajes de logueo o salidas de debugging
* Cambios a los archivos de ‘metadata’ como Gemfile, .gitignore, scripts de construcción, etc.
* Mover archivos con código de un directorio o paquete a otro  

# Cómo reportar un bug
Cuando llenas un issue, asegurate de responder estas cinco preguntas:

1. ¿Qué version de Hugo estas usando?
2. ¿Qué sistema operativo y que procesador estas usando?
3. ¿Qué hiciste?
4. ¿Qué esperabas ver?
5. ¿Qué viste en lugar de ello?

Preguntas generales deberían de ir en los grupos de chat (Telegram e IRC) en vez del issue tracker. La comunidad te indicará si es necesario abrir un issue cuando encuentres un bug.

# Cómo sugerir una nueva característica
Si te encuentras desdeando una característica que no existe en el sitio, probablemente no estas solo. Abre un issue en la lista de issues de GitHub que describa la característica que te gustaría ver, porqué la necesitas y como debería funcionar.

# Proceso de Revisión del código
Quién la revisa? Quien necesita firmar antes de que sea aceptada? Cuando debería esperar el contribuidor que le respondas? Cómo puede tener un contribuidor acceso a hacer commits, si fuese necesario?

El core team revisa los Pull Requests, luego de que se da la retroalimentación se esperan respuestas en las siguientes dos semanas. Luego de ello puede que se cierre el pull request debido a la inactividad.


# Comunidad
Puedes unirte a la comunidad en [Telegram](https://t.me/archlinuxmx) y en la sala de chat en IRC Freenode: [#archlinux-mx](ircs://chat.freenode.net/archlinux-mx)


# Mensajes de commit y etiquetado
Nos gustaría que seas descriptivo en el mensaje del commit usando el prefijo `feature` y `fix`. Un ejemplo podría ser:

```
feature: Add Arch Linux theme as git submodule
```

# Gracias por leer este documento
Ya que has llegado al final de este documento nos gustaría agradecerte por tomarte el tiempo de leerlo y con gusto estamos dispuestas y dispuestos a ayudarte.
Gracias!