# Pokemon-Tracker

El repositorio **Pokemon-Tracker** es una herramienta desarrollada en Python que te permite recopilar información de combates Pokémon VGC en la plataforma de simulación de batallas Pokémon Showdown. Esta herramienta te ayuda a realizar estadísticas sobre tus combates, lo que resulta especialmente valioso para aquellos que participan en torneos de Pokémon VGC.

## Propósito

El propósito principal de este repositorio es proporcionar a los jugadores de Pokémon VGC una forma eficiente de recopilar datos de sus combates en Pokémon Showdown. La información recopilada puede ser utilizada para realizar análisis y mejorar la estrategia en futuros combates. Esta herramienta está diseñada para ayudar a los jugadores a prepararse mejor para sus enfrentamientos, entender sus matchups y adaptarse más eficazmente.

## Contenido Principal

El repositorio contiene tres archivos principales:

1. **pokemon_tracker.py**: Este archivo permite abrir una ventana del navegador con Pokémon Showdown y rastrear el chat de los combates que juegas en esa ventana. Los datos recopilados se guardan en archivos de registro de texto.

2. **conversion_datos.py**: Este archivo toma los registros de texto generados por `pokemon_tracker.py` y extrae los datos relevantes. Luego, convierte estos datos en un archivo JSON que es más fácil de manejar y analizar.

3. **stats_datos.py**: Este archivo permite crear gráficos y visualizaciones a partir de los datos almacenados en formato JSON. Proporciona una representación visual de las estadísticas de tus combates.

## Características Clave

- Automatización de la recopilación de datos de combates Pokémon VGC en Pokémon Showdown.
- Proceso dividido en tres pasos: rastreo de chat, conversión a JSON y visualización de estadísticas.
- Permite una mejor preparación para enfrentamientos futuros al analizar y comprender los patrones en tus combates.

## Ejemplos Visuales

A continuación, se presentan ejemplos visuales de los gráficos generados por la herramienta Pokemon-Tracker. Estos gráficos te ayudarán a comprender mejor tus estadísticas de combate y mejorar tu estrategia en Pokémon VGC.

### Ejemplo de Gráfico de apariciones de pokemon rivales en derrotas

![Gráfico de Tipo de Victoria](/images/Pokemon_Tracker1.JPG)
*Este gráfico muestra la distribución de los pokemon que estaban en el equipo rival en una derrota. Puede ayudar a identificar los pokemon con los que más sufres.*

## Bibliotecas Requeridas

- **Selenium**: Biblioteca de automatización de navegadores web, utilizada para rastrear el chat de los combates en Pokémon Showdown.
- **BeautifulSoup**: Biblioteca para analizar y extraer información de documentos HTML y XML, utilizada para procesar los datos recopilados.
- **Pandas**: Biblioteca para el análisis y manipulación de datos, utilizada para gestionar los datos de los combates.
- **Matplotlib**: Biblioteca para la visualización de datos en gráficos, utilizada para crear visualizaciones visuales de las estadísticas de los combates.
- **Seaborn**: Biblioteca de visualización de datos basada en Matplotlib, utilizada para mejorar la estética de las visualizaciones.

## Requisitos de Instalación

Asegúrate de tener Python instalado en tu sistema. Además, instala las siguientes bibliotecas usando `pip`:

```bash
pip install selenium beautifulsoup4 pandas matplotlib seaborn
