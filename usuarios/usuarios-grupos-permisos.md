Usuarios, roles y permisos
Configuracion del sistema de seguridad y control de accesos en Odoo 17 para Retro Vault S.L., aplicando el principio de minimo privilegio.

1. Usuarios internos creados
   Comercial: Usuario encargado de la atencion al cliente y la creacion de presupuestos de venta. Cuenta con un rol restringido enfocado unicamente a sus propias operaciones comerciales.

Responsable de ventas: Usuario con privilegios de supervision global sobre el departamento comercial, encargado de revisar presupuestos y validar albaranes de salida.

Administracion / Facturacion: Usuario con acceso al area contable y de facturacion, encargado de emitir facturas y registrar los cobros, sin privilegios directos sobre la creacion de pedidos de venta.

2. Grupo de seguridad personalizado
   Para cumplir con los requisitos especificos de la tienda, se ha creado un grupo personalizado desde el modo desarrollador:

Nombre del grupo: Retro Vault / Comercial junior

Modelo asociado: Pedidos de venta (sale.order)

Permisos configurados: Acceso basico de lectura, escritura y creacion sobre los presupuestos y pedidos, manteniendo el aislamiento de datos frente a otros departamentos.

Asignacion: El grupo ha sido asignado al usuario con perfil comercial creado en el sistema.