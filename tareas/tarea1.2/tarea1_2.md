## Tarea 1.2- Trabajando con Git y MarkDown II
Para la entrega de esta y las sucesivas tareas/prácticas que hagamos durante el curso haremos uso de GitHub, deberán enviarme a través de Campus el enlace a la práctica así como el commit que indique la fecha de entrega. Este commit debe reflejar una fecha que se encuentre dentro del plazo establecido para la realización de la práctica marcado a través de la plataforma Campus, en caso contrario se dará por suspendida la práctica.

Este ejercicio es continuación del anterior por lo que tendremos el mismo repositorio.

Se deben incluir todos los comandos que se usen durante el ejercicio, las explicaciones y capturas de pantalla en el fichero README.me del repositorio.

### CREAR UNA RAMA
- git branch v0.2

> Creamos nuestra primera rama

![Rama v0.2](crear_branch_v02.jpg)

### AÑADIR  EL FICHERO 2.txt  (1 PUNTO)
> Añadir un fichero 2.txt en la rama v0.2

### CREAR UNA RAMA REMOTA v0.2 (1 PUNTO)
> Subir los cambios al repositorio remoto.

![2.txt](crear_2txt.jpg)

### MERGE DIRECTO (1 PUNTO)
- Posicionarse en la rama master.
- Hacer un merge de la rama v0.2 en la rama master.

![merge con master](hacer_merge_conmaster.jpg)

### MERGE CON CONFLICTO (1 PUNTO)
- En la rama master poner Hola  en el fichero 1.txt y hacer commit.
- Posicionarse en la rama v0.2 y poner Adios en el fichero 1.txt y hacer commit.
- Posicionarse de nuevo en la rama master y hacer un merge con la rama v0.2

![hola y adios en branch](hola_enMaster_adios_enBranch.jpg)

![merge hola y adios](hola_adios_mezclado.jpg)

### LISTADO DE RAMAS (1 PUNTO)
- Listar las ramas con merge y las ramas sin merge.

![listado de ramas](listado_commits.jpg)

### ARREGLAR  CONFLICTO (1 PUNTO)
- Arreglar el conflicto anterior y hacer un commit. Explicar como lo has arreglado incluyendo capturas de pantalla.

### BORRAR RAMA (1 PUNTO)
- Crear un tag v0.2
- Borrar la rama v0.2

![Creamos tag](crear_tag_v02.jpg)

![Borramos rama v0.2](borramos_branch_v02.jpg)

### LISTADO DE CAMBIOS (1 PUNTO)
- Listar los distintos commits con sus ramas y sus tags.

![Listado de commmits](listado_commits.jpg)

### CREAR UNA ORGANIZACIÓN (1 PUNTO)
- Crea una organización llamada orgdpl-tunombredeusuariodegithub ( ejemplo orgdpl-amarzar )

![Creamos organización](crear_organizacion.jpg)

### CREAR EQUIPOS 
- Crear dos equipos en la organización orgdpl-tunombredeusuariodegithub, uno llamado administradores con más permisos y otro colaboradores con menos permisos.
- Meter a github.com/amarzar y a 2 de vuestros compañeros de clase en el equipo de administradores.
- Meter a github.com/amarzar y a 2 de vuestros compañeros de clase en el equipo de colaboradores.

![Creamos Administradores](crear_administradores.jpg)

### CREAR UN index.html
- Crear un index.html que se pueda ver como página web en la organización.

### CREAR PULL REQUESTS
- Hacer 2 forks de 2 repositorios orgdpl-tunombredeusuariodegithub.github.io de 2 organizaciones de las que sean ni administradores ni colaboradores.
- Crear una rama en cada fork.
- En cada rama modificar el fichero index.html añadiendo vuestro nombre.
- Con cada rama hacer un pull request.

### GESTIONAR PULL REQUESTS
- Aceptar los pull request que lleguen a los repositorios de tu organización.

