# html_cero

1. Dentro de HTML, las mayúsculas en las etiquetas de HTML, no pasa nada si se escribe en mayúsculas, pero es recomendable escribir en minúsculas

2. Comillas dobles o comillas sencillas: En todo lenguaje de programación hay eventos, los cuales nos permiten visualizar lo que esta pasando o lo que se ve en el programa.

- Mouse Over
- Mouse Move
- Mouse Click

HTML no tiene conflicto con un valor al momento de darle un **name = valor**, aunque, solo leerá el primer valor, y si escribes otro, este no lo leerá

```html
<p tittle = Este es el titulo> Este es un parrafo </p>
```

Como ves, aqui solo leerá **Este**, ya que es el primer valor.

Si quieres que lea todos los valores o palabras, puedes ponerlo con comillas dobles o comillas sencillas:

```html
<p tittle = "Este es el titulo"> Este es un parrafo </p>
```

Para que te salga una image, es mediante este código:
```html
<img src = "static/images/golden-retriever.webp" />
```

Das la ruta donde se encuentra la imagen y pones el nombre de la imagen
(Las rutas absolutas y relativas puedes ponerlas gracias a **src**)