# CMDental Web Project

## URL Web Live Github

https://github.com/cbienzobasf/dental_front

## Contribución

Proyecto realizado por **Carlos Bienzobas** como parte de curso Desarrollo Web, pre-entrega 03 (continuación de trabajo tratado en pre-entrega 02), comisión 59900, Coder House.

## Descripción

Este proyecto consiste en la construcción de un sitio web para un centro odontologico ficticio llamado "CMDental", ubicado en Santiago de Chile. El sitio está diseñado para proporcionar información a los usuarios sobre dentistas, especialidades y sucursales. 

El sitio está desarrollado utilizando **HTML5**, **CSS**, **SASS** y **Bootstrap 5**, donde a diferencia de la entrega anterior (pre-entrega 02), se construyen los estilos personalizados de la página web por medio de **SASS** y sus archivos .scss para su posterior compilación en el archivo **CSS**, se utilizan las clases base de **bootstrap** directamente en los archivos HTML, y configuran efectos/animaciones de CSS provenientes de **animista.net**.

Nota: Es importante señalar, que la metodologia principal seguida para la gestión de estilos es kebab-case o dash-case, la cual es utilizada por bootstrap.

El proyecto se basa en  Bootstrap Grid y Flexbox para gestionar el layout responsivo y la alineación de su contenido, apuntando a  la simplicidad y reutilización de las clases predefinidas.

Sass actúa como un preprocesador que toma el código escrito en .scss previamente consolidado en el archivo styles.scss y lo compila en un archivo .css estándar que los navegadores pueden interpretar.

## Estructura

El proyecto consta de las siguientes páginas:

- **Index.html**: Página de inicio con una presentación general sobre el centro dental.
- **dentistas.html**: Página que presenta a los dentistas del centro, sus especialidades y formación.
- **especialidades.html**: Página que presenta las especialidades ofrecidas en el centro.
- **sucursales.html**: Página que presenta las diferentes sucursales disponibles del centro dental.
- **login.html**: Página para el inicio de sesión de usuarios para permitir modificaciones a la información previamente presentada.

Archivos **.scss** en la carpeta **src**:

- **dentistas**: Archivo gestor de estilos y animaciones especificas para página de dentistas. Sin registros por el momento, sus estilos y animaciones son transversales al proyecto y por ende estan definidas en la hora de styles directamente.
- **especialidades**: Archivo gestor de estilos y animaciones especificas para página de especialidades. Sin registros por el momento, sus estilos y animaciones son transversales al proyecto y por ende estan definidas en la hora de styles directamente.
- **footer**: Archivo gestor de estilos y animaciones especificas para sección footer (pié de página).
- **inicio**: Archivo gestor de estilos y animaciones especificas para página de index.
- **login**: Archivo gestor de estilos y animaciones especificas para página de login.
- **navbar**: Archivo gestor de estilos y animaciones especificas para sección navbar (barra de navegación).
- **sucursales**: Archivo gestor de estilos y animaciones especificas para página de sucursales.
- **styles**: Archivo gestor de estilos y animaciones comunes a todas las paginas del proyecto. Este archivo consolida tambien todo el contenido de los los archivos especificos para secciones o paginas previamente descritos.

Archivo **.css** en la carpeta **dist**:

- **styles**: Contedor final de la totalidad de estilos y animaciones personalizadas para el presente proyecto previamente construidos y definidos en los archivos sass ya descritos.El archivo CSS (`styles.css`) contiene los estilos personalizados para ajustar la apariencia base otorgada por las clases de bootstrap, a una  apariencia y funcionalidad acorde las necesidades del centro dental.

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

## Utilización de Saas

Se ha migrado el sistema de estilos a Sass (Syntactically Awesome Stylesheets), lo que ha permitido una mejor organización y utilización del código CSS. A continuación los principales usos aplicados al presente proyecto:

- **Variables**: Se han definido variables para colores, como **primary-color** y **secondary-color**, lo que facilita la modificación global del del proyecto de manera rápida.
- **Anidación**: Se ha utilizado anidación en algunos selectores para reducir la redundancia del código y mejorar la legibilidad.
- **Partición de estilos**: Se ha organizado los estilos en diferentes archivos parciales de Sass (_navbar.scss, _footer.scss, _login.scss, etc.), que se combinan en un solo archivo **styles.scss** para facilitar su gestión y mantenimiento.

## Animaciones y Efectos CSS

Como parte de los temas a tratar en la presente entrega, se han implementado varios efectos y animaciones CSS, para asi, darle un toque más dinámico al proyecto. A continuación los principales efectos y animiaciones utilizadas:

- **Animaciones de carga**: Se han implementado efectos de entrada, como slide-in-left y slide-in-right, para que los elementos se desplacen desde los lados al entrar en la vista del usuario.

- **Zoom en imágenes**: Las imágenes ahora tienen un efecto de aumento leve cuando el usuario pasa el mouse sobre ellas.

- **Efectos de hover en enlaces**: Proveniente de la entrega anterior, Se ha mantenido la  personalización de los enlaces de navegación con un efecto de cambio de color y sombra al pasar el mouse sobre los mismos (hover).

## Cambios adicionales y personalización

- **Video de Fondo - Página de Login**: Se ha añadido un video de fondo en la página de Login (inicio de sesión), lo que le otorga un aspecto más moderno y fluido. El video se reproduce en bucle y se ha configurado con una transparencia/opacidad al 70% con el fondo blanco para que el contenido sea fácilmente visible.

- **Transparencia en Navbar**: El navbar ahora es fijo y semi-transparente, trabajando la transparencia/opacidad al 20% de modo que permanece visible al desplazarse por la página.

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
- **Sass**: [Documentación Oficial](https://sass-lang.com/)
    Sass es un preprocesador de CSS que permite el uso de variables, anidación, y partición de estilos, facilitando la organización y mantenimiento del código CSS.
- **Animista**: [Documentación Oficial](https://Animista.net/)
    Animista proporciona una colección de animaciones CSS prediseñadas que se han implementado en el proyecto para efectos interactivos y visuales atractivos.