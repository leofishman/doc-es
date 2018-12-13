CSS Hull
========


Descripción 
-----------

El CSS Hull es el componente que junto al CSS Token forman una CryptoSpaceShip. Este modulo descartable solamente se utiliza para un tetro de operaciones.


.. note::
    La generacion actual de los CSS Hull es: **Gen 0**

Caracteristicas de la generación actual 
---------------------------------------

- Cuenta con dos motores CrIon-2 que permiten un salto de hasta 6 gdu

- Almacenamiento de hasta 16.000.000 de recursos 

- Espacio para hasta 520 drones de combate

- 2 Conectores QAIM

- 4 Modos de comportamiento. Ataque, Defensa, Movimiento y Defecto


.. note::
    La generacion **Gen 0** tiene una interfaz de 2 QAIM con el modulo CSS Token. Es decir si el CSS Token tiene mas QAIMs, como maximo se van a poder conectar con dos de ellos.
    

Estructuras Productivas
-----------------------

- **6 Paneles solares**: Cada uno de los paneles solares se puede actualizar desde el nivel 1 al nivel 10

- **1 Recolector de Grafeno**: El recolector de grafeno se puede actualizar desde el nivel 1 al nivel 10. Produciento en el primer nivel 1 grafeno por densidad y en el utimo nivel 40 grafeno por densidad.

- **1 Recolector de Minerales**: El recolector de metales se puede actualizar desde el nivel 1 al nivel 10. Produciendo en el primer nivel 1 grafeno por densidad y en el ultimo nivel 40 grafeno por densidad.


.. note::
    En el **Crypto-Space** existen 3 elementos: Energia, Grafeno y Metales. La produccion de energia no depende de la posicion donde se encuentre la CryptoSpaceShip ya que no depende de la distancia a la estrella mas cercana. En el caso del grafeno y los metales cada coordenada del crypto-space tiene una densidad distinta. 
    La variacion de la densidad es un tema de estudio actual.

A continuacion se detalla el calculo de produccion.

::
    pe = d * N
    Siendo
    - pe = Produccion
    - d = Densidad del recurso en la posicion
    - N = La cantidad que produce un recolector (ya sea de grafeno o metales) en un nivel dado.



   






