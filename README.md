# Proyecto_AmigoSecreto
Es un proyecto que consiste en sortear al azar, diferentes nombres agregados a una lista. 

# Ejecución de código
Para ver este código en acción, se deberá descargar el archivo "index.html" y abrir en el navegador.
En este caso, se descargó en Visual y se pudo ver descargando la extensión LIve Server. 

# Explicación de código
![Captura de pantalla 2025-03-18 210146](https://github.com/user-attachments/assets/c66067d0-ad9d-439c-b400-da48615d0200)

Se gener la funcion agregar 

function agregarAmigo(){
    let inputAmigo = document.getElementById("amigo");
     
    let nombreAmigo= inputAmigo.value;
// Aqui le doy una advertencia para cuando no se agregue un nombre
    if(!nombreAmigo){
        alert("Ingrese un nombre");
        return;

    }
