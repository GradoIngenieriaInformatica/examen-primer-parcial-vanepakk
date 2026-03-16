# GRUPO D

Contexto: una biblioteca digital gestiona un catálogo de libros técnicos.

Base de datos: `biblioteca`
Colección: `libros`

## Pregunta 1 (1 punto)

Un sistema de búsqueda permite encontrar documentos mediante ​embeddings semánticos​.
Indique ​el tipo de base de datos más adecuado para este tipo de búsqueda​.

## Pregunta 2 (1 punto)

Insertar en la colección `libros` el documento:

```JS
titulo: "Sistemas Distribuidos"
autor: "Ana Torres"
anio: 2022
categoria: "informatica"
```

## Pregunta 3 (1 punto)

Consultar los libros de categoría `"informatica"` mostrando ​solo​:

```JS
titulo
autor
```

## Pregunta 4 (1 punto)

Actualizar el libro `"Sistemas Distribuidos"` para que su ​año sea 2023​.

## Pregunta 5 (2 puntos)

Utilizando ​Aggregation Framework​, calcular el ​total de libros por categoría​.

## Pregunta 6 (1 punto)

Crear un índice sobre el campo:

```JS
categoria
```

## Pregunta 7 (1 punto)

Crear un índice compuesto sobre:

```JS
categoria + anio
```

## Pregunta 8 (1 punto)

Ejecutar `explain("executionStats")` sobre la consulta de libros de categoría `"informatica"`.

## Pregunta 9 (1 punto)

Realizar una consulta que devuelva ​solo el campo `titulo` de todos los libros​.

