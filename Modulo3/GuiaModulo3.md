# Modulo 3:  Describir los componentes arquitectónicos centrales de Azure

![](https://docs.microsoft.com/es-es/azure/security/fundamentals/media/infrastructure-network/network-arch.png)

>## Estructura organizativa de los recursos en Azure

>|Niveles   |
>| ------------ |
>|1.- Administracion de grupos|
>|2.- Suscripciones|
>|3.- Recursos de grupos|
>|4.- Recursos|

>1. #### Recursos: Estos serian los que usted como usuario de la nuve crea para poder ofrecer o utilizar
>2. #### Grupos de recuros: Habiendo tantos y diferentes tipos de recursos se tuvo la necesidad de organizarlos en (Grupos de recursos) para tener una mejor organizacion.
>3. #### Suscripciones: Habiendo tantos y diferentes tipos de recursos se tuvo la necesidad de organizarlos en (Grupos de recursos) para tener una mejor organizacion.
>4. #### Grupos de administracion: Facilitan el control de acceso y politicas. En estos grupos de administracion se da algo llamado herencia que es cuando se agrega una nueva suscripcion esta pasa a tener las mismas restricciones del grupo de administracion en el que este.

## Regiones de Azure
![](https://images4.alphacoders.com/758/thumb-350-75886.jpg)
>#### Son lugares en alguna parte del mundo en donde hay desde 1 a varios centros de datos conectados a una red 

## Utilidad de las Regiones de Azure
>#### No es dificl de adivinar ya que tener si se tiene mas cerca algo que utilizamos por ende podremos trabajar mejor y con mayor velocidad.

## Regiones especiales de Azure
>1. #### Departamento de Defensa de EE. UU. Central, gobierno de EE. UU. Virginia, gobierno de EE. UU. Iowa y más
>2. #### China East, China North y más

## Zonas de disponibilidad de Azure
>#### Se componen de uno o más centros de datos independientes, separadas por si alguna falla la otra sigue trabajando y asi se asegura la alta disponibilidad.

## Par de regiones
>#### Se podria decir que cada region de Azure tiene su gemela para evitar afectaiones en caso de desastre natural, a region gemela continua trabajando.

## Administrador de recursos de Azure
>#### Es como el sistema que te da privilegios, podria decirse que es el usuario root como en linux, el cual permite crear, actualizar y eliminar recursos en su cuenta de Azure.

## Suscripciones de Azure
>#### Desde mi punto de vista es un pase VIP el cual te da el acceso a algun roducto o servicio de Azure

## Limites de suscripcion en Azure
>#### 1. Límite de facturación : este tipo de suscripción determina cómo se factura una cuenta de Azure por usar Azure.
>#### 2. Límite de control de acceso : Azure aplica políticas de administración de acceso en el nivel de suscripción y puede crear suscripciones independientes para reflejar diferentes estructuras organizativas.
