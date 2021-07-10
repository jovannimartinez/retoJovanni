# Modulo 5: Explore los servicios de red de Azure
![](https://aidanfinn.com/wp-content/uploads/2015/10/Azure-Virtual-Network-1024x522.png)

## Redes virtuales de Azure
>#### Este tipo de redes  posibilitan que las máquinas virtuales, las aplicaciones web y las bases de datos, se comuniquen entre sí, con los usuarios de Internet y con sus equipos cliente locales.

## Las redes virtuales de Azure ofrecen:
>#### 1. Aislamiento y segmentación
>#### 2. Comunicaciones por internet
>#### 3. Comunicarse entre los recursos de Azure
>#### 4. Comunicarse con recursos locales
>#### 5. Enrutar el tráfico de la red
>#### 6. Filtrar el tráfico de la red
>#### 7. Filtrar el tráfico de la red

## Aislamiento y segmentación
>#### Practicamente consiste en crear subredes


## Comunicarse con recursos locales
>#### 1. Redes privadas virtuales punto a sitio
El cliente se conecta via VPN a la red virtual de Azure
>#### 2. Redes privadas virtuales de sitio a sitio
Vincua su dispositivo VPN local a la puerta de enlace de Azure VPN en una red virtual. 
>#### 3. Azure ExpressRoute
Es especial para entornos con requisitos de ancho de banda y seguridad mayores, conectividad privada que no viaja por internet

## Enrutar el tráfico de la red
>#### Azure es tan bueno que por default enruta el tráfico entre subredes en cualquier red virtual conectada, redes locales e Internet

>#### 1. Tablas de rutas
Permiten definir reglas sobre cómo se debe dirigir el tráfico
>#### 2. Protocolo de puerta de enlace fronteriza (BGP)
Funciona con puertas de enlace VPN de Azure o ExpressRoute para propagar rutas BGP locales a redes virtuales de Azure.

## Filtrar el tráfico de la red
>#### Usted puede filtrar mediante los siguientes enfoques:

>#### 1. Grupos de seguridad de red
Es un recurso de Azure que puede contener varias reglas de seguridad entrantes y salientes.
>#### 2. Dispositivos virtuales de red
Es una máquina virtual especializada que se puede comparar con un dispositivo de red reforzado.

## UDR (Enrutamiento definido por el usuario)
>#### Permite a los administradores de red controlar las tablas de enrutamiento entre subredes dentro de una red virtual, así como entre redes virtuales.