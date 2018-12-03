# GSS-mtig-18-19

[https://gss-mtig.github.io/gss-mtig-18-19/](https://gss-mtig.github.io/gss-mtig-18-19/)

## Temario

* Introducción a las Smart Cities
    * Conceptos Smart Cities
    * Conceptos Open Data
    * Conceptos sensores
    * Tecnologías OpenData

* API servicios Open data (CKAN y SOCRATA)
* Conceptos VectorTiles
* Visualización con Kepler.gl


* Herramientas de visualización de datos
* Conceptos básicos de Geoservicios
* Servicios realtime Open data
* Ejemplo servicio bicing Barcelona (se podría adaptar a vector tiles)
* Servicios realtime sensores
* Ejemplo sensores port Barcelona
* Ejemplo Sentilo ACA
* Geoservicios realtime
* Herramientas de visualización geoservicios
* Ejemplo de Geocodificador
* Ejemplo Isócronas (cambiar por https://openrouteservice.org o https://graphhopper.com)
* Ejemplo Creación de geoservicio realtime para compartir ubicación del usuario
* Ejemplo GTFS (Google transit)

## Entorno

Se puede crear un entorno para generar la documentación instalando [Anaconda](https://www.anaconda.com/)

Una vez instalado el Anaconda crear un *enviroment* donde instalar el mkdocs

Para crear el *enviroment* abrir la consola de Anaconda y escribir
```bash
conda create --name <NOMBRE_DEL_ENVIROMENT>
```

Para activar el nuevo *enviroment* escribir
```bash
conda activate <NOMBRE_DEL_ENVIROMENT>
```

### Herramienta de documentación

Se usa [mkdocs](http://mkdocs.org) con el tema [mkdocs-material](https://squidfunk.github.io/mkdocs-material/).

Desinstalar versiones anteriores de mkdocs:

```bash
    sudo pip uninstall mkdocs
```

E instalar con el comando:

```bash
pip install mkdocs-material
```

### Comandos mkdocs

* `mkdocs serve`: Arranca un servidor web con auto-recarga.
* `mkdocs build`: Compila la documentación en html.
* `mkdocs gh-deploy`: Publica la documentación en gh-pages.

### Layout

    mkdocs.yml    # El fichero de configuración.
    docs/
        index.md  # La portada.
        ...       # Otras páginas en markdown, imágenes, etc.

### Markdown

* Chuleta rápida sobre links, imágenes y tablas en markdown: http://www.mkdocs.org/user-guide/writing-your-docs/#linking-documents
* [Especificación Markdown](http://spec.commonmark.org/0.28/) completa.
* Visual Studio Code ofrece una vista de Preview que va mostrando el resultado del markdown en tiempo real sin tener que salir del editor.
