# CMDental Web Project

## URL Web Live Github

https://cbienzobasf.github.io/dfront/

## Contribución

Proyecto realizado por **Carlos Bienzobas** como parte de curso Desarrollo Web, pre-entrega 02 (continuación de trabajo tratado en pre-entrega 01), comisión 59900, Coder House.

## Descripción

Este proyecto consiste en la construcción de un sitio web para un centro odontologico ficticio llamado "CMDental", ubicado en Santiago de Chile. El sitio está diseñado para proporcionar información a los usuarios sobre dentistas, especialidades y sucursales. 

El sitio está desarrollado utilizando **HTML5**, **CSS**, y **Bootstrap 5**, donde a diferencia de la entrega anterior (pre-entrega 01), se migra la mayoria del estilo de la página web hacia las clases base de bootstrap, con puntuales modificaciones por medio de personalización en CSS.

Nota: Es importante señalar, que la metodologia principal seguida para la gestión de estilos es kebab-case o dash-case, la cual es utilizada por bootstrap.

El proyecto se basa en  Bootstrap Grid y Flexbox para gestionar el layout responsivo y la alineación de su contenido, apuntando a  la simplicidad y reutilización de las clases predefinidas.

## Estructura

El proyecto consta de las siguientes páginas:

- **Index.html**: Página de inicio con una presentación general sobre el centro dental.
- **dentistas.html**: Página que presenta a los dentistas del centro, sus especialidades y formación.
- **especialidades.html**: Página que presenta las especialidades ofrecidas en el centro.
- **sucursales.html**: Página que presenta las diferentes sucursales disponibles del centro dental.
- **login.html**: Página para el inicio de sesión de usuarios para permitir modificaciones a la información previamente presentada.

Incluye archivo CSS (`styles.css`) con estilos personalizados para ajustar la apariencia base otorgada por las clases de bootstrap, a una  apariencia y funcionalidad acorde las necesidades del centro dental.

## Uso de Bootstrap

Bootstrap 5 se ha utilizado ampliamente en este proyecto para asegurar un diseño responsivo y consistente en todas las páginas, migrando la gran mayoria de configuración realizada en la entrega anterior a dicho framework. A continuación, algunas de las principales clases y componentes de Bootstrap utilizados:

1. **Navbar**:
    - Utilizado para geestinar una barra de navegación responsiva.
    - Clases usadas: `navbar`, `navbar-expand-lg`, `container-fluid`.

2. **Grid System**:
    - Grillas de Bootstrap se han utilizado para estructurar las diferentes secciones de contenido en cada pagina web del sitio.
    - Clases usadas:`row`, `col-12`, `col-md-6`

3. **Flexbox y alineamiento de contenido**:
    - Se ha utilizado para alinear y distribuir elementos dentro de contenedores.
    - Clases usadas: `d-flex`, `justify-content-center` y `align-items-center`

4. **Botones**:
    - Utilizado clase de botones de bootstrap en las páginas para mantener un diseño consistente y a su vez personalizado mediante `btn-custom` apoyado por CSS.
    - Clases usadas:`btn` `btn-custom`
  
5. **Formularios**:
    - Componentes de formularios de Bootstrap para estructurar los campos de usuario y contraseña.
    - Clases usadas:`form-control`, `col-form-label`

6. **Aspect Ratio**:
    - Utilizado para manejar la relación de aspecto de video incrustado en la página de inicio, manteniendo una relación de aspecto de 16:9.
    - Clases usadas: `ratio`

## Estilos Personalizados (CSS)

Estilos personalizados en el archivo `styles.css` para ajustar la apariencia del sitio por sobre las clases base de bootstrap, adaptandolo a la necesidades del centro dental:

- **Colores personalizados**:
    - : Se han aplicado colores de fondo y texto personalizados.
    - Clases usadas:`custom-navbar`, `custom-footer` `custom-link`, `custom-login`, `custom-name`, `bg-custom-1`
  
- **Efectos**:
    - Se han aplicado efectos de flotación y sombras.
    - Clases usadas:`custom-link:hover`, `btn-custom:hover`
  
- **Mapa de Google**:
    - Se ha integrado un mapa de Google.
    - Clases usadas: (`map-container`).


## Recursos

- **Bootstrap 5**: [Documentación Oficial](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
- **Font Awesome**: [Documentación Oficial](https://fontawesome.com/)
- **Google Maps Embed**: [Documentación Oficial](https://developers.google.com/maps/documentation/embed/)

