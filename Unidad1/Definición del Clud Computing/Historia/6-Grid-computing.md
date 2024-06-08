## [Grid Computing]()

Es un conjunto de PC interconectados como una rejilla para que trabajen de forma
paralela conectados atravez de una interfaz de red para compartir sus recursos. 
( RAM, CPU, HDD, etc. )

El nodo central del **Grid** recibe una tarea que requiere una gran capacidad de 
computo, el mismo la ejectua entre el resto de los nodos del **Grid** como si fuese
1 solo. 

Si 1 nodo se cae, el servidor de control reconfigura los procesos internos para que 
ese servidor no reciba mas tareas. 

### [Las 5 capas de una Grid]()
1. Aplicación:
    * Son todas las Apps construidas con el protocolo API ( Aplication Programming Interface)
2. Coleccion:
    * Captura las diversas interacciones entre los recursos del grid
3. Recursos
    * Protocolo para gestionar los recursos del **Grid**
4. Conectividad: 
    * Protocolo de comunicación y autentificación entre los nodos
5. Estructura
    * Acceso a diferentes recursos.

### [Ventajas]()
- Comparten recursos y el nodo principal se encarga de enviar tareas solo a los nodos
activos.
- Los costes son mas ecónimico ya que comparten recursos
- Los nodos pueden estar conectados a miles de kilometros, solo necesitan estar conectados
en una red privada. 

### [Desventajas]()
- La distancia entre los nodos puede ser más lentas debido a que los mismos pueden
estar a miles de kilometros
- La sicronización entre los nodos es vital ya es es el core del sistema.
- Dificultad para sincronizar los procesos en todos los equipos.
- Alungas Apps. no pueden procesarse de esta forma, como las bases de datos transaccionales.


### [¿ El Grid puede ser considerado como un primer paso al Cloud Computing]()
- Se comparten los recursos
- Razones de escalabilidad