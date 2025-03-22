# BetterIfYouDontReadme

Aqui describiré los elementos que he utilizado para el desarrollo del porfolio. 

Mostraré los colores, la tipografía, recursos y algun que orto problema que haya ocurrido en el desarrollo de la página

## 🖌️ Colores 🖌️

Prácticamente todos los colores utilizados han sido a través de variables CSS. Los colores han sido los siguientes:

- --bg-gradiant: linear-gradient(to right, #000000 30%, #a8a8a8 90%, #ffffff);
- --bg-gris: #a8a8a8;
- --bg-radial: radial-gradient(circle, #c5c3c3 20px, #666666 100px);
- --bg-h2: linear-gradient(to right, #fd0000 30%, #000000 80%);
- --bg-h: linear-gradient(to left, #fd0000 30%, #000000 80%);
- --bg-h1: linear-gradient(to left, #fd0000 90%, #000000 97%);
- --bg-corner: linear-gradient(230deg, #919191, #1b1b1b);
- --c-letra: rgb(197, 180, 180);
- Red
- White

El uso de colores han sido utilizados en:

- Fondo --> Header, footer, main...
- Texto --> Color de la variable --c-letra para el texto principal
- Titulos --> Uso de  variables como --bg-h2, --bg-h1, --bg-h

## 🔠 Tipografía 🔠

El proyecto se ha basado en la siguiente fuente, principalmente por el uso de sans-serif:

- font-family: Arial, Helvetica, sans-serif;

## ⚪ Logo Personal ⚪

El logo ha sido diseñado en una página que estará linkada al final de este documento.
Está linkado al html en el head a través de está linea:

<link rel="icon" type="image/x-icon" href="../Img/favicon.png">

## 📚 Librería utilizada 📚

Aqui en este proyecto únicamente he utilizado Bootstrap para los iconos:

He usado icónos representado las cosas donde las he puesto.
Algunos ejemplos:

- bi-github --> Icóno de GitHub
- bi-linkedin --> Icóno de LinkedIn

## 🔧 Problema técnicos 🔧

1. Rutas erroneas
    He tenido en algunos links problemas con los paths, en algunos variaba ya que al mover los archivos de sitios pues ya tenía que cambiar los paths de ir hacia atras de la carpeta para acceder a otra.

2. CSS
    Aqui han sido en varios sitios dónde he tenido que buscar de que manera hacer las cosas si no funcionaban de la manera que pensaba como por ejemplo en el trozo de código de contact, en el que la imagen al hacer el hover se expanda la imagen correctamente

3. Favicon
    Este ha sido el error más tonto que he tenido, en cuanto puse el favicon no se mostraba, no entendía porqué y era tan simple como la extensión del archivo que en vez de .ico era .png

## 🔗 Enlace a lo utilizado 🔗

- Bootstrap Icons: https://icons.getbootstrap.com/


- Favicon Generator: https://favicon.io/favicon-generator/

