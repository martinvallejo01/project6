Proyecto 6 - Programación 4

CMP0311: Programación 3 - CMP3104: Programación 4
# Proyecto 6: Animación de  banderas , notificaciones, Broadcast.
Fecha de Entrega: 13 de Abril, 10 am, demo de 5 min en clase.
Cada hora o fracción de hora  de retraso tiene una penalidad del 5% de la nota 
del proyecto. Se contabiliza a partir de la hora de entrega.
Proyecto Individual o Parejas
Si no se hace la presentación se penaliza 50% de la nota final del proyecto. 
Subir a D2L el proyecto sin resultado de compilación, usar la opción Build/
clean del IDE, antes de empaquetarlo y subirlo.
MinSdk  API 22 - target sdk API 28 

La aplicación debe:
Presentar un botón (“Iniciar”)  y una grilla  (3 X 3) vacía .
Cuando se presiona “Iniciar”, crean un botón (o vista) en una posición de la 
grilla, notifica su  posición e inicia un ciclo de 6 cambios de banderas  aleatorios 
con tiempo específico , cuando termina el ciclo, el cuadro queda en blanco y 
envía una notificación de terminación con su posición en la grilla.
Cuando la grilla esta llena , se des-habilita el botón “Iniciar”, y se vuelve ha 
habilitar cuando hay alguna posición disponible.
Si cuando el botón-vista  esta cambiando de bandera,  si se dan un click sobre el 
botón-vista, se termina su ciclo de este botón-vista.
Dar un click sobre una posición vacía ,  envía un mensaje a un  Broadcast 
Receiver . El mismo que emite una notificación de error.
En el menú de setup , permite : seleccionar los continentes de los cuales se 
seleccionan banderas, y el tiempo de despliegue de las banderas. 

Calificación:
1) Funciona un botón-vista con ciclo completo - (10%)
2) Funciona mas de un botón-vista simultáneamente. - (20%)
3) Un botón-vista notifica inicio/terminación correctamente. - (10%)
4) Mas de un botón-vista notifica inicio/terminación correctamente. - (10%)
5) Habilita/Des-habilita “Iniciar”, con espacios usados en grilla. - (10%)
6) Interrupción ciclo de botón-vista y notificación correcta. -  (10%)
7) Broadcast-Notificación de Error en posición vacía - (10%)
8) Menu de Setup, funciona correctamente selección de continentes . (10%)
9) Menu de Setup, , funciona correctamente tiempo fijado. (10%)
Criterio que afectan la Evaluación :
1) Compila y Corre, garantizar que se compila desde la linea de comando. 
2) Funciona correctamente
3) Código entendible , comentado razonablemente
4) Código limpio
5) Responden preguntas todos los miembros del grupo o solo uno. 
6) Similitud con otros estudiantes? 
