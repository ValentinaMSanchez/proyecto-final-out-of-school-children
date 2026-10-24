# Evolución de la exclusión escolar infantil 2000–2025

Proyecto final del curso *Programación y análisis reproducible con datos*.
**Autora:** Valentina Merchan Sanchez

## Pregunta de análisis
Entre 2000 y 2025, ¿cómo evolucionó el número de niños en edad de primaria fuera de la escuela en las siete regiones del mundo, y se frenó la reducción global después de 2013 mientras el problema se concentraba en África Subsahariana?

## Datos
- **Dataset:** Out-of-school children of primary school age (Our World in Data)
- **Fuente:** https://ourworldindata.org/grapher/out-of-school-children-of-primary-school-age-by-world-region
- **Productor original:** UNESCO Institute for Statistics (2026)
- **Licencia:** CC BY 3.0 IGO
- **Fecha de descarga:** 20 de octubre de 2026
- El archivo CSV está en este repositorio y el notebook lo carga desde GitHub.

## Contenido del repositorio
- `notebook.ipynb`: notebook con el análisis completo.
- `out-of-school-children-of-primary-school-age-by-world-region.csv`: dataset.
- `requirements.txt`: librerías necesarias.
- `figuras/`: gráficos interactivos exportados en HTML.

## Cómo reproducir el análisis
1. Descarga o clona este repositorio.
2. Crea y activa un entorno virtual (probado con Python 3.15.0):
   ```bash
   python -m venv .venv
   .venv\Scripts\activate
   ```
3. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```
4. Abre el notebook en Visual Studio Code, selecciona el entorno `.venv` como kernel y ejecuta *Run All*.

## Gráficos interactivos
GitHub no muestra los gráficos de Plotly dentro del notebook. Las versiones interactivas estarán aquí cuando activemos GitHub Pages:
- [Evolución por región](https://valentinamsanchez.github.io/proyecto-final-out-of-school-children/figuras/evolucion_por_region.html)
- [Participación por región](https://valentinamsanchez.github.io/proyecto-final-out-of-school-children/figuras/participacion_por_region.html)
