# MODU — Cyber Edition

### Diseño y desarrollo de una landing page responsive para una campaña de retail ficticia.

MODU es una marca ficticia de muebles y objetos contemporáneos que busca transformar los espacios cotidianos en lugares donde suceden historias.

**Cyber Edition** es una campaña gráfica y digital que combina fotografía editorial, intervenciones ilustradas y mensajes conceptuales para comunicar descuentos sin perder la identidad estética de la marca.

El proyecto contempla el desarrollo de una identidad visual de campaña y su aplicación en distintos formatos digitales, incluyendo una landing page responsive.

---

## 01. Concepto creativo

### No es solo una silla.

La campaña parte de la idea de que los muebles no son únicamente objetos funcionales, sino que forman parte de nuestras experiencias, conversaciones y momentos cotidianos.

A través de mensajes cercanos y fotografías de interiores, MODU propone una comunicación comercial que conecta emocionalmente con el usuario.

**Mensajes de campaña:**

- No es solo una silla.
- Hay conversaciones que merecen otra taza.
- Hay lugares de los que cuesta levantarse.
- Las mejores ideas no siempre llegan de pie.
- El mejor plan también es quedarse.

La campaña utiliza intervenciones gráficas dibujadas a mano para destacar detalles de los productos y reforzar su narrativa.

---

## 02. Objetivos del proyecto

### Objetivo principal

Diseñar y desarrollar una landing page responsive para promocionar la campaña Cyber Edition, facilitando el descubrimiento de productos y el acceso a las ofertas.

### Objetivos específicos

- Traducir una identidad gráfica a una experiencia web.
- Crear una interfaz visualmente coherente con la campaña.
- Aplicar principios de diseño UX/UI.
- Establecer una jerarquía clara de información.
- Implementar una estructura HTML semántica.
- Desarrollar una interfaz adaptable a mobile, tablet y desktop.
- Considerar buenas prácticas de accesibilidad y SEO.

### Objetivo de conversión

**Conversión principal:** dirigir al usuario hacia los productos y ofertas de Cyber Edition.

**Conversión secundaria:** incentivar la suscripción al newsletter de MODU.

---

## 03. Sistema de diseño

El sistema visual combina una estética editorial y minimalista con recursos gráficos expresivos.

### Paleta de colores

| Color       | HEX       | Aplicación               |
| ----------- | --------- | ------------------------ |
| Carbón      | `#25231F` | Textos, botones y fondos |
| Marfil      | `#EAE5DD` | Fondos y secciones       |
| Terracota   | `#B84430` | Acentos y destacados     |
| Blanco      | `#FFFFFF` | Fondos y textos          |
| Gris cálido | `#625B53` | Textos secundarios       |

### Tipografía

**Cormorant Garamond**

Utilizada en titulares editoriales y mensajes conceptuales de campaña.

**Montserrat**

Utilizada en navegación, botones, textos informativos y elementos de interfaz.

### Recursos gráficos

- Ilustraciones lineales de trazo blanco.
- Flechas y anotaciones manuscritas.
- Contornos que destacan elementos de las fotografías.
- Composiciones fotográficas editoriales.
- Contrastes entre tipografía serif y sans serif.

Los recursos gráficos complementan las fotografías sin interferir con la legibilidad del contenido.

---

## 04. Estructura de la landing page

La página está organizada para facilitar la exploración de la campaña y orientar al usuario hacia las ofertas.

### Header

Identidad MODU y navegación principal.

### Hero

Presentación de Cyber Edition con el mensaje principal, información promocional y CTA «Descubrir ofertas».

### Beneficios

Franja informativa con el mensaje «Compra hoy. Recibe hoy».

### Descubre la colección

Acceso visual a las categorías Sillas, Sofás y Lámparas.

### Colección destacada

Presentación editorial de una colección mediante fotografía, storytelling y CTA.

### Favoritos Cyber

Selección de productos destacados con enlaces para conocer cada pieza.

### Newsletter

Formulario de suscripción para recibir inspiración y novedades de MODU.

### Footer

Identidad de marca y navegación complementaria.

---

## 05. Diseño responsive

La landing está desarrollada bajo el enfoque **Mobile First**, comenzando por la experiencia en pantallas pequeñas.

### Breakpoints

| Dispositivo | Ancho                                  | Layout        |
| ----------- | -------------------------------------- | ------------- |
| Mobile      | Desde 375 px como referencia de diseño | Una columna   |
| Tablet      | Desde 768 px                           | Dos columnas  |
| Desktop     | Desde 1024 px                          | Tres columnas |

### Técnicas utilizadas

- CSS Flexbox para navegación y distribución de elementos.
- CSS Grid para categorías, productos y secciones.
- Media queries para adaptar el layout.
- Imágenes fluidas y ajustes de encuadre.
- Variables CSS para mantener la consistencia visual.

---

## 06. Accesibilidad

El proyecto incorpora buenas prácticas de accesibilidad web desde la estructura y el diseño de la interfaz.

### Consideraciones

- Uso de etiquetas HTML5 semánticas.
- Un único encabezado H1.
- Jerarquía de encabezados H2 y H3.
- Textos alternativos descriptivos en imágenes.
- Etiquetas asociadas a campos de formulario.
- Estados `hover` y `focus-visible`.
- Enlace para saltar directamente al contenido principal.
- Botones y enlaces identificables.
- Adaptación a distintos tamaños de pantalla.
- Respeto por la preferencia de movimiento reducido.

Estas decisiones constituyen una base de accesibilidad. La conformidad con WCAG requiere pruebas y validaciones adicionales.

---

## 07. SEO

La estructura HTML incorpora elementos básicos de optimización para motores de búsqueda y plataformas digitales.

- Meta title.
- Meta description.
- Etiquetas Open Graph.
- HTML semántico.
- Jerarquía de encabezados.
- Textos alternativos en imágenes.

---

## 08. Tecnologías y herramientas

### Diseño

- Figma — Wireframes, UI y diseño responsive.
- Adobe Illustrator — Identidad visual y recursos gráficos.
- Adobe Photoshop — Tratamiento e intervención de fotografías.

### Desarrollo

- HTML5 — Estructura semántica.
- CSS3 — Estilos, Flexbox, Grid y responsive.
- Visual Studio Code — Editor de código.
- Live Server — Visualización local.
- Git — Control de versiones.
- GitHub — Repositorio del proyecto.

---

## 09. Estructura del proyecto

```text
modu/
├── index.html
├── README.md
├── css/
│   └── styles.css
└── img/
    ├── hero-silla.jpg
    ├── sillas.jpg
    ├── sofas.jpg
    ├── escritorio.jpg
    └── coleccion-cafe.jpg
```

---

## 10. Instalación y visualización

### Clonar el repositorio

```bash
git clone https://github.com/TU-USUARIO/TU-REPOSITORIO.git
```

### Abrir el proyecto

1. Abrir la carpeta del proyecto en Visual Studio Code.
2. Instalar la extensión Live Server si aún no está instalada.
3. Abrir `index.html`.
4. Seleccionar **Open with Live Server**.
5. Visualizar la landing en el navegador.

El proyecto utiliza HTML y CSS, por lo que no requiere instalar dependencias.

---

## 11. Estado del proyecto

Proyecto de diseño y desarrollo frontend con fines educativos y de portafolio.

**Funcionalidades pendientes de integración:**

- Páginas individuales de productos.
- Carrito de compras.
- Conexión del formulario de newsletter.
- Integración con una plataforma de e-commerce.
- Validación completa de accesibilidad.

---

## 12. Créditos

**Concepto, identidad visual, diseño UI y desarrollo frontend:** proyecto personal de portafolio.

**Fotografías:** Unsplash.

Las fotografías fueron utilizadas como base visual e intervenidas mediante ilustraciones y recursos gráficos desarrollados para la campaña.

MODU es una marca ficticia creada con fines de práctica y presentación profesional.

Los productos, descuentos y mensajes comerciales son ilustrativos y no corresponden a una tienda real.
