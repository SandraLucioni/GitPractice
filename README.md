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
- Conflicto al no hacer pull. **Resuelto, al hacer pull VCS te da la opción de aceptar todos los cambios o los anteriores o los que se acaban de guardar**
- Aceptar todos los cambios.
- Git commit and pull.

### Día dos
#### Carpeta Instituto

![imagen de código donde se hicieron cambios en el mismo párrafo sin hacer push en carpeta casa](GitPractice\imagenes\conflicto_mismo_párrafo.png)

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
 - Eliminé una condición de _CSS_.
 - Git commit and push.
