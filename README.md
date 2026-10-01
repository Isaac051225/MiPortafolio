# Portafolio Personal - Isaac Emmanuel Díaz Martínez

## Portada
* **Autor:** Isaac Emmanuel Díaz Martínez
* **Nombre del proyecto:** Portafolio personal
* **Materia:** Programación Web
* **Institución:** Instituto Tecnológico de Oaxaca
* **Repositorio:** https://github.com/Isaac051225/MiPortafolio
* **GitHub Pages:** https://isaac051225.github.io/MiPortafolio/

Portafolio web personal construido con HTML, CSS y JavaScript a partir de una plantilla de Bootstrap. Presenta mi perfil como estudiante de Ingeniería en Sistemas Computacionales, mis habilidades, mi formación y mis proyectos.

## Descripción del proyecto

### Framework y plantilla
* **Framework CSS:** Bootstrap 3.
* **Plantilla:** AirCV, plantilla gratuita Bootstrap HTML5 para portafolio y currículum personal, creada por KeenThemes y distribuida por ThemeWagon.
* **Descarga de la plantilla:** https://themewagon.com/themes/free-bootstrap-html5-template-personal-cv-portfolio-website/
* **Vista previa original:** https://technext.github.io/Aircv/HTML/
* **Licencia:** gratuita y de código abierto. Se conserva el crédito al autor en el footer.

### Secciones del portafolio
El menú de navegación está compuesto por cinco secciones:

* **Inicio:** portada con mi nombre, mi carrera, mi foto y los enlaces a mis redes sociales (GitHub, Facebook e Instagram).
* **Sobre mí:** descripción de quién soy, mi base técnica en el CECyTE y mi formación en el ITO, junto con barras de habilidades.
* **Perfil:** tres tarjetas con mi formación, mi experiencia y mis intereses.
* **Proyectos:** cuadrícula de cinco elementos con ventana emergente de detalle de proyectos hecho o cursos tomados.
* **Contacto:** ubicación, teléfono, correo y enlace a mi GitHub.

## Proceso de creación

1. **Elegir y descargar la plantilla.** Descargué AirCV desde ThemeWagon, descomprimí el `.zip` y renombré la carpeta como `portafolio`. Abrí `index.html` en el navegador para comprobar que funcionaba antes de modificarlo.
2. **Revisar la estructura.** Identifiqué qué hace cada parte: el `<head>` con los CSS, el menú de navegación, las secciones y los scripts al final del `<body>`.
3. **Cambiar el idioma y los metadatos.** Puse `lang="es"`, cambié el título de la pestaña y agregué la descripción y el autor.
4. **Personalizar la portada.** Reemplacé el nombre y el título de la plantilla por los míos, agregué mi foto formal como imagen de fondo y puse los enlaces de mis redes.
5. **Reescribir Sobre mí.** Redacté mi presentación incluyendo mi información. Actualicé las barras de habilidades, cuidando que el porcentaje del texto coincida con el atributo `data-width`, que es el que realmente llena la barra.
6. **Reemplazar las tarjetas de experiencia por Perfil.** Las convertí en Formación, Experiencia e Intereses y cambié sus íconos para que coincidan con cada tema.
7. **Armar la sección de Proyectos.** Sustituí los proyectos de ejemplo por mis proyectos y documentos: Fitz-Cell, app del clima, landing de cafetería, certificado de Coursera y título del CECyTE.
8. **Actualizar Contacto y footer.** Puse mis datos de contacto y dejé el crédito a KeenThemes, como pide la licencia de la plantilla.
9. **Crear mis archivos personalizados.** `css/portafolio.css` contiene mis ajustes de tamaños de letra y se carga después de `layout.min.css` para sobrescribirlo. `js/portafolio.js` coloca automáticamente el año actual en el footer.
10. **Publicar.** Subí el proyecto a GitHub con `git init`, `git add .`, `git commit` y `git push`, y activé GitHub Pages desde *Settings → Pages* con la rama `main` y la carpeta `/ (root)`.

11. ## Capturas de pantalla
### Inicio
![Inicio](img/inicio.png)

### Sobre mí
![Sobre mí](img/sobremi.png)

### Perfil
![Perfil](img/perfil2.png)

### Proyectos
![Proyectos](img/proyectos.png)

### Contacto
![Contacto](img/contacto.png)

## Créditos
Plantilla **AirCV** por [KeenThemes](http://www.keenthemes.com/), distribuida por [ThemeWagon](https://themewagon.com/).
