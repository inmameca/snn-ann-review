# SNN vs. ANN Review Database

**Classification database of 400 articles on Spiking Neural Networks (SNNs), Artificial Neural Networks (ANNs) and neural networks, in Spanish and English.**

This repository contains the working database behind the poster *Neuromorphic Neural Networks for Interconnected AI Systems: A Systematic Review of Models, Hardware, Learning Rules and Networked Applications*, presented at AIxNET 2026.

[English](#english) · [Español](#español)

---

## English

### What this database is

The database collects and classifies 400 scientific articles published between 2017 and 2026 on spiking neural networks, artificial neural networks and their comparison. Each record was documented and checked individually, and every field is given in both Spanish and English.

The database was built as part of a systematic literature review. Its main purpose is to identify the studies that compare SNNs and ANNs directly and empirically. The 66 articles in the category *SNN-ANN comparison* are the core corpus synthesised in the poster.

### Files

| File | Description |
|---|---|
| `Clasificacion_400_articulos_SNN_ANN_bilingue_v.xlsx` | Full database in Excel, with two sheets: the classification of the 400 articles and a summary by category (automatic counts). Links to the full texts are clickable. |
| `Clasificacion_400_articulos_SNN_ANN_bilingue.csv` | Same data as the main Excel sheet, in plain text (UTF-8, comma-separated), so it can be viewed directly on GitHub and opened with any software (R, Python, Excel, LibreOffice). It adds a column with the link to each article. |

### Columns

Every text field contains two lines: the first one starts with `ES:` (Spanish) and the second one with `EN:` (English).

| Column | Content |
|---|---|
| **No.** | Record number (1 to 400). |
| **Author(s) and year** | First author followed by *et al.* when there are several authors, and year of publication. |
| **Title** | Title of the article, in Spanish and English. |
| **Category** | Classification of the article into one of the six categories of the review (see the table below). |
| **Main type** | Type of contribution: direct comparison, ANN→SNN conversion, SNN architecture, applied SNN, applied ANN, neuromorphic/SNN hardware, systematic review or ANN review. |
| **Database** | Bibliographic database where the article is indexed (Web of Science, Scopus, IEEE Xplore) and journal or venue. Articles that are only available as arXiv preprints are marked as not indexed. In some records the database is inferred from the journal. |
| **Keywords** | Keywords of the article. |
| **PDF / Full text** | Indicates whether there is an open-access PDF (*See PDF*), a link to the DOI or publisher page (*See DOI / publication*), or no open-access version (3 records, with the recommended steps to obtain the full text). |
| **Link** (CSV only) | URL of the PDF, DOI or publisher page. In the Excel file the same link is embedded in the previous column. |
| **Usefulness for the review** | Short note on what the article contributes to the review. |

### Categories

| Category | Articles |
|---|---|
| SNN only | 67 |
| ANN only | 67 |
| Hardware / Neuromorphic | 67 |
| Systematic review of neural networks | 67 |
| ANN-SNN conversion | 66 |
| SNN-ANN comparison | 66 |
| **Total** | **400** |

### How to cite

If you use this database, please cite it as:

> Meca, I., Pérez-Sánchez, B., & López-Espín, J. J. (2026). *Classification database of 400 articles on spiking neural networks, artificial neural networks and neural networks (bilingual ES/EN)* [Data set]. GitHub. https://github.com/inmameca/snn-ann-review

And the related poster:

> Meca, I., Pérez-Sánchez, B., & López-Espín, J. J. (2026). *Neuromorphic Neural Networks for Interconnected AI Systems: A Systematic Review of Models, Hardware, Learning Rules and Networked Applications* [Poster]. AIxNET 2026.

### Funding and the GROUNDS project

This activity is part of the project **"Global Resource Optimization Using Novel Data-driven Strategies" (GROUNDS)**, with reference CIPROM/2024/34, funded by the Conselleria de Educación, Cultura y Universidades of the Generalitat Valenciana. GROUNDS develops data-driven strategies for the optimisation of resources; this review explores whether neuromorphic models can provide more energy-efficient and lower-latency AI for that kind of application.

I. Meca is supported by a predoctoral research training contract of the Universidad Miguel Hernández (call PI26/001).

### Licence

The classification, keywords, translations and notes in this database are released under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) licence. Abstracts are not included: each record links to the original publication, where the full article and its abstract can be consulted. Titles remain the property of their respective authors and publishers.

### Contact

[Department of Statistics, Mathematics and Computer Science](https://demi.umh.es/es/), Universidad Miguel Hernández de Elche (UMH), Spain · imeca@umh.es

---

## Español

### Qué es esta base de datos

La base de datos recoge y clasifica 400 artículos científicos publicados entre 2017 y 2026 sobre redes neuronales de impulsos (SNN), redes neuronales artificiales (ANN) y su comparación. Cada registro se ha documentado y verificado uno a uno, y todos los campos aparecen en español y en inglés.

Se construyó dentro de una revisión sistemática de la literatura. Su objetivo principal es identificar los estudios que comparan SNN y ANN de forma directa y empírica. Los 66 artículos de la categoría *Comparación SNN-ANN* forman el corpus central que se sintetiza en el póster.

### Archivos

| Archivo | Descripción |
|---|---|
| `Clasificacion_400_articulos_SNN_ANN_bilingue_v.xlsx` | Base de datos completa en Excel, con dos hojas: la clasificación de los 400 artículos y un resumen por categoría (recuentos automáticos). Los enlaces al texto completo se pueden pulsar. |
| `Clasificacion_400_articulos_SNN_ANN_bilingue.csv` | Los mismos datos de la hoja principal en texto plano (UTF-8, separado por comas), para verlos directamente en GitHub y abrirlos con cualquier programa (R, Python, Excel, LibreOffice). Añade una columna con el enlace a cada artículo. |

### Columnas

Cada campo de texto tiene dos líneas: la primera empieza por `ES:` (español) y la segunda por `EN:` (inglés).

| Columna | Contenido |
|---|---|
| **Nº** | Número de registro (del 1 al 400). |
| **Autor(es) y año** | Primer autor, seguido de *et al.* si hay varios, y año de publicación. |
| **Título** | Título del artículo en español y en inglés. |
| **Categoría** | Clasificación del artículo en una de las seis categorías de la revisión (ver la tabla siguiente). |
| **Tipo principal** | Tipo de aportación: comparación directa, conversión ANN→SNN, arquitectura SNN, SNN aplicado, ANN aplicado, hardware neuromórfico/SNN, revisión sistemática o revisión ANN. |
| **Base de datos (BBDD)** | Base de datos bibliográfica en la que está indexado el artículo (Web of Science, Scopus, IEEE Xplore) y revista o congreso. Los artículos disponibles solo como preprint de arXiv aparecen como no indexados. En algunos registros la base de datos se deduce de la revista. |
| **Palabras clave** | Palabras clave del artículo. |
| **PDF / Texto completo** | Indica si hay un PDF en acceso abierto (*Ver PDF*), un enlace al DOI o a la página de la editorial (*Ver DOI / publicación*) o si no existe versión en abierto (3 registros, con los pasos recomendados para conseguir el texto completo). |
| **Enlace** (solo en el CSV) | Dirección del PDF, del DOI o de la página de la editorial. En el Excel el mismo enlace está incrustado en la columna anterior. |
| **Utilidad para la revisión** | Nota breve sobre lo que aporta el artículo a la revisión. |

### Categorías

| Categoría | Artículos |
|---|---|
| Solo SNN | 67 |
| Solo ANN | 67 |
| Hardware / Neuromórfico | 67 |
| Revisión sistemática de redes neuronales | 67 |
| Conversión ANN-SNN | 66 |
| Comparación SNN-ANN | 66 |
| **Total** | **400** |

### Cómo citarla

Si utilizas esta base de datos, cítala así:

> Meca, I., Pérez-Sánchez, B., & López-Espín, J. J. (2026). *Classification database of 400 articles on spiking neural networks, artificial neural networks and neural networks (bilingual ES/EN)* [Conjunto de datos]. GitHub. https://github.com/inmameca/snn-ann-review

Y el póster relacionado:

> Meca, I., Pérez-Sánchez, B., & López-Espín, J. J. (2026). *Neuromorphic Neural Networks for Interconnected AI Systems: A Systematic Review of Models, Hardware, Learning Rules and Networked Applications* [Póster]. AIxNET 2026.

### Financiación y proyecto GROUNDS

Esta actividad forma parte del proyecto **"Global Resource Optimization Using Novel Data-driven Strategies" (GROUNDS)**, con referencia CIPROM/2024/34, financiado por la Conselleria de Educación, Cultura y Universidades de la Generalitat Valenciana. GROUNDS desarrolla estrategias basadas en datos para optimizar recursos, y esta revisión estudia si los modelos neuromórficos pueden ofrecer una inteligencia artificial más eficiente en energía y con menor latencia para ese tipo de aplicaciones.

I. Meca cuenta con un contrato predoctoral de formación de personal investigador de la Universidad Miguel Hernández (convocatoria PI26/001).

### Licencia

La clasificación, las palabras clave, las traducciones y las notas de esta base de datos se publican con la licencia [Creative Commons Reconocimiento 4.0 Internacional (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.es). No se incluyen los resúmenes: cada registro enlaza con la publicación original, donde pueden consultarse el artículo completo y su resumen. Los títulos pertenecen a sus autores y editoriales.

### Contacto

[Departamento de Estadística, Matemáticas e Informática](https://demi.umh.es/es/) de la Universidad Miguel Hernández de Elche (UMH), España · imeca@umh.es
