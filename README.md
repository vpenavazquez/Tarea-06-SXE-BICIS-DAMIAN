# Tarea-06-SXE-BICIS-DAMIAN
- En el ubuntu server primero crear la carpeta "bicisDamian" en la que hay que crear un repositorio con git init para poner el compose.yaml
> ![img_1.png](Capturas/img_1.png)
- Despues meter el ".env" dentro de gitignore como pide la tarea y poner las contraseñas y nombre de usuario
> ![img_2.png](Capturas/img_2.png)
- Dentro del nano del compose.yaml poner el siguiente codigo que saque de https://hub.docker.com/r/dolibarr/dolibarr 
> ![img_3.png](Capturas/img_3.png)

- Configuracion Dolibarr

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



