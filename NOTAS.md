# Inicio
>ng new TodoDragAndDrop
>code . [abrir en VSCode]
>ng serve --o
# Bootstrap
Instalar bootstrap a nuestro proyecto
>npm install bootstrap
Ir angular.json e insertar
"styles": [
              "src/styles.css",
              "node_modules/bootstrap/dist/css/bootstrap.min.css"
            ],
>ng serve --o
# Fondo con uiGradients
https://uigradients.com/#DayTripper
Elegir gradiente, copiar css y pegar en styles.css
# Tipologia letras GoogleFonts
Seleccionar, copiar link -> ir a index.html y pegar
Copiar CSS rules to specify families -> ir tarea.css
ir a tarea.html y usarlo como una class

# Drag&Drop 
Instalar libreria @angular/cdk
https://www.npmjs.com/package/@angular/cdk
>npm i @angular/cdk
Ir Angular Material
https://material.angular.io/cdk/drag-drop/overview
Ir app.module e importar -> import {DragDropModule} from '@angular/cdk/drag-drop'; 
Ir a Overview -> copiar codigo y pegar en el html
Ir a CSS -> copiar codigo y pegar en el css
Ir a TS -> copiar codigo y pegar en el ts

# Componente
Crear app/componentes
>ng g c components/tarea
Renderizar el componente en app.component.html
Ir tarea.html

# Input ingresar nueva tarea
Ir tarea.html
Ir app.module e importar FormsModule

# Deploy en netlify
>ng help [lista todos comandos]
>ng build --prod [modo compilacion AOT]
Genera carpeta dist/nombre proyecto/archivos
Ir netlify - signin - sites - arrastrar carpeta dentro de dist con el nombre del proyecto, en campo inferior - loading
Site settings -> change site name [cambiar nombre dela pagina]