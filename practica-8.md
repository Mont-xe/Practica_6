# CUESTIONARIO

### Responde las siguientes preguntas con tus propias palabras e incluye fragmentos de código en formato markdown.

###### a.	¿Cómo se inicializa un repositorio en Git?

Para inicializar un repositorio en Git se utiliza el comando 
``` git init ```

###### b. ¿Cómo creas un repositorio en GitHub?

Primero se inicia sesión en la cuenta de GitHub, luego clic en el botón "+" en la esquina superior derecha de la página, se completa la información requerida y despúes clic en "Create repository"

###### c. ¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?

Se crea con el comando ``` git remote add origin <URL del repositorio creado> ```

###### d. ¿Cuál es el flujo básico de trabajo en Git y GitHub?

El flujo básico es
``` 
git init (una vez)
git branch -m main (una vez)
git remote add origin <url del repositorio>
git add .
git commit -m "mensaje descriptivo"
git push -u origin main (una vez)
git push (para el resto de los cambios) 
```
##### e. ¿Para qué sirve el archivo .gitignore?

Se utiliza para especificar archivos y directorios que Git debe ignorar, lo que significa que no serán trackeados por Git ni incluidos en los commits

##### f. ¿Cuál es el propósito de una rama?

Es una línea independiente que permite trabajar en características nuevas de desarrollo sin afectar la rama main 

##### g. ¿Qué es una fusión?

Es el proceso de combinar los cambios de una rama con otra

##### h. Explica los diferentes tipos de fusión que existen.

Fusión estándar, la fusión recursiva (utilizada para fusionar ramas que tienen cambios de diferencias) y la fusión fast-forward (cuando no hay dif y se puede aplicar directamente)

##### i. ¿Cómo puedes ver el historial de tu repositorio?

Se pueden utilizar

``` 
git log
git status
git log --oneline
```
