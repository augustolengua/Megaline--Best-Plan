## Data:
+
Tabla *Calls*
- 'id' — identificador único de la llamada
- 'user_id' — identificador del usuario que realiza la llamada
- 'call_date' — fecha de la llamada
- 'duration' — duración de la llamada en minutos

Tabla *Internet*
- 'id' — identificador único de la sesión
- 'user_id' — identificador del usuario
- 'session_date' — fecha de la sesión web
- 'mb_used' — volumen de datos gastados durante la sesión en megabytes

Tabla *Mensajes*
- 'id' — identificador único de SMS
- 'user_id' — identificador del usuario que envía SMS
- 'message_date' — fecha del SMS

Tabla *Plans*
- 'plan_name' — nombre de la tarifa
- 'usd_monthly_fee' — pago mensual en dólares estadounidenses
- 'minutes_included' — minutos incluidos al mes
- 'messages_included' — SMS incluidos al mes
- 'mb_per_month_included' — datos incluidos al mes (en megabytes)
- 'usd_per_minute' — precio por minuto tras exceder los límites del paquete (por ejemplo, si el paquete incluye 100 minutos el operador cobrará el minuto 101)
- 'usd_per_message' — precio por SMS tras exceder los límites del paquete
- 'usd_per_gb' — precio por gigabyte de los datos extra tras exceder los límites del paquete (1 GB = 1024 megabytes)


## Goal:

Determinar cuál de los planes genera más ingresos para ajustar el presupuesto de publicidad.
Probar las hipótesis:
- El ingreso promedio de los usuarios de las tarifas Ultimate y Surf difiere.
- El ingreso promedio de los usuarios en el área de estados Nueva York-Nueva Jersey es diferente al de los usuarios de otras regiones.

## Libraries used:

pandas

scipy

numpy

datetime

math

mathplotlib.pyplot

