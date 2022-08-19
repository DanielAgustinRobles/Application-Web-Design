
   ## Información de la actividad 1 en Markdown
   
   |  | Mi información |
   | ------ | ------ |
   | Nombre | Daniel Agustín Robles Ávila |
   | Matrícula | AL02918254 |
   | Carrera | Ingeniería en Desarrollo de Software |
   | Semestre | Octavo semestre |
   
   |  | Información de la materia |
   | ------ | ------ |
   | Nombre de la materia | Diseño de aplicaciones web |
   | Profesor | Carlos Ignacio Hernández Nolasco |
   
   ### *¿Para qué se usa Markdown?*
   Markdown es un lenuaje de marccado que facilita la aplicación de formato a un texto empleando una serie de carácteres de una forma especial. Al principio se pensó para elaborar textos que eran destinados a páginas web, pero actualmente también se puede utilizar para cualquier tipo de texto.En pocas palabras, Markdown es normalmente utilizado para convertir el lenguaje en HTML válido para texto en páginas web.
   
   ## Algunas etiquetas que se usan en Markdown son las siguientes
   
   Encabezados: 
   # Encabezado nivel 1
   
   ## Encabezado nivel 2
   
   ## Encabezado nivel 3
   ...
   ###### Encabezado nivel 6
   
   Encabezados alternativos:
   
   Heading level 1
   ===============
   
   Heading level 2 
   ---------------
   
   Enfasis (Bold e Italic):
   Este es un **texto en Bold**
   Este es _un texto en Italic_.
   Este es un ***texto en Bold e Italic***.
   Este es otro ___texto en Bold e Italic___.
   
   Bloques de citas de texto.
   > Dorothy la siguió por los muchos cuartos del castillo.
   
   Listas ordenadas:
   1. Primer objeto.
   2. Segundo objeto.
   3. Tercer objeto.
        1. Indentación uno.
        2. Indentacion dos.
    4. Cuarto objeto.

Listas desordenadas:
- Primer objeto 
- Segundo Objeto
* Tercer objeto.
+ Cuarto objeto.

Para colocar imagenes se hace lo siguiente:
![The San Juan Mountains are beautiful!](/assets/images/san-juan-mountains.jpg "San Juan Mountains")
Siempre y cuando la imagen se encuentro en la carpeta especificada dentro de nuestra computadora.

## Comandos de Git:
1. Ver el estado de un repositorio local.
> "git Status" es el comando que nos da información del repositorio local y de la "branch" en la que estemos trabajando.
2. Añadir archivos individualmente o en conjunto (globally).
> El comando "git add <archivo>" añade un unico archivo al repositorio. El comando "git add -A" añade todos los archivos de una vez.
3. Añadir comentarios al commit.
> "git commit -m "mensaje de confirmación" añade un comentario sobre el por qué se hizo el commit o por qué se hizo ese guardado.
4. Subir los cambios al repositorio remoto.
> "git push <nombre-remoto> <nombre-de-tu-rama>" envía los cambios al repositorio una vez que se han confirmado los cambios con un commit.
5. Crear, buscar o borrar branches.
> "git branch" es el comando que enumara las ramas del repositorio para buscar uno en especifico. "git branch <branch>" es el comando para crear una branch con el nombre indicado dentro de los simbolos <>. "git branch -d <branch>" elimina la branch especificada dentro de los simbolos <>.
6. Regresar el repositorio a un commit especifico.
> "git revert" es el comando para revertir un commit especifico, pero primero hay que ver el historial de commits con el comando "git log --oneline" y ese nos dará el histórico de commits en la rama pricipal. Entoces solo necesitamos especificar el código de comprobación que encontrarás junto al commit que queremos deshacer, por ejemplo: git revert 3321844. El comando git revert deshará el commit que le hemos indicado, pero creará un nuevo commit deshaciendo la anterior. La ventaja de utilizar git revert es que no afecta al commit histórico. Esto significa que puedes seguir viendo todos los commits en tu histórico, incluso los revertidos.Otra medida de seguridad es que todo sucede en local a no ser que los enviemos al repositorio remoto. Por esto es que git revert es más seguro de usar y es la manera preferida para deshacer los commits.