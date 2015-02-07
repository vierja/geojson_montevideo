# GeoJSON Montevideo
#### Archivos en formato GeoJSON del departamento de Montevideo, Uruguay

Utilizando principalmente el [catálogo de datos abiertos](https://catalogodatos.gub.uy/) se descargan, convierten, procesan, limpian para generar los archivos listados.

## direcciones.geojson

Listado de direcciones de Montevideo.  

Licencia: Uruguay Open Data Licence  
Fuente: [Catalogo Datos](https://catalogodatos.gub.uy/dataset/direcciones-oficiales-de-montevideo)   
Ejemplo:  
```
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

Licencia: Uruguay Open Data Licence  
Fuente: [Catalogo Datos](https://catalogodatos.gub.uy/dataset/limites-barrios)   
Ejemplo:  
```
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
