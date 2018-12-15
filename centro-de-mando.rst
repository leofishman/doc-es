###############
Centro de Mando
###############

Todo capitan de una Crypto-space Ship tiene que saber como hacerla evolucionar, ganar batallas y surcar el crypto-espacio.


*********************
Indicadores Generales
*********************

Los siguiente indicadores estan siempre presentes e informan lo siguiente:

.. image:: indicadores.png
    :width: 700px
    :alt: Recursos
    :align: center

1. Cantidad de **Energia** acumulada sobre la cantidad que puede almacenar actualmente. ( **acumulado** of **capacidad** )

2. Cantidad de **Grafeno** acumulado sobre la cantidad que puede almacenar actualmente

3. Cantidad de **Metales** acumulado sobre la cantidad que puede almacenar actualmente

4. Estado de la Crypto-space Ship. **100%** indica que se encuentra en optimas condiciones.

.. hint::
    Cuando el recurso acumulado es igual a la cantidad que la Crypto-space ship puede almacenar actualmente y la produccion de cada recurso es mayor a 0, se estan desperdiciando recursos. **Se recomienda gastar o de ser posible ampliar el almancen**.


********
Recursos
********

A continuacion se presenta la vista de Recursos.

.. image:: resources.png
    :width: 700px
    :alt: Recursos
    :align: center

Seccion Izquierda
=================

Se puede observar el nivel de:

1. Los paneles Solares

2. Recolector de Grafeno

3. Recolector de Metales

Las barras indican la cantidad de recursos disponibles para ampliar al proximo nivel. El color amarillo representa a la energia, el color negro al grafeno y el gris a metales.

El boton intermitente **UPGRADE READY** indica que se tienen los recursos necesario para ampliar de nivel y que no hay nada contruyendo, ya que no se permiten ampliaciones simultaneas. Al presionarlo se puede observar la cantidad re recursos necesarios para la actualiacion y al presionar el boton **Confirm** se envia la orden de construccion.

.. image:: upgrade.png
    :width: 400px
    :alt: Recursos
    :align: center

Una vez que se confirma, se descuentan los recursos y empieza su actualizacion.

Seccion Derecha
===============

Sobre este espacio se puede observar:

1. **Location**: Coordenada donde se encuentra la Crypto-space Ship

2. **Production Ratio**: La produccion de recursos por bloque

3. **Watch countdown**: La cuenta regresiva que muestra la cantidad de bloques restantes para terminar la actualizacion.

Opcionalmente pueden aparecer otros botones intermintes desbloqueando ciertas caracteristicas, como por ejemplo la opcion de prender el conversor de recursos y la opcion de convertir recursos.


**************
Construcciones
**************

Vista del panel de construcciones internas


.. image:: buildings.png
    :width: 700px
    :alt: Recursos
    :align: center

Seccion Izquierda
=================

Al igual que en la vista de recursos, se puede observar el nivel de las siguientes estructuras

1. Almacen

2. Hangar

3. W.O.P.R

Las barras indican la cantidad de recursos disponibles para ampliar al proximo nivel. El color amarillo representa a la energia, el color negro al grafeno y el gris a metales.

El boton intermitente **UPGRADE READY** indica que se tienen los recursos necesario para ampliar de nivel y que no hay nada contruyendo, ya que no se permiten ampliaciones simultaneas. Al presionarlo se puede observar la cantidad re recursos necesarios para la actualiacion y al presionar el boton **Confirm** se envia la orden de construccion.

Al momento de ampliar el W.O.P.R de nivel 0 a nivel 1, ademas se tiene que seleccionar el rol de W.O.P.R entre:

1. Converter

2. Crypto-Ion Cannon

3. Reparer

.. image:: wopr.png
    :width: 400px
    :alt: Recursos
    :align: center

Seccion Derecha
===============

En esta seccion se puede encontrar infomacion sobre la configuracion de la flota de drones de combate (**fleet**).

1. El numero de drones que compone la flota

2. Las caracteristicas de la flota, es decir, puntos de ataque, defensa, distancia y carga. En el caso de que la flota este diseñada. Al construir el hangar en nivel 1 ya aparece el boton intermintente **DESIGN FLEET** y luego que este diseñada **BUILD MORE**.
Ademas la otra opcion que puede aparecer es el boton intermitente **DISASSEMBLE FLEET** para destruir la flota actual.

3. La cantidad de drones que se encuentran en la cola de construccion.

4. Los relojes de cuenta regresiva

    - **BUILD**: Cuantos bloques faltan para finalizar la ampliacion del almace, hangar o wopr.

    - **FLEET**: Bloques restantes para la finalizacion de la construccion de la flota de drones.

    
***
Map
***

.. image:: map.png
    :width: 700px
    :alt: Recursos
    :align: center


********
Mensajes
********


*******
Eventos
*******

