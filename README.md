# LEE ESTO PRIMERO
Los siguientes puntos se deben considerar para el avance de este proyecto Spring Boot y React o Angular.

* Si deseas agregar una nueva caracteristica o modificar algo, debes de crear tu propia rama apartir de la rama "master" para luego hacer el merge cuando creas haber terminado.
* Antes de hacer un commit, el mensaje debe parecerse mas o menos asi:" Añadido las clases, caracteristicas y tal... ", "Agregado bla bla bla...", "Modificado el bla bla " bueno ya me entienden.

# Empecemos


### Para levantar el proyecto
Considedar las siguientes configuraciones

* Si usas un ide para java con Maven, solo ejecuta el main() de la clase "FerroTodoApplication.java"
* El proyecto ya tiene tomcat embebido que se levanta en el puerto localhost:8081 (puedes modificarlo en el archivo properties si lo deseas o si tienes algun conflicto con este puerto 8081)
* Lo primero que se veras es el index que esta en la carpeta resources/static/ al introducir la url: http://localhost:8081/ despues de haber lebantado el proyecto

### Para los Frontends
Todo el proyecto del frontend deben hacerlo dentro de la carpeta static/, a continuacion los consejos:

* Puedes hacerlo en React o Angular
* No olvides que debes abrir la carpeta static/ en tu ide favorito y estaras listo para empezar y dejar volar tu imaginacion
* Para ver tu avance puedes usar el LiveServer de VScode si lo usas.
* No es necesario que levantes toooodo el proyecto Spring Boot para ver tu avance, y porque? confia en mi, cualquier proyecto fronted solo debes ponerlo en la carpeta static/ y todo funcionara normal, por lo demas no te preocupes, eso dejalo a los Banckends.

### Logica de negocio de la empresa Ferrotodo (Dominio)
* El Administrador se encarga de gestionar la empresa Ferrotodo
* El Cliente llega a la empresa Ferrotodo y hace sus compras
* La Ferreteria expone sus Productos en stock y los expone en la tienda fisica y en la web
* El Proveedor se encarga de suministrar los Productos al la empresa Ferrotodo
* El Vendedor de Ferrotodo se encarga de vender los Productos de la empresa
* SI FALTA ALGO MAS EN CUANTO A LOS REQUERIMIENTOS FUNCIONALES, LO ESTARE ACTUALIZANDO...

### Este .md se ira actualizando...
