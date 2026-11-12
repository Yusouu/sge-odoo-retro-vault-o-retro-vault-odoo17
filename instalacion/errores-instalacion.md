Errores de instalacion y configuracion
Instalacion de Odoo 17 mediante Docker en entorno local.

Problemas encontrados durante el despliegue
Conflicto inicial con el contenedor de PostgreSQL o la base de datos previa que impedia arrancar correctamente el servicio en el puerto habitual.

Fallo de permisos o corrupcion en los datos de la base de datos de prueba inicial.

Solucion aplicada
Se elimino el contenedor anterior y el volumen asociado mediante docker para limpiar el entorno por completo.

Se creo una base de datos nueva desde cero en Odoo 17, asegurando que estuviera completamente limpia y sin datos de demostracion.

Se configuro el entorno para España y se comprobó el acceso correcto a traves de localhost.