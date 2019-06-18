# docs-hceleste

•	La habitación consta de varios tipos de cama (pequeña, mediana y grande), se puede agregar una cama adicional (máximo 1 adicional por el momento). 
•	Las camas deben estar en stock (solo hay siete adicionales hasta el momento).
•	Las solicitudes pueden hacerse por teléfono o presencial.
•	Los cortes son diarios (fundamental).
•	Una reserva puede ser registrada por un usuario y una salida por otro.
•	Estados de los pagos son: cancelados y pendientes.
•	Posibles escenarios de la reserva: Pagos a créditos, cortesía y efectivo.
•	Medios de pago: efectivo y a futuro con tarjeta.
•	El corte del día debe estar a las 6:00 am del día siguiente pero el cliente tiene hasta las 2:00 pm para irse o confirmar si sigue, lo cual contaría como otra reserva.
•	El reporte del corte debe incluir las habitaciones en estado pendiente.
•	Los cobros deben ser “día fracción” (mínimo un día de cobro).
•	Los estados posibles de la habitación son: reservado, disponible, ocupado, limpieza y mantenimiento.
•	Cuando la habitación está en estado de limpieza no puede ser ocupada, pero si reservada.
•	Cuando la habitación está en estado de mantenimiento no puede ser reservada.
•	La opción de mantenimiento puede darse en cualquier parte del ciclo.
•	Cuando se registra una salida en una habitación pasa a estado de limpieza automáticamente.
•	En caso de que el cliente pague, aunque no esté ocupándola, esta debe ser marcada como ocupada.
•	El cambio en la reserva debe darse antes de que la habitación esté ocupada.
•	el mvp será realizará en dos iteraciones, solo hotel sin cargos adicionales y una segunda iteración con cargos adicionales.
•	A una habitación se le pueden agregar cargos adicionales, los cuales aumentan el costo del servicio.
•	El calculo del corte diario se realiza de la siguiente forma: 
(Total de costo de habitaciones) - (total habitaciones pendientes) + (total servicios adicionales).
•	Debe haber un usuario con privilegios para cambiar el estado de una habitación en cualquier momento, así como sus precios y servicios adicionales con su debida observación.
•	Se debe generar un reporte con el corte diario o con un rango de fecha en formato excel.
