# Tarea-06-SXE-BICIS-DAMIAN
- En el ubuntu server primero crear la carpeta "bicisDamian" en la que hay que crear un repositorio con git init para poner el compose.yaml
> ![img_1.png](Capturas/img_1.png)
- Despues meter el ".env" dentro de gitignore como pide la tarea y poner las contraseñas y nombre de usuario
> ![img_2.png](Capturas/img_2.png)
- Dentro del nano del compose.yaml poner el siguiente codigo que saque de https://hub.docker.com/r/dolibarr/dolibarr 
> ![img_3.png](Capturas/img_3.png)

- Configuracion Dolibarr

-PASO 1

![img_4.png](Capturas/img_4.png)

Una vez instalado Dolibarr e iniciado sesion para configurarlo vamos a Inicio - Configuracion - Modulos


Ahora vamos a activar varios Modulos

![img_5.png](Capturas/img_5.png)

Activamos Terceros necesario para dar de alta tanto a clientes como a proveedores

![img_9.png](Capturas/img_9.png)

Activamos Intervenciones para saber que piezas o cambios le hemos vendido a nuestros clientes

Ahora vamos a Gestion de Relaciones con Proveedores

![img_6.png](Capturas/img_6.png)

Activamos proveedores para asociar los artículos a surtidores y registrar precios de compra.

Ahora vamos a Gestion de Productos

![img_7.png](Capturas/img_7.png)

Activamos Productos para gestionar el catálogo de recambios y piezas.

![img_8.png](Capturas/img_8.png)

Activamos Stocks para el control de existencias en tiempo real


- PASO 2

- Ahora vamos a crear el almacen principal 
- Vamos a Productos/Servicios - Almacenes - Nuevo Almacen

![img_10.png](Capturas/img_10.png)


![img_11.png](Capturas/img_11.png)

Creamos el almacen y le añadimos nombre y descripciones si lo queremos



- Ahora vamos a registrar el catalogo de recambios
- Vamos a Productos - Nuevo producto

![img_12.png](Capturas/img_12.png)


![img_13.png](Capturas/img_13.png)

- Creamos el nuevo producto, añadimos referencia, nombre, descripcion, cuando queremos que nos alerte si llega a x unidades y cual seria el stock deseado

![img_14.png](Capturas/img_14.png)

- Producto creado

- Vamos a la pestaña de arriba de Stock

![img_15.png](Capturas/img_15.png)

- Le damos a corregir stock y añadimos el stock del almacen 

![img_16.png](Capturas/img_16.png)

- Añadimos el stock que queremos y precio por unidad

Paso 3

- Asociar Proveedores y tarifas para elegir la opcion mas economica

- Vamos a Terceros - Nuevo Tercero

![img_17.png](Capturas/img_17.png)


![img_18.png](Capturas/img_18.png)

- Le ponemos nombre y marcamos la opcion proveedor

- Ahora volvemos a Productos - Lista de Productos y seleccionamos el reecambio que habiamos creado

![img_19.png](Capturas/img_19.png)

- Una vez vamos al producto le vamos a la pestaña superior de Precios de compra

- 
- ![img_20.png](Capturas/img_20.png)

- Añadimos un proveedor con su referencia y precio de compra

![img_21.png](Capturas/img_21.png)

Una vez añadido podemos ver nuestros proveedores y quien tiene mejor precio de compra


Paso 4

- Ahora vamos a crear el historial de reparaciones para damian

- Volvemos a ir a terceros - nuevo tercero y creamos un cliente

![img_22.png](Capturas/img_22.png)

- cliente creado

- Ahora vamos a crear una ficha de taller para saber que reparacion le hemos hecho a cada cliente y que piezas usamos

- vamos a comercial - intervenciones - nueva intervencion

![img_23.png](Capturas/img_23.png)

- Le damos a nueva intervencion

![img_24.png](Capturas/img_24.png)

- Seleccionamos a un tercero

![img_25.png](Capturas/img_25.png)

![img_30.png](Capturas/img_30.png)

Añadimos descripcion y articulo usado 

Ahora vamos a Terceros - Lista de clientes

Seleccionamos al cliente al que le creamos la intervencion y podremos ver las intervenciones que hemos creado

![img_31.png](Capturas/img_31.png)

![img_32.png](Capturas/img_32.png)

