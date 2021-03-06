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

![imagen de código donde se hicieron cambios en el mismo párrafo sin hacer push en carpeta casa](https://github.com/SandraLucioni/GitPractice/blob/main/imagenes/conflicto_mismo_parrafo.png)

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

![Imágen del código después de hacer pull posterior al error](https://github.com/SandraLucioni/GitPractice/blob/main/imagenes/conflicto_contenido_por_nopull.png)

![Imágen del código con conflicto en el mismo párrafo](https://github.com/SandraLucioni/GitPractice/blob/main/imagenes/conflicto_cambio_en_la_misma_linea_pero_distinto_contenido.png)

 _No tengo necesidad de hacer de forma manual git merge porque al estar en la misma rama se hace automáticamnte. En el caso de que estuviera trabajando en ramas, sí. Por eso en las capturas aparece **git merge** en el terminal, porque al principio no entendía cuando debía usarlo._
  
 - Git add ., commit and push.

--

### Práctica p02-40, git tags
 - En Carpeta Casa cree un tag V1.2.
 - En Carpeta Casa abrí mi primer commit "Initial commit" donde perdí todo el trabajo realizado.
 - En carpeta Instituto abrí el tag V1.2 donde recuperé el proyecto.


 ![Imagen del código con el tag hecho](https://github.com/SandraLucioni/GitPractice/blob/main/imagenes/codigo_tag.png)

 ![Imagen del código regresando al primer commit](https://github.com/SandraLucioni/GitPractice/blob/main/imagenes/git_push_after_tag.png)

### Práctica 02-50

#### Carpeta Casa
- crear rama con nombre _firstbranch_.
- Realizar cambios, hacer commit and push.

![Imagen del código despúes de haber creado la rama y haberlo subido a CarpetaInstituto](https://github.com/SandraLucioni/GitPractice/blob/main/imagenes/changes_carpetainstituto_branch.png)
 
#### Carpeta Instituto
- Hacer pull y cambiar a rama _firstbranch_.
- Realizar cambios, hacer commit and push.
- Cambiar de branch y unir (**merge**) la rama _firstbranch_ con _main_.

![Imagen del código haciendo el cambio de la branch a main](https://github.com/SandraLucioni/GitPractice/blob/main/imagenes/cambio_a_main.png)
![Merge](https://github.com/SandraLucioni/GitPractice/blob/main/imagenes/merge.png)
![Conflicto en merge](https://github.com/SandraLucioni/GitPractice/blob/main/imagenes/conflict_merge.png)
![Lista commits](https://github.com/SandraLucioni/GitPractice/blob/main/imagenes/list-commits.png)