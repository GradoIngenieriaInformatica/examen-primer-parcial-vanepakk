# GRUPO A

## Pregunta 1 (1 punto)

Una universidad necesita analizar ​relaciones entre investigadores, publicaciones y citas académicas​.

Indique ​el tipo de base de datos más adecuado​.

## Pregunta 2 (1 punto)

Insertar en la colección `cursos` el documento:

```JS
nombre: "Arquitectura de Software"
nivel: "avanzado"
creditos: 6
departamento: "Informatica"
profesor: "Dr. Lopez"
```

## Pregunta 3 (1 punto)

Consultar los cursos de nivel `"avanzado"` mostrando ​solo nombre y profesor.

## Pregunta 4 (1 punto)

Actualizar el curso `"Arquitectura de Software"` para que tenga ​7 créditos​.

## Pregunta 5 (2 puntos)

Usando ​Aggregation Framework, calcular el ​total de créditos por nivel​.

## Pregunta 6 (1 punto)

Crear un índice sobre el campo:

```JS
nivel
```

## Pregunta 7 (1 punto)

Crear un índice compuesto sobre:

```JS
nivel + creditos
```

## Pregunta 8 (1 punto)

Ejecutar `explain("executionStats")` sobre la consulta de cursos `"avanzado"`.

## Pregunta 9 (1 punto)

Realizar una consulta que devuelva ​solo el campo nombre de todos los cursos*.

