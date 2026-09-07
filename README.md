# fundamentos-web-taller-1
## Caso A

Problema identificado:
La etiqueta `<img>` utiliza `href`, pero el atributo correcto para indicar la ubicación de una imagen es `src`.

Código incorrecto:

html
<img href="multimedia/perfil.jpg" alt="Fotografia del estudiante">


Corrección realizada:

html
<img src="multimedia/imagen1.jpg" alt="Imagen relacionada con programación">


Fuente consultada:
MDN Web Docs - elemento `<img>`: https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/img

## Caso B

Problema identificado:  
La etiqueta `<a>` utiliza `src`, pero el atributo correcto para establecer el destino de un enlace es `href`.

Código incorrecto:

html
<a src="https://developer.mozilla.org/">
    Consultar MDN
</a>


Corrección realizada:

html
<a href="https://developer.mozilla.org/">
    Consultar MDN
</a>


Fuente consultada:  
MDN Web Docs - elemento `<a>`: https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/a

## Caso C

Problema identificado:
Dentro de `<source>` se utiliza `href`, pero para especificar el recurso multimedia se debe utilizar `src`.

Código incorrecto:

html
<video controls>
    <source href="multimedia/video.mp4" type="video/mp4">
</video>


Corrección realizada:

html
<video controls>
    <source src="multimedia/video.mp4" type="video/mp4">
</video>


Fuente consultada: 
MDN Web Docs - elemento `<source>`: https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/source

## Caso D

Problema identificado:  
`correo` no es un valor válido para el atributo `type` de `<input>`. Para un campo de correo electrónico se debe utilizar `type="email"`.

Código incorrecto:

html
<input type="correo" name="correo">


Corrección realizada:

html
<input type="email" name="correo">


Fuente consultada:
MDN Web Docs - elemento `<input>`: https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/input

## Caso E

La afirmación es: Incorrecta.

Justificación:  
La etiqueta estándar de HTML para insertar una imagen es `<img>`, no `<image>`. Además, `<img>` es un elemento vacío y no necesita una etiqueta de cierre `</img>`.

Corrección realizada:

```html
<img src="multimedia/imagen1.jpg" alt="Imagen relacionada con programación">
```

Fuente consultada:
MDN Web Docs - elemento `<img>`: https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/img