# Posicionamiento 

    como hacer posicionamiento usando HTML y CSS 
    Para posicionar elementos podemos posicionarlo en tres dimensiones, x, y, z:
    Podemos tener contenedores en 8 niveles del eje z, y moverlo en los ejes, x, y.

    Como visualizar los elementos del maquetado en el plano, tenemos que saber quien tiene la herencia.

    Se usa  ls ptopiedad z-index para mover los elementos en los planos.
    Dependiendo del elemento que estemos maquetando o las propiedades que estos tengan, el navegador entiende que estos se comportan de manera diferente.
    Por ello dedemos controlas el z-index.
    una maña de frontend, cuando tenemos plugins estorbane en el desarrollo, por lo cual se les pone un numeor muy alto es una mala práctica, pero para asegurar que el contenido no se encime conotros debemos asegurar que tiene un nivel alto para que no se encimen.

    la primer propiedad que debemos usar para posicionar un elemento es 

        position
    
    con sus cuatro valores

        static,
        relative,
        absolute,
        fix,
        sticky

    relative es la más importante para controlar las demas cosas

    si tenemos un div un circulo dentro de este contenedor tenemos que saber que coordenadas tiene.
    Tenemos que decir que el contenedor padre es relativo con el cual daremos sentido a los elementos que se encuentran dentro de ellos, es decir, tenemos que indicar que el contenedor es relative para poner los elementos como absolute y moverlos dentro del contenedor padre.
    absolute hace que los elementos dentro del contenedor denotado como relative se posicionen con respecto al contenedor.
    Si el contenedor no estuviese indicado como relativo, entonces los elementos marcados como absolute  se posicionarian con repecto al viewport (pagina, lugar visible)

    