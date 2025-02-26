### Diseño y Nuevos Medios → Clase 10 → 11/05/2021

# Bootstrap v5.1

### Teoría

[Bootstrap](https://getbootstrap.com/) es un kit de herramientas de código abierto para la implementación de diseño [responsive](https://es.wikipedia.org/wiki/Dise%C3%B1o_web_adaptable) y [mobile-first](https://en.ryte.com/wiki/Mobile_First) de sitios y aplicaciones web. 

Con [Bootstrap](https://getbootstrap.com/) puedes implementar tanto prototipos rápidos como productos acabados, esto mediante el uso de Elementos de HTML5 relacionados con reglas de CSS3 predefinidas con [Sass](https://sass-lang.com/) ([Less](http://lesscss.org/) en versiones de Boostrap anteriores a la 4), además de Javascript simplificado por una biblioteca (que debe complementarse con [jQuery](https://jquery.com/) en versiones de Bootstrap anteriores a la 5). Nosotros trabajaremos con [la más reciente](https://getbootstrap.com/docs/versions/), la quinta versión (punto uno, punto tres). 

Hay distintas maneras de comenzar a trabajar con Boostrap v5.1.3. Nosotros podemos partir con una adaptación de la [Starter template](https://getbootstrap.com/docs/5.1/getting-started/introduction/#starter-template), con un documento HTML que debe verse así: 

```
<!doctype html>
<html lang="es">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    <title>DNO037</title>
  </head>
  <body>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
  </body>
</html>
```

En el cuerpo de tal documento HTML (`<body></body>`) podemos comenzar a utilizar las clases del CSS de Bootstrap, que nos permiten tomar de 1 a 12 columnas (`class="col"`) en cada fila (`class="row"`) que esté dentro de un contenedor (`class="container"`).

Puesto de otro modo, podemos incluir, entre etiquetas `<body>…</body>`, algo como: 

```
<div class="container">
  <div class="row">
    <div class="col-4">Esto</div>
    <div class="col-4">es</div>
    <div class="col-4">Bootstrap</div>
  </div>
</div>
```

El código recién escrito indica que lo ancho se divide en 3 desde 0 pixeles de ancho. Sería distinto si usara las clases: `col-sm-4`, `col-md-4`, `col-lg-4`, `col-xl-4` o `col-xxl-4`. En todas estoy tomando la misma porción de columnas disponibles, pero lo haría desde distintos tamaños de pantalla: https://getbootstrap.com/docs/5.1/layout/grid/#grid-options

Después de revisar la página recién vinculada, conviene revisar los archivos contenidos en [esta carpeta de repositorio](https://profesorfaco.github.io/dno037-2022/clase-10/index.html), que servirán de base para un "remake" de su prueba. 

Para completar este "remake" conviene tener a mano la [documentación de Bootstrap](https://getbootstrap.com/docs/5.1/getting-started/introduction/).

- - - - - - - 

### Práctica

El ejercicio se completa cuando cada estudiante publique, [con GitHub Pages](https://docs.github.com/es/free-pro-team@latest/github/working-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site), lo preparado en https://profesorfaco.github.io/dno037-2022/clase-10/

El ejercicio completo puede ser evaluado con:

- **0 punto** → no logrado.

- **1 punto** → logrado.

- **2 puntos** → logrado, con aporte descatado.

El ejercicio incompleto es evaluado con 0 punto.

- - - - - - - 

###### [← CLASE ANTERIOR](https://github.com/profesorfaco/dno037-2022/tree/main/clase-09) — [SIGUIENTE CLASE →](https://github.com/profesorfaco/dno037-2022/tree/main/clase-11)
