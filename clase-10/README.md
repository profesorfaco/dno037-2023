### Diseño y Nuevos Medios → Clase 10 → 10/05/2023

# Bootstrap v5.3

### Teoría

[Bootstrap](https://getbootstrap.com/) es un kit de herramientas de código abierto para la implementación de diseño [responsive](https://es.wikipedia.org/wiki/Dise%C3%B1o_web_adaptable) y [mobile-first](https://en.ryte.com/wiki/Mobile_First) de sitios y aplicaciones web. 

Con [Bootstrap](https://getbootstrap.com/) puedes implementar tanto prototipos rápidos como productos acabados, esto mediante el uso de Elementos de HTML5 relacionados con reglas de CSS3 predefinidas con [Sass](https://sass-lang.com/), además de una biblioteca de Javascript. Nosotros trabajaremos con [la más reciente](https://getbootstrap.com/docs/versions/), la quinta versión (punto tres). 

Hay distintas maneras de comenzar a trabajar con Boostrap v5.3. Nosotros podemos partir con una adaptación de la [Starter template](https://getbootstrap.com/docs/5.3/getting-started/introduction/#quick-start), con un documento HTML que debe verse así: 

```
<!doctype html>
<html lang="es">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>DNO037</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD" crossorigin="anonymous">
  </head>
  <body>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js" integrity="sha384-w76AqPfDkMBDXo30jS1Sgez6pr3x5MlQ1ZAGC+nuZB+EYdgRZgiwxhTBTkF7CXvN" crossorigin="anonymous"></script>
  </body>
</html>
```

Pueden copiar y pegar el código en un documento nuevo, credo en su editor de código fuente. Pueden guardar tal documento como `bootstrap.html`.

En el cuerpo del mismo documento HTML (`<body></body>`) podemos comenzar a utilizar las clases del CSS de Bootstrap, las que nos permiten tomar de 1 a 12 columnas (`class="col"`) en cada fila (`class="row"`) que esté dentro de un contenedor (`class="container"`).

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

El código recién escrito indica que lo ancho se divide en 3 desde 0 pixeles de ancho. Sería distinto si usara las clases: `col-sm-4`, `col-md-4`, `col-lg-4`, `col-xl-4` o `col-xxl-4`. Por ejemplo, dentro de la división de clase `row`, podrían incluir:

```
<div class="col-lg-4"><img src="https://picsum.photos/300/300?random=1" class="w-100 my-2 shadow" /></div>
<div class="col-lg-4"><img src="https://picsum.photos/300/300?random=2" class="w-100 my-2 shadow" /></div>
<div class="col-lg-4"><img src="https://picsum.photos/300/300?random=3" class="w-100 my-2 shadow" /></div>
```

Nuevamente tomo 3 veces 4 columnas de las 12 disponibles; por ello tengo 3 imágenes en una misma fila en pantallas grandes (`-lg-`, de *large*), esto exige un ancho de la ventana del navegador igual o mayor a 992px.

Para más detalles sobre tamaños, conviene consultar directamente a la documentación de Bootstrap: https://getbootstrap.com/docs/5.3/layout/grid/#grid-options


- - - - - - - 

### Práctica

Los archivos contenidos en [esta carpeta de repositorio](https://profesorfaco.github.io/dno037-2023/clase-10/index.html) servirán de base para un "remake" de su prueba. 

Para completar este "remake" conviene tener a mano la [documentación de Bootstrap](https://getbootstrap.com/docs/5.1/getting-started/introduction/).

El ejercicio se completa cuando cada estudiante publique, [con GitHub Pages](https://docs.github.com/es/free-pro-team@latest/github/working-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site), lo preparado en https://profesorfaco.github.io/dno037-2023/clase-10/

El ejercicio completo puede ser evaluado con:

- **0 punto** → no logrado.

- **1 punto** → logrado.

- **2 puntos** → logrado, con aporte descatado.

El ejercicio incompleto es evaluado con 0 punto.

- - - - - - - 

###### [← CLASE ANTERIOR](https://github.com/profesorfaco/dno037-2023/tree/main/clase-08) — [SIGUIENTE CLASE →](https://github.com/profesorfaco/dno037-2023/tree/main/clase-11)
