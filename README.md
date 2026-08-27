# Hoja de Vida Web Semántica

**Estudiante:** Valeria Raisa Rodriguez Salgado  
**Carrera:** Ingeniería de Sistemas  
**Institución:** Universidad Católica Boliviana "San Pablo"  
**Semestre:** 4.º Semestre  

---

## Descripción del Proyecto

Este proyecto consiste en una **Hoja de Vida (CV) interactiva y accesible**, desarrollada exclusivamente con **HTML5 nativo**. Su propósito es estructurar de forma profesional la información académica, proyectos universitarios destacados (como *WayFinder* y *Mercado Popular*), competencias técnicas, experiencia laboral e idiomas, aplicando las mejores prácticas de desarrollo web semántico sin depender de frameworks externos.

---

## Etiquetas HTML5 Utilizadas

El documento implementa una estructura modular utilizando las siguientes etiquetas semánticas y elementos multimedia:

* **Estructura Principal:** `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`.
* **Semántica Textual:** `<h1>` a `<h3>`, `<p>`, `<strong>`, `<em>`, `<mark>`, `<abbr>`, `<time>`.
* **Formularios e Interacción:** `<form>`, `<label>`, `<input>` (`text`, `email`, `tel`, `checkbox`), `<textarea>`, `<select>`, `<option>`, `<button>` (`submit`, `reset`), `<details>`, `<summary>`.
* **Datos Tabulares e Indicadores:** `<table>`, `<caption>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`, `<meter>`.
* **Elementos Multimedia:** `<figure>`, `<figcaption>`, `<picture>`, `<img>`, `<audio>`, `<video>`, `<source>`, `<track>`.

---

## Elementos de Accesibilidad Implementados

Para garantizar que el sitio web sea navegable e interpretable por lectores de pantalla y tecnologías de asistencia, se incorporaron las siguientes prácticas:

1. **Atributos WAI-ARIA:** Uso de `aria-labelledby` en las secciones para asociar títulos con sus contenedores principales.
2. **Textos Alternativos:** Inclusión del atributo `alt` descriptivo en todas las imágenes.
3. **Formularios Accesibles:** Vinculación directa entre cada etiqueta `<label>` y su control mediante el atributo `for`.
4. **Fechas Semánticas:** Uso del atributo `datetime` en la etiqueta `<time>` siguiendo el estándar ISO.
5. **Encabezados de Tabla:** Definición explícita de `scope="col"` y `scope="row"` en elementos `<th>`.
6. **Subtítulos y Formatos de Respaldo:** Uso del elemento `<track>` para subtítulos `.vtt` en el reproductor de video.

---

## Instrucciones para Visualizar el Proyecto

No se requieren dependencias externas ni compiladores para ejecutar este proyecto.

1. **Clonar o descargar el repositorio:**
   ```bash
   git clone https://github.com/ValRod-Sal/hoja-vida-Rodriguez-Valeria.git