#Repositorio grupla de Taller de enmarcado

Este es una carpeta de los trabajos del grupo.
recuerden siempre hacer git pull y mandar un
mensaje que hicieron cambios

#Comision 04:

        #Grupo de taller enmarcado
        -SEBASTIAN IGNACIO MONTERO
        -Lucía Nicole Caro
        -Lautaro Brea
        -Nuñez Valentin Elias


#Ayuda<br>

2.documentos para problemas con commits :<br> https://docs.github.com/es/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/changing-a-commit-message

<hr>

#organizacion de commits<br>
utilizaremos las etiquetas de Conventional Commits para comunicar cada cambio hecho 
en un commit.


fuentes de inspiracion:<br>

-https://www.conventionalcommits.org/en/v1.0.0/

-https://midu.dev/buenas-practicas-escribir-commits-git/

-https://github.com/KarmaPulse/git-commit-message-conventions

resumen:<br>

estructuras de commits:<br>

Estructura 1 con alcance:

        <TIPO>(<alcance>):ASUNTO
        espacio en blanco
        <cuerpo opcional>
        espacio en blanco
        <pie de pagina opcional>

<img src="assets/ejemplo.png">

Estructura 2 sin alcance:

        <TIPO>:ASUNTO
        espacio en blanco
        <cuerpo opcional>
        espacio en blanco
        <pie de pagina opcional>

TIPO: es el tipo de cambio que hace en el codigo<br>

alcance: es el archivo donde se hace los cambios<br>

ASUNTO: es una descripcion que empieza con una palabra infinitiva<br>
(en español) es decir verbo que termina con ar,er, ir , o imperactiva<br>
(en ingles) que tiene como limite maximo de carecteres 50<br>

Cuerpo: lo mismo que el ASUNTO pero mas largo, si el ASUNTO no basta<br> 
para describir el cambio, 100 caracteres maximo por linea, pueden<br> 
haber parrafos tanto parrafos como quieras para describir un cambio<br>

pie de pagina: donde se pone una etiqueta llamada  BREAKING CHANGE de<br>
 100 caracteres maximo por linea, puede haber mas de un pie de pagina.<br>

#Etiquetas:

        "feat" se añadio una nueva funcion

        "fix" se arreglo un error o bug

        "docs" se añadio o modifica la documentacion

        "chore" tarea rutirania, ejemplo: modificar gitignore o mover archivo de lugar.
        
        refactor: Refactorización del código como cambios de nombre de variables
        o funciones.

        "style" cambios en el codigo que no afecta la logica, ni el contexto 
        o estado del codigo. solo afecta al codigo con espacios en blanco,
        tabulaciones, sangria, mas lineas vacias, menos linea vacias,etc.

        "test" añade una version de testeo del proyecto

        "BREAKING CHANGE" o "!" : es una cambio critico, que genera
         incompatibilidad con versiones anteriores como MAJOR.
