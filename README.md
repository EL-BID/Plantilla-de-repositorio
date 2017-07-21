*Plantilla README.md para documentar Herramientas Digitales. [CÓDIGO PARA EL DESARROLLO](http://www.code.iadb.org)*


## Código para el desarrollo 

Este es un repositorio tiene dos propósitos: 
* Servir de plantilla modelo de repositorio para otros desarrolladores.
* Proponer recomendaciones sobre cómo documentar, evaluar y licenciar una herramienta digital. ([**ver wiki**](https://github.com/EL-BID/Codigo-para-el-desarrollo/wiki)

### Nombre y descripción
---
Esto es un archivo README. Debe contener la documentación de soporte uso de la herramienta digital. Las siguientes secciones son las secciones recomendadas que debes poner incluir en cualquier herramienta digital. Puedes descargar este archivo para que te sirva como plantilla.

Asegúrate de empezar este archivo con una breve descripción sobre las funcionalidades y contexto de la herramienta digital. Sé conciso y al grano.
 	
### Guía de instalación
---
Paso a paso de cómo instalar la herramienta digital. En algunas ocasiones esto puede ser sencillo, pero en otras ocasiones es necesario instalar otras herramientas que tiene dependencia con la herramienta digital. Si este es el caso, añade también la siguiente sección.

#### Dependencias
Descripción de los recursos externos que generan una dependencia para la reutilización de la herramienta digital (librerías, frameworks, acceso a bases de datos y licencias de cada recurso). Es una buena práctica describir las últimas versiones en las que ha sido probada la herramienta digital. 

    Puedes usar este estilo de letra diferenciar los comandos de instalación. Este es un buen ejemplo de una descripción de dependencias.
Ejemplo:
En el repositorio de la herramienta digital Smartmap https://github.com/EL-BID/SmartMap esta sección luce así:

    Cómo instalar

    Navega hasta cd js/components/smartmap-ui:

    npm install
    grunt init --force (instala las depencias de Bower, se requiere parar el proceso para continuar, utiliza Ctrl +c. Se ejecuta el comando forzado por un bug que se debe resolver.)
    grunt build
    Navega al directorio raiz de tu aplicación

    npm install
    grunt init --force (instala las depencias de Bower)
    grunt build
    Abre una nueva terminal y ejecuta Browser Sync para cargar un servidor HTTP

    browser-sync start --server --files "css/*.css"
    Voila !! Todo esta listo y corriendo.

    Recuerda:

    Cada vez que necesite reconstruir completamente el proyecto ejecuta grunt build en el directorio smartmap-ui y una vez completado ejecuta grunt build en la raíz de la aplicación.

### Guía de usuario
---
Idealmente en el README.MD


Una vez instalada, explica los pasos básicos de cómo usar la herramienta digital. Es una buena sección para mostrar capturas de pantalla y atraer a que más usuarios se animen a reutilizarla.



### Cómo contribuir
---
Idealmente en el README.MD


Esta sección explica debe explicar a desarrolladores cuáles son las maneras habituales de enviar una solicitudes de adhesión de nuevo código (“pull requests”), cómo declarar fallos en la herramienta y qué guías de estilo se deben usar al escribir más líneas de código.

### Código de conducta 
---
Idealmente en el README.MD


El código de conducta establece las normas sociales, reglas y responsabilidades que los individuos y organizaciones deben seguir al interactuar de alguna manera con la herramienta digital o su comunidad. Es una buena práctica para crear un ambiente de respeto e inclusión en las contribuciones al proyecto. La plataforma Github premia y ayuda a los repositorios dispongan de este archivo. Al crear CODE_OF_CONDUCT.md puedes empezar desde una plantilla sugerida por ellos. 

### Autor/es
---
Idealmente en el README.MD


### Información adicional
---
Opcional en el README.MD

### Licencia 
---
Idealmente en el README.MD

Es un conjunto de permisos que un desarrollador le puede otorgar a un usuario en los que tiene la posibilidad de distribuir, usar y/o modificar el producto bajo una licencia determinada.

Si tu herramienta digital no cuenta todavía con una licencia, te recomendamos que visites esta página https://choosealicense.com/.
