# Uso de Blob Storage y creación de un sitio web estático
En este repositorio tenemos una demostración del uso de Blob Storage con un sitio web estático.

![Microsoft-Azure-Blob-Storage-Logo](https://github.com/DagonNR/Blob-Storage/blob/main/images/Microsoft-Azure-Blob-Storage-Logo.png)

---

## Requisitos
- Cuenta en [Microsoft Azure](https://portal.azure.com)
- Un dispositivo, por ejemplo una computadora
- Acceso a internet
- Navegador de internet como Google Chrome, Opera, Mozilla Firefox, etc.

---

## Importante
- Los Blob Storage de Azure cobran, dependiendo de cuanto se almacena en ellos.
- Es necesario crear una "Cuenta de almacenamiento" para poder hacer un "Blob Storage".

---

## Pasos a seguir
- Lo primero es crear una "Cuenta de almacenamiento" en [Microsoft Azure](https://portal.azure.com).
![P1](https://github.com/DagonNR/Blob-Storage/blob/main/images/P1.PNG)

- Es llenar los datos que nos pidan, igual que en todos los recursos de Azure, este pide suscripción, grupo de recursos, nombre y región, además de que se pueden cambiar ciertas cosas.
- Después de modificarlo a nuestra conveniencia, lo siguiente es ir al apartado de "Revisar y crear" y si todo sale correcto, darle clic en "Crear".
- Después de unos pocos minutos, nos saldrá que se completó la implementación.
- Lo siguiente es ir al recurso que acabamos de crear e ir al apartado de "Contenedores".
![P2](https://github.com/DagonNR/Blob-Storage/blob/main/images/P2.PNG)

- Entonces lo siguiente es clicar en "+Contenedor", entonces se nos desplegara una serie de opciones en el lateral derecho de la pantalla, nos pedira un nombre y un nivel de acceso, además de otras opciones más avanzadas.
![P3](https://github.com/DagonNR/Blob-Storage/blob/main/images/P3.PNG)

- Al finalizar le damos clic en "Crear".
- Entonces nos aparecerá el contenedor recién creado.
![P4](https://github.com/DagonNR/Blob-Storage/blob/main/images/P4.PNG)

- Si clicamos sobre él, ya podremos empezar a almacenar archivos.
- Para ello, vamos a clicar sobre "Cargar".
![P5](https://github.com/DagonNR/Blob-Storage/blob/main/images/P5.PNG)

- Entonces seleccionamos el o los archivos a subir y clicamos en "Cargar", y luego si clicamos sobre el archivo recien subido, nos dará acceso a una URL, donde podemos visualizar el contenido del mismo.
![P6](https://github.com/DagonNR/Blob-Storage/blob/main/images/P6.PNG)

- Para subir un sitio web estático, regresaremos a la cuenta de almacenamiento, y en lugar de entrar a "Contenedores", iremos a "Sitio web estático".
![P7](https://github.com/DagonNR/Blob-Storage/blob/main/images/P7.PNG)

- Dentro nos aparecerá que se encuentra "Deshabilitado", por lo que le clicamos, para habilitarlo, entonces nos pedirá un nombre, y luego clicamos en "Guardar".
- Después nos dará el mensaje de que se ha creado el contenedor, por lo que podemos acceder a el desde el apartado de "Contenedores" o clicando en "$web".
![P8](https://github.com/DagonNR/Blob-Storage/blob/main/images/P8.PNG)

- Ahora solo falta subir los archivos del sitio web, y listo.
