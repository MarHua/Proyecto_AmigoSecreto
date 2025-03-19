# Proyecto_AmigoSecreto
Es un proyecto que consiste en sortear al azar, diferentes nombres agregados a una lista. 

# Ejecución de código
Para ver este código en acción, se deberá descargar el archivo "index.html" y abrir en el navegador.
En este caso, se descargó en Visual y se pudo ver descargando la extensión LIve Server. 

# Explicación de código

Seagrega la función agregar para insertar nombres de las personas que se van a sortear.
Asimismo, se da una advertencia para cuando no se agregue un nombre

![Captura de pantalla 2025-03-18 210146](https://github.com/user-attachments/assets/c66067d0-ad9d-439c-b400-da48615d0200)

Para seguir agregando nombres, le mando una ordem con amigo.push y  con inputAmigo.value, se limpia el campo de texto.
![Captura de pantalla 2025-03-18 211210](https://github.com/user-attachments/assets/a7800071-b23d-4e3e-ba64-9751e7c75385)

Para que no se repita la lista de amigos y no me aprezca el mismo nombre, se agrega listaAmigos.innerHTML

![Captura de pantalla 2025-03-18 211246](https://github.com/user-attachments/assets/dc444dbe-e74e-49e0-9e3c-8e51201fc24a)

Se valida primero si hay amigos agregados para hacer el sorteo, en caso de que no, se lanza la alerta mediante un mensaje ¨No hay amigos para sortear¨ y se retorna nuevamente.
Se declara una variable "resultado" que se toma de el archivo index.html para poder hacer el sorteo y nos de un mensaje cuando se haga la ejecución de manera efectiva.

![Captura de pantalla 2025-03-18 211253](https://github.com/user-attachments/assets/0f1da75a-00d8-41fc-a716-37fdefea60f2)
