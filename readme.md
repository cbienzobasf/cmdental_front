# Proyecto CMDental - Entrega Final

Autor: Carlos Biénzobas

## URL Web Live en Github

[Repositorio del proyecto CMDental](https://github.com/cbienzobasf/cmdental_front)
Branch: Main

## Contribución

Proyecto realizado 100% por **Carlos Bienzobas** como parte del curso de Desarrollo Web, Comisión 59900, Coder House.

## Descripción General

CMDental es una plataforma web diseñada para un centro dental que ofrece servicios odontológicos integrales. El proyecto incluye información sobre los dentistas, especialidades, sucursales, y una interfaz de acceso para usuarios. Este README resume las correcciones realizadas en base a las entregas anteriores y las optimizaciones aplicadas.

Nota: Con la finalidad de facilitar la revisión y análisis del presente proyecto, el seguimiento de avance, trabazabilidad de cambios y mejoras, es que se incluyo dentro del presente repositorio los **readme.md** de las entregas anteriores en la carpeta **"readme_old_versions"**. Adicionalmente,en caso de requerir mayor información, la totalidad del contenido de las entregas anteriores se encuentra en las branchs **"pre-entrega01"**, **"pre-entrega02"** y **"pre-entrega03"** respectivamente.

## Principales cambios realizados respecto de tercera entrega

### 1. `index.html`
- **Meta descripción**: `"CMDental: Centro Odontológico Integral ofreciendo servicios dentales de calidad en Santiago."`
- **Optimización de accesibilidad**: Se añadieron atributos `aria-label` y textos alternativos en imágenes.
- **Corrección de enlaces**: Los enlaces fueron revisados para ser rastreables por motores de búsqueda.

### 2. `dentistas.html`
- **Meta descripción**: `"Equipo de dentistas altamente capacitados en CMDental."`
- **Accesibilidad mejorada**: Atributos `aria-label` y y textos alternativos en imágenes.
- **Jerarquía de encabezados**: Corregida para un mejor SEO.

### 3. `especialidades.html`
- **Meta descripción**: `"Nuestras especialidades dentales incluyen ortodoncia, endodoncia, periodoncia."`
- **Corrección de enlaces** y **jerarquía de encabezados**: Enlaces rastreables y mejor jerarquía en títulos.

### 4. `sucursales.html`
- **Meta descripción**: `"CMDental cuenta con sucursales en Santiago y alrededores."`
- **Google Maps accesible**: Uso de `aria-label` para describir los mapas.
- **Corrección de enlaces y jerarquía**: Ajustes para mejor SEO.

### 5. `login.html`
- **Meta descripción**: `"Accede a tu cuenta en CMDental."`
- **Mejoras en accesibilidad**: Atributos `aria-label` para los campos de formulario y corrección de enlaces.

## Cobertura a los Puntos de Mejora en Entregas Anteriores

### 1. **SEO**:
- Todas las páginas incluyen **meta descripciones** optimizadas para mejorar la visibilidad en los motores de búsqueda.
- Se aseguraron **títulos** y jerarquías para favorecer el SEO en todas las páginas.
- Los **enlaces** en cada página son ahora completamente rastreables, lo que resuelve el problema de enlaces no "crawlable" de acuerdo a retroalimentación de análisis Lighthouse.

### 2. **Accesibilidad**:
- Se aplicaron mejoras significativas en la **accesibilidad**, asegurando que cada imagen tenga un **texto alternativo**.
- Se utilizaron **etiquetas `aria-label`** en los botones de navegación, mapas, entre  otros.
- Formularios y campos con etiquetas y atributos **accesibles**.

### 3. **Optimización de Código**:
- **HTML** y **CSS** fueron optimizados eliminando redundancias.
- Se estructuraron los estilos en **SCSS**, facilitando la escalabilidad y mantenimiento del proyecto.

## Estado Final del Proyecto

El proyecto ha sido optimizado, alcanzando un **100% en Lighthouse** para SEO y sobre 90% para accesibilidad en todas las páginas principales. Esto garantiza que el sitio es accesible, eficiente en términos de SEO, y tiene un rendimiento adecuado para su explotación.

## Tecnologías Utilizadas
- **HTML5**, **CSS3**, **Bootstrap 5**
- **SCSS** para modularidad en estilos
- **Google Maps API** en la página de sucursales
- **Lighthouse** para auditoría de SEO, accesibilidad y rendimiento

**Nota:** Para mayor información sobre los cambios realizados, actualización del proyecto en base a feedback de entregas anteriores y racional sobre el cumplimiento de los criterios de evaluación, por favor referise a documentos ubicados en carpeta **info_extra** 
