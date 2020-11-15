# GitPractice
Repository where we will learn about how to use GitHub

 - crear nuevo repositorio
 - git clone en ***carpetaCasa*** y ***carpetaInstituto***.
 - crear documento _.html_ y _.css_ en ***carpetaCasa***.
 - Git commit and push.
 - Error al subir contenido sin guardar antes en cada ventana. Actualizado.

#### Carpeta Instituto
- Imagen añadida y centrada.
- Git commit and push.

#### Carpeta Instituto
- Añadido Enlace a _w3schools_ .
- Git commit and push.

#### Carpeta Casa
- añadido fieldset y centrado.
- Git commit

#### Carpeta Instituto
- Conflicto al no hacer pull. **Resuelto, al hacer pull VSC te da la opción de aceptar todos los cambios o los anteriores o los que se acaban de guardar**
- Aceptar todos los cambios.
- Git commit and pull.

### Día dos
#### Carpeta Instituto

![imagen de código donde se hicieron cambios en el mismo párrafo sin hacer push en carpeta casa](https://github.com/SandraLucioni/GitPractice/blob/main/imagenes/conflicto_contenido_por_nopull.png)

- Git pull después de que Git avisara del error.
- Aceptar todos los cambios.
- Save, Git add . , commit and push.

    ```
    PS D:\Sandra\carpetaInstituto\GitPractice> git add .
    PS D:\Sandra\carpetaInstituto\GitPractice> git status
    On branch main
    Your branch and 'origin/main' have diverged,
    and have 3 and 4 different commits each, respectively.
    (use "git pull" to merge the remote branch into yours)
    All conflicts fixed but you are still merging.
    (use "git commit" to conclude merge)

    Changes to be committed:

            modified:   README.md
            modified:   ejercicio.html

    PS D:\Sandra\carpetaInstituto\GitPractice> git add .       
    PS D:\Sandra\carpetaInstituto\GitPractice> git status
    On branch main
    Your branch and 'origin/main' have diverged,
    and have 3 and 4 different commits each, respectively.
    (use "git pull" to merge the remote branch into yours)
    All conflicts fixed but you are still merging.
    (use "git commit" to conclude merge)

    Changes to be committed:

            modified:   README.md
            modified:   ejercicio.html
            new file:   "imagenes/conflicto_mismo_p\303\241rrafo.png"

    ```

 _No hace falta hacer Git merge porque el VSC te lo facilita bastante con las opciones que aparecen encima de los cambios señalados en el código._

 #### Carpeta Casa
 - Git pull
 - Eliminé una condición de _.css_ .
 - Git commit and push.
 #### Carpeta Instituto
 - Conflicto al cambiar una condición de _.css_ sin hacer pull previamente.
 - Al hacer Git pull después de dar error, VSC nos da la posibidad de quedarnos con los cambios guardados en el repositorio o combinar ambos, en este caso la condición de _.css_ seguiría pero con el cambio que pedía. Como soy yo el máster elegí la opción que dejé antes; condición eliminada.

![Imágen del código después de hacer pull posterior al error](https://github.com/SandraLucioni/GitPractice/blob/main/imagenes/conflicto_cambio_en_la_misma_linea_pero_distinto_contenido.png)

![Imágen del código después de hacer pull posterior al error](https://github.com/SandraLucioni/GitPractice/blob/main/imagenes/conflicto_mismo_parrafo.png)

 _No tengo necesidad de hacer de forma manual git merge porque al estar en la misma rama se hace automáticamnte. En el caso de que estuviera trabajando en ramas, sí. Por eso en las capturas aparece **git merge** en el terminal, porque al principio no entendía cuando debía usarlo._
  
 - Git add ., commit and push.
