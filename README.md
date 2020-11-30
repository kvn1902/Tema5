# Laboratorio 5
## Modelos probabilísticos de señales y sistemas
### Kevin Cambronero, B71491

Para satisfacer el requisito se siguió el mismo procedimiento del ejemplo, pero calculando la probabilidad de que hubiera al menos un cliente en el sistema, y sabiendo que eso debía ser mayor a 90%.

Para comprobar que el resultado obtenido es correcto, se modificó ligeramente el código, cambiando nu por 2.22/60 (2.22 solicitudes atendidas por minuto) y P por 1 (1 persona en el sistema). Al final se calcula el tiempo con "más de -1 solicitudes en fila", porque en la fila normalmente no habría nadie, y se encontraría en el sistema solo la persona que se está atendiendo.
