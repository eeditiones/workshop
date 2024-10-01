Instalación de eXist-DB
--------

*   Clica en el icono que presenta la versión estable más reciente que vemos al final de [la página de inicio de eXist-DB](http://exist-db.org/exist/apps/homepage/index.html).
  ![image](https://github.com/eeditiones/workshop/assets/8516387/4bddb5be-d6ec-4c7a-953b-8e758ba59e14)
*   Este enlace te llevará a la página GitHub del proyecto. Selecciona el fichero cuyo nombre sigue el siguiente formato (en lugar de la letra “x” tendrás el número de la versión): `exist-installer-x.x.x.jar`
*   Abre el fichero (requiere que tengas Java instalado; [aquí](https://www.java.com/en/download/help/download_options.html) tienes unas instrucciones de cómo instalarlo si lo necesitas).
*   Una vez lances el fichero, te saldrá un diálogo de ayuda:
  ![image](https://github.com/eeditiones/workshop/assets/8516387/9b98d366-e66a-40f7-8a4d-7bbd8cb5a1a5)
*   Selecciona el directorio de instalación (paso 2) y el directorio de datos (paso 3): puedes usar las opciones que te ofrece por defecto.
*   En el paso 4 establece la contraseña del usuario `admin` (el usuario administrado de la base de datos).
*   En los siguientes pasos, puedes aceptar las opciones por defecto.

Para probar que la instalación ha funcionado, busca la aplicación entre los programas instalados y ábrela. Si el servidor funciona correctamente, en la página: [http://localhost:8080/exist/](http://localhost:8080/exist/) deberías ver el “Dashboard” de eXist (durante el proceso de instalación, has podido seleccionar la instalación de determinadas aplicaciones dentro de eXist, por lo que tu dashboard no será idéntico al que se presenta en la captura):  
![image](https://github.com/eeditiones/workshop/assets/8516387/dbcc7776-517d-49ec-8492-ce50e90a5143)


En la esquina superior derecha, clica en `Login` y conéctate como el usuario `admin`.  

Si tienes problemas durante la instalación, consulta las [instrucciones disponibles en la página de eXist-DB](https://exist-db.org/exist/apps/doc/basic-installation).


