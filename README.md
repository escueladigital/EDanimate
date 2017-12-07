# EDanimate

Es una librería de animaciones empaquetadas en mixins de Sass. Esta inspirada en animate.css y es parte del curso [CSS Avanzado Animaciones de EDteam](https://ed.team/css-animaciones).

## ¿Cómo usarlo?

Puedes usar EDanimate con CSS o con Sass (recomendable).

### Con CSS
* Descarga el archivo `public/css/ed-animate.css` e inclúyelo en tu proyecto. Luego puedes agregar las siguientes clases a los elementos que deseas que se animen:
```language-css
.fade-in
.fade-out
.slide-left
.slide-right
.slide-top
.slide-bottom
.slide-up
.slide-down
.zoom-in
.zoom-out
.bounce-left
.bounce-top
.bounce-right
.bounce-bottom
.animated-borders
``` 

### Con Sass
* Instale EDanimate con el comando `npm install --save-dev ed-animate`
* Establezca la variable `$EDanimatehelpers: false` para compilar solo lo necesario (debe hacerlo antes de importar EDanimate).
* Importe `ed-animate/ed-animate` en su proyecto.
* Los mixins disponibles son:
```language-scss
fadeIn($time)
fadeOut($time)
slideLeft($time)
slideRight($time)
slideTop($time)
slideBottom($time)
slideDown($time, $height)
slideUp($time,$height)
zoomIn($time)
zoomOut($time)
bounceLeft($time)
bounceTop($time)
bounceRight($time)
bounceBottom($time)
animatedBorders($time, $color)
``` 
