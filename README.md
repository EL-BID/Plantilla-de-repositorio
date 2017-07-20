*Plantilla README.md para documentar Herramientas Digitales. [CÓDIGO PARA EL DESARROLLO](http://www.code.iadb.org)*


## Código para el desarrollo <img src="https://cdn.rawgit.com/nteract/hydrogen/17eda245/static/animate-logo.svg" alt="hydrogen animated logo" height="50px" align="right" />


Este es un repositorio que contiene los archivos modelo para que una herramienta digital pueda ser reutilizada.

Los requisitos mínimos a nivel de documentación que necesita tu repositorio para ser subido en el github oficial de EL-BID son:

* README.md
  * Nombre y descripción
  * Guía de instalación
  * Guía de usuario
  * Licencia
  * Autores
  
* LICENCE (puede estar incluido en el Readme.md)

Un archivo README contiene información sobre la herramienta digital. Es una forma de documentación de software y es por eso que  en la iniciativa de Código para el desarrollo solicitamos que el repositorio contenga un documento README.md, la extención del archivo deberá ser Markdown.
El nombre del archivo es generalmente escrito en mayúsculas.

Lineas abajo te describimos que contenido debes colocar en el README.md

### Nombre y descripción
---
Idealmente en el README.MD

Esta primera sección del README.md se presenta la herramienta digital, el nombre con el que se le conoce acompañado de una breve descripción que oriente al que la lea sobre las funcionalidades y contexto de la herramienta.

 	
### Guía de instalación
---
Idealmente en el README.MD


Paso a paso de cómo instalar la herramienta digital y los requerimientos mínimos para hacer esto posible. Esta sección contempla las configuraciones necesarias para dejar preparado el ambiente de trabajo y las versiones mínimas en las que ha sido probado anteriormente la herramienta digital.

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
