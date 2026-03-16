# GRUPO C

Contexto: una empresa industrial recopila datos de sensores ambientales distribuidos por distintas zonas de una planta.

Base de datos: `iot`
Colección: `sensores`

## Pregunta 1 (1 punto)

Un sistema analiza ​grandes volúmenes de datos de sensores para analítica a gran escala​.
Indique ​el tipo de base de datos más adecuado para este tipo de análisis​.

## Pregunta 2 (1 punto)

Insertar en la colección `sensores` el siguiente documento:

```JS
sensor_id: "S500"
temperatura: 24
humedad: 60
zona: "planta"
```

## Pregunta 3 (1 punto)

Consultar los sensores ubicados en la zona `"planta"` mostrando ​solo​:

```JS
sensor_id
temperatura
```

## Pregunta 4 (1 punto)

Actualizar el sensor `"S500"` para que su temperatura sea ​25​.

## Pregunta 5 (2 puntos)

Utilizando ​Aggregation Framework​, calcular la ​temperatura promedio por zona​.

## Pregunta 6 (1 punto)

Crear un índice sobre el campo:

```JS
zona
```

## Pregunta 7 (1 punto)

Crear un índice compuesto sobre:

```JS
zona + temperatura
```

## Pregunta 8 (1 punto)

Ejecutar `explain("executionStats")` sobre la consulta que busca sensores en la zona `"planta"`.

## Pregunta 9 (1 punto)

Realizar una consulta que devuelva ​solo el campo `sensor_id` de todos los sensores​.

