Proceso de venta y ciclo comercial
Documentacion del circuito comercial completo llevado a cabo en Odoo 17 para Retro Vault S.L.

1. Creacion del presupuesto y pedido (S0001)
   Se genera un nuevo pedido de venta bajo la referencia S0001 asociado al cliente Yusepps.

Se añaden los productos correspondientes del catalogo aplicando el tipo impositivo del 21% de IVA (Bienes):

The Legend Of Zelda Majora's Mask (N64): 2 unidades a 200,00 € cada una.

The Legend Of Zelda Twilight Princess (Gamecube): 1 unidad a 40,00 €.

Se confirma el presupuesto para convertirlo formalmente en pedido de venta, reservando el stock en el almacen.

2. Albarán y entrega de mercancía
   Se procesa la entrega asociada al pedido desde el modulo de Inventario.

Se comprueba que las cantidades entregadas coinciden con las solicitadas (2 unidades de Majora's Mask y 1 unidad de Twilight Princess) y se valida el albarán.

3. Facturación y cobro
   Se genera la factura regular a partir de las cantidades entregadas en el pedido.

Se valida la factura para asignarle su numeración oficial.

Se registra el pago correspondiente en el sistema y se deja marcada como pagada.