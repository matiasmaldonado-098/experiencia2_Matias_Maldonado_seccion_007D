# experiencia2_Matias_Maldonado_seccion_007D

Documentación pasó a paso de como iniciar la aplicación de novela anime
Instalación de los programas que vamos a usar (si ya tienen instalado todo esto sáltense esta parte)
1)  Deben descargar node.js el link de este entorno de ejecución es el siguiente:
https://nodejs.org/es/

2) luego deben abrir el símbolo del sistema para instalar angular dejo el comando de instalación:
npm install -g @angular/cli

3) Deben crear una carpeta en el escritorio o donde estimen conveniente (esto es para poder almacenar el proyecto)

4) En la misma carpeta deben abrir el cmd o símbolo del sistema (también pueden abrir el cmd como administrador y ubicarse en la carpeta)

5) ya estando ubicado en la dirección de la carpeta en cmd deben instalar ionic ya que este proyecto está hecho con este framework dejo el comando de instalación:
npm install -g @ionic/cli

6) para crear un proyecto en ionic angular deben ejecutar el comando que dejare más abajo (en este caso se asume que tu como usuario no tienes proyectos creados y no sabes cómo hacer este tema te  si ya tienes esta parte puedes saltarte estos pasos)
ionic start myApp blank ( puede ser blank, tabs o side menú puedes buscar en la documentación de ionic y myApp es el nombre del proyecto que tú le quieras colocar)

7) si ya ejecutaste el comando de creación de proyecto te preguntara con que framework quieres trabajar esta aplicación debes elegir angular ya que este proyecto trabaja con este framework


8) ya estando lista esta parte debes eliminar el src de la aplicación que creaste o que ya tienes creada

9) descargar el src de github que estará en .rar al descomprimirlo debes tomar ese src y pegarlo en tu aplicación que eliminaste anteriormente el src antiguo

10) ya teniendo listo el paso “9” debes abrir el cmd y ubicarte dentó de la aplicación para poder instalar los plugin necesarios para que funcione correctamente esta aplicación y su base de datos

11) El primer plugin que deben ejecutar es:
npm install @ionic/storage

12) El segundo plugin que deben ejecutar es:
npm install @ionic/storage-angular

13) ya teniendo instalados los plugin pueden ejecutar el comando para arrancar el proyecto de ionic con el comando:
Ionic serve
