## [Aplicaciones cliente/servidor y Peer to Peer]()

Arquitectura que surgio en la decada del 70

* Servidor:
Es la maquina que provee los rescuros al resto de equipos para lograr una
centralización de la información

* Cliente:
Es la maquina que tendra cada usuario para hacer peticiones al Server

- Ejemplo
    * Paginas Web
    * Servidores FTP
    * email
    * etc.

### [Arquitectura cliente/servidor en 3 capas]()

El cliente hace una petición al server
El Server puede hacer peticiones a un Server de **BASES DE DATOS**
La base de datos le devuelve la respuesta al Server
El Server procesa todo y se lo responde al Cliente

#### [Ventajas de esta arquitectura]()
- Arquitectura madura
- Fácil de administrar
- Fácilmente escalable

#### [Desventajas de esta arquitectura]()
- Dependencias de un único punto
    * Puede colapsar si hay muchas peticiones de forma simultanea
    * Si el server cae, toda la estructura se cae.
    * Dependemos del Hard y el Soft del Server

- Los dispositivos Clientes dependen por completo del server


### [Definicion Peer to Peer]()
- Es un red con grandes ventajas y optimizan el ancho de banda para evitar
posibles problemas del punto de fallo del servidor. Si un nodo de esta red
se cae, el resto puede servir la información de todos modos. 
> Ejemlo: 
> - Ares Galaxy
> - eMule
> - Spotify
