# FORM-IC-01 — Arquitecturas Distribuidas en la Industria

Investigación individual de Aplicaciones Distribuidas.

- **Estudiante:** Muñoz Vera Melanie Michelle.
- **Semana:** 5, del 23 al 29 de noviembre de 2026.
- **Cierre:** sábado 28 de noviembre de 2026, a las 23:59 (Ecuador).
- **Actividad vinculada:** preparación del informe TA-IND-02.

## Estado

Repositorio inicial. Están pendientes la elección del estilo arquitectónico y de la empresa, y el registro del caso en el foro del SGA para comprobar su disponibilidad.

El análisis tendrá una página, sin contar carátula ni referencias. Se desarrollarán la descripción y escala del caso, la arquitectura anterior y el motivo del cambio, los beneficios, los desafíos y su aplicación al PFC.

## Organización

```text
docs/          Fuentes LaTeX, bibliografía y PDF del informe
evidencias/    Capturas originales de lectura de la fuente principal
```

Los archivos previstos son `docs/informe.tex`, `docs/referencias.bib` y `docs/informe.pdf`. Todavía no se han creado; esta estructura se completará con los avances reales de la investigación.

## Compilación prevista

**Compilador:** pdfLaTeX. **Bibliografía:** Biber con `biblatex` y estilo IEEE.

**Archivo principal:** `docs/informe.tex`.

Una vez añadidos los archivos del informe, ejecutar desde la raíz del repositorio:

```text
cd docs
pdflatex -interaction=nonstopmode -halt-on-error informe.tex
biber informe
pdflatex -interaction=nonstopmode -halt-on-error informe.tex
pdflatex -interaction=nonstopmode -halt-on-error informe.tex
```

Se necesita TeX Live o MiKTeX con pdfLaTeX y Biber. Para la plantilla se prevén los paquetes `fontenc`, `babel` (español), `geometry`, `graphicx`, `csquotes`, `biblatex`, `biblatex-ieee` e `hyperref`. Las dependencias se ajustarán al documento final. Debe conservarse la estructura de carpetas para cargar las capturas.

## Comprobaciones antes de entregar

- Registrar en el foro del SGA una empresa que no esté reservada por otro estudiante.
- Usar una fuente oficial verificable del caso y al menos dos referencias académicas de los últimos cinco años.
- Abrir cada DOI y contrastar autores, año, título, publicación, volumen y páginas o número de artículo con la obra real.
- Incluir una captura original de la fuente principal con los fragmentos subrayados o anotados por la estudiante.
- Incorporar un ejemplo de un sistema conocido de primera mano y justificar la relación con el estilo analizado.
- Comprobar que el análisis ocupa una página y que el PDF se regenera a partir de los archivos publicados.
- Documentar el uso de IA que corresponda al trabajo realizado.

Este repositorio no contiene todavía resultados, referencias ni evidencias de una investigación completada.
