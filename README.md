# Reddit Downloader

Esta herramienta de línea de comandos permite descargar imágenes y videos de publicaciones de usuarios o subreddits específicos en Reddit.

## Características

-   Descarga imágenes y videos de publicaciones de un usuario de Reddit.
-   Descarga imágenes y videos de publicaciones de un subreddit específico.
-   Crea un directorio con el nombre del usuario o subreddit para organizar las descargas.


## Requisitos

-   Python 3.6+
-   Dependencias listadas en `requirements.txt` (instalar con `pip install -r requirements.txt`).

## Instalación

1.  Clona el repositorio:

    ```bash
    git clone https://github.com/DanielRodZa/RedditScraper.git
    cd reddit-downloader
    ```

2.  Crea un entorno virtual (recomendado):

    ```bash
    python3 -m venv venv
    source venv/bin/activate  # En Linux/macOS
    venv\Scripts\activate  # En Windows
    ```

3.  Instala las dependencias:

    ```bash
    pip install -r requirements.txt
    ```

## Uso

### Descargar contenido de un usuario de Reddit

```bash
python main.py -u <nombre_de_usuario>
```