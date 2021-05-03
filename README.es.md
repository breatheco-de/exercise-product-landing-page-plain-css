# Construye la Página de inicio de un producto con HTML/CSS

![Product Landing Page Exercise for HTML/CSS](https://github.com/breatheco-de/exercise-product-landing-page-plain-css/blob/master/.learn/assets/preview.png?raw=true)

Diseñar o hacer layouts es una de la cosas más difíciles en CSS/HMTL, nunca ha sido una buena tecnología para facilitar este proceso, lo que es extraño y triste pues era su principal objetivo.

Sin embargo, en los últimos años las cosas han mejorado, desde el año 2018 podemos usa las reglas CSS `display: flex;` y `display: grid;`.

Hay algunos frameworks de css como Bootstrap [que se utiliza ampliamente en ~ 30% de los sitios web del mundo.](https://w3techs.com/technologies/details/js-bootstrap), Foundation, Material UI, etc. El objetivo de este ejercicio es pulir tus habilidades en CSS/HTML puro.

## 📝 Instrucciones

1. Reproduce exactamente [la página de este producto](https://github.com/breatheco-de/exercise-product-landing-page-plain-css/blob/master/.learn/assets/preview.png?raw=true) en HTML/CSS. No puedes usar ningún framework CSS y la página de inicio no debe ser interactiva.
2. Usa la imágenes de la carpeta `./assets`.
3. Usa las reglas de CSS flex-box, aquí hay un muy buen documento que explica todo al respecto: https://css-tricks.com/snippets/css/a-guide-to-flexbox/

## 🌱  Cómo iniciar este proyecto

Este proyecto viene con los archivos necesarios para empezar a trabajar, pero tienes dos opciones para empezar:

a) Abrir este link con Gitpod en tu navegador(recomendada): https://gitpod.io#https://github.com/breatheco-de/exercise-product-landing-page-plain-css

b) Clonar este repositorio localmente en tu computador:
```sh
$ git clone https://github.com/breatheco-de/exercise-product-landing-page-plain-css.git
```
**Asegúrate de tener instalado node.js en tu computador y ejecutar el siguiente comando en tu terminal para previsualizar tu sitio web:**

```sh
npx --yes http-server -c-1
```

💡 Importante: 

+ Recuerda actualizar el `remote` del proyecto con el de tu repositorio usando `git remote set-url origin <your new url>`, y luego guardar tu código en tu nuevo repositorio usando `add`, `commit` y `push`.

+ Nota: tendrás que actualizar tu navegador cada vez que actualices tu código.

## Nadie te dice esto:

- El 40% de los errores al hacer HTML son tags o etiquetas de cierre faltantes o mal puestas, para evitarlo abre y cierra la etiqueta o tag al mismo tiempo y luego agrega el contenido de la etiqueta.

- Elegir los nombres de las clases de CSS es el verdadero truco: los nombres de las clases le dan forma a tu forma de pensar. En lugar de usar nombres orientados a los negocios como producto1, producto2, nosotros, etc. Deberías usar nombres orientados al comportamiento como `menú` o` lista-horizontal`, etc. Eso te ayudará a reutilizar mucho las clases.

- Don't use the `<img>` for images that will be uploaded later by a user, you should instead use `<div>` with background images, the image tag is only used for little things.

No uses el `<img>` para imágenes que más tarde cargará un usuario, en su lugar deberías usar un `<div>` con imágenes de fondo, la etiqueta de imagen solo se usa para pequeñas cosas.
