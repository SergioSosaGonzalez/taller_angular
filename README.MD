En la siguiente carpeta se encontrará todo el material necesario para llevar el curso.

Pasos para inciar el curso de angular:

- Instalar la versión estable de NodeJS del siguiente link: https://nodejs.org/es/

- Instalar angular con el siguiente comando: npm install -g @angular/cli@latest.

- Entrar en la terminal o CMD y ubicarse en alguna carpeta de su preferencia para iniciar con el proyecto de angular.

- Crear un proyecto de angular con el siguiente comando: ng new tallerAngular. En caso de que les pregunte si quieren agregar el archivo routing le dicen que sí y si pregunta que tipo de lenguaje de hojas de estilo desea usar seleccione CSS.

- Entrar a la carpeta del proyecto que crearon por medio del CMD o terminal e instalar bootstrap y jquery con el siguiente comando: npm i bootstrap jquery.

- Ingrese al archivo angular.json y busque dentro del objeto build ( que esta aproximadamente en la linea 13 ) la propiedad styles y dentro de los corchetes ([]) escribir lo siguiente: "node_modules/bootstrap/dist/css/bootstrap.min.css", y en la parte de scripts un poco mas abajo poner: "node_modules/jquery/dist/jquery.min.js","node_modules/bootstrap/dist/js/bootstrap.min.js"

- Iniciar con npm start
