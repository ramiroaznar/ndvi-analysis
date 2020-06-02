# Análisis de imágenes de satélite con Python notebooks
## https://go.planet.com/ndvi-analysis

* Autor: Ramiro Aznar
* [Webinar link](https://www.unigis.es/webinar-analisis-de-imagenes-de-satelite-con-python-notebooks/) 

## Instrucciones

1. Crear una cuenta en https://www.planet.com
2. Obtener tu Planet API Key en tu perfil en https://www.planet.com/explorer/
3. Clonar este repositorio y dirígente a la carpeta

```bash
$ git clone https://github.com/ramiroaznar/ndvi-analysis.git
$ cd ndvi-analysis/
```

1. Crea un entorno virtual y lanza jupyter

```bash
$ virualvenv -p python3 env
$ source env/bin/activate
```

5. Guarda to Planet API Key como variable de entorno

```bash
$ export PL_API_KEY=XXXXXXXXXXXXXXXXXXXXXXXXX
```

6. Lanza jupyter

```bash
$ jupyter notebook
```

7. Haz click en `ndvi.ipynb` y corre el notebook
