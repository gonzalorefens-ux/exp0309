# exp0309
clase para compañeros

clonar el repositorio
git clone <nombre de la rama>

crear una rama
git checkout -b "nombre de rama, sin espacios y sin caracteres especiales"

"añadir todos los archivos modificados al paquete que queremos subir"
git add . 

"añadir por nombre de archivo, separado con espacios"
git add nombre_archivo nombre_archivo nombre_archivo

"peparar el paquete para la subida"
git commit -m "mensaje del paquere"

enviar los cambios agregados en el commit que se prepara
git push origin <nombre de rama>

Si quiero cargar una rama de un compañero para poder modificarla, o crear una nueva rama desde ella.
git fetch origin "bryan"
git checkout bryan
git checkout -b "modificacion_bryan"
