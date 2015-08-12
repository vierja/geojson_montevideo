# GeoJSON Montevideo
#### Archivos en formato GeoJSON del departamento de Montevideo, Uruguay

Utilizando principalmente el [catálogo de datos abiertos](https://catalogodatos.gub.uy/) se descargan, convierten, procesan, limpian para generar los archivos listados.

## direcciones.geojson y direcciones_por_barrio

Listado de direcciones de Montevideo.

- Licencia: Uruguay Open Data Licence
- Fuente: [Catalogo Datos](https://catalogodatos.gub.uy/dataset/direcciones-oficiales-de-montevideo)
- Ejemplo:
```json
{
  "type": "Feature",
  "properties": {
    "gid": 28431,
    "padron": 21537,
    "cod_nombre": 7572,
    "calle": "AV 18 DE JULIO",
    "num_puerta": 2340,
    "letra": "BIS",
    "PARIDAD": null
  },
  "geometry": {
    "type": "Point",
    "coordinates": [
      -56.165166,
      -34.897821
    ]
  }
}
```


## barrios.geojson

Límites de barrios de Montevideo.
![Imgur](http://i.imgur.com/dsb3aCD.png?)

- Licencia: Uruguay Open Data Licence
- Fuente: [Catalogo Datos](https://catalogodatos.gub.uy/dataset/limites-barrios)
- Ejemplo:
```json
{
  "type": "Feature",
  "properties": {
    "id_barrio": 32,
    "nombre": "MANGA TOLEDO CHICO",
    "codigo": "MT"
  },
  "geometry": {
    "type": "Polygon",
    "coordinates": [
      [
        [
          -56.087509,
          -34.779
        ],
        [...]
        [
          -56.091242,
          -34.778686
        ],
        [
          -56.087895,
          -34.77899
        ],
        [
          -56.087509,
          -34.779
        ]
      ]
    ]
  }
}

```


## multas/multas20**.geojson.gz

Multas por año con detalles.

- Licencia: Uruguay Open Data Licence
- Fuente: [Catalogo Datos](https://catalogodatos.gub.uy/dataset/multas-transito)
- Ejemplo:

```json
{
    "geometry": {
        "type": "Point",
        "coordinates": [
            -56.200111,
            -34.908392
        ]
    },
    "type": "Feature",
    "properties": {
        "vehicle_type": "SEDAN 2 PUERTAS",
        "ordinance": {
            "ur_amount": 15,
            "article": 140,
            "paragraph": "1A",
            "id": 1,
            "description": "CONDUCE CON UNA CONCENTRACION DE ALCOHOL EN SANGRE SUPERIOR A LA PERMITIDA MEDIDA MEDIANTE AIRE ESPIRADO, O NEGARSE A REALIZAR LA PRUEBA (D.677)"
        },
        "street_name": "LINIERS",
        "street_id": 3954,
        "date": "2010-12-31T17:30:00-03:00",
        "intersection": {
            "secondary_street_id": 5886,
            "secondary_street_name": "RECONQUISTA"
        },
        "neighbourhood": {
            "name": "CIUDAD VIEJA",
            "id": 1
        }
    }
}
```
