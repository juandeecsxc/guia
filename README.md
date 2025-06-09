# guia
guia para tomar notas 
graph TD
  A[portfolio-site/] --> B[index.html]
  A --> C(css/)
  A --> D(images/)
  A --> E(pages/)
  A --> F(fonts/)

  C --> C1[styles.css]
  
  D --> D1[perfil.jpg]
  D --> D2[proyecto1.jpg]
  D --> D3[proyecto2.jpg]
  D --> D4[proyecto3.jpg]

  E --> E1[about.html]
  E --> E2[portfolio.html]
  E --> E3[contact.html]

  F --> F1[Google Fonts (import en CSS)]
//////////////////////////////////////////////////////////////////7
| Carpeta / Archivo       | Descripción                                                                                              |
| ----------------------- | -------------------------------------------------------------------------------------------------------- |
| `index.html`            | Página principal con sección Hero y navegación.                                                          |
| `/css/styles.css`       | Estilos globales (tipografía, grid, flexbox, media queries).                                             |
| `/images/`              | Imágenes utilizadas en el sitio: perfil personal, miniaturas de proyectos.                               |
| `/pages/about.html`     | Página independiente para "Sobre mí".                                                                    |
| `/pages/portfolio.html` | Portafolio con proyectos usando imágenes de `/images/`.                                                  |
| `/pages/contact.html`   | Formulario de contacto.                                                                                  |
| `/fonts/`               | Carpeta opcional si quieres usar fuentes locales (en este caso usamos Google Fonts importado en el CSS). |



@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap');
