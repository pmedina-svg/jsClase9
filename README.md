# jsClase9

Entregable

Asincronismo
Para esta instancia, se deben cumplir los siguientes puntos

Temporizador:
Se debe plantear un temporizador setTimeout()para generar una pequeña asincronía y mostrarle al usuario información unos segundos después de ingresar al simulador (ej. la cotización del dólar del día, un cupón de descuento, un mensaje a modo de recordatorio de una tarea importante, etc.)

Manejo de errores: (OPCIONAL)
Plantear una estructura try-catch-finally sobre un fragmento de código que pueda llegar a generar un error a futuro y capturarlo en el catch.

Contexto:
El proyecto debe mantener el contexto actual y las herramientas ser una adición al mismo, no se deben incorporar de manera aislada. Es importante presentar avances en el proyecto acordes a la instancia del curso.

Entrega:
Sube tus archivos a un repositorio de GitHub y comparte la URL. Asegúrate de que el repositorio sea público para que pueda ser revisado.

----------------------------------------------

Observaciones:

Temporizador:
Agregué temporizador en varias instancias: 
1. Al añadir un nombre de astronauta usé setTimeout entre el mensaje de bienvenida y el simulador.
2. Al cerrar sesión usé setInterval para mostrar un conteo en regresivo en pantalla y setTimeout para confirmar el cierre de sesión con cancelación automatica en caso de tiempo cumplido.
3. Al lanzar misión usé setTimeout con un plazo de 5 segundos para cancelar el lanzamiento de la misión (por si quieren modificar algo o simplemente cancelar).

Manejo de errores:
Lo agregué de manera casi simbolica (porque era opcional) usando el try, catch y finally en el mensaje de bienvenida antes de iniciar el simulador.