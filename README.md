# DS-FE-TP3
Desarrollo Software - Frontend - Trabajo Practico 3

## Ejercicio Práctico: Mi Primera Página Estilizada

### Descripción
Este proyecto es un ejercicio práctico para aprender los fundamentos de HTML y CSS, creando una página web simple con estilos externos.

### Estructura del Proyecto
```
DS-FE-TP3/
├── index.html      # Archivo HTML principal
├── styles.css      # Hoja de estilos CSS externa
└── README.md       # Documentación del proyecto
```

### Contenido HTML
El archivo `index.html` incluye:
- **Encabezado `<h1>`**: Título principal de la página
- **Tres párrafos `<p>`**: Contenido de texto con Lorem Ipsum
- **Contenedor `<div>`**: Con clase `image-container` que contiene dos imágenes
- **Imágenes**: Dos imágenes placeholder de 150x150px

### Estilos CSS Aplicados

#### 1. Estilo del Encabezado (`h1`)
- **Color del texto**: `#84482D` (marrón cálido)
- **Alineación**: Centrada (`text-align: center`)

#### 2. Estilo de los Párrafos (`p`)
- **Tamaño de fuente**: `18px`
- **Espaciado de línea**: `1.5em` (mejora la legibilidad)
- **Color del texto**: `#1C1D1F` (gris oscuro)

#### 3. Estilo del Contenedor de Imágenes (`.image-container`)
- **Display**: `flex` (permite layout flexible)
- **Justify-content**: `space-around` (distribuye el espacio uniformemente)
- **Borde**: `2px solid #BE6841` (borde sólido color terracota)
- **Padding**: `20px` (espacio interno)

#### 4. Estilo de las Imágenes (`.image-container img`)
- **Ancho**: `150px`
- **Margen**: `10px` (espacio alrededor de cada imagen)

### Conceptos Aprendidos

#### HTML
- **Estructura básica de un documento HTML5**: `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`
- **Metadatos**: `<meta charset="UTF-8">` para codificación de caracteres
- **Viewport**: `<meta name="viewport">` para diseño responsive
- **Vinculación de CSS externo**: `<link rel="stylesheet" href="styles.css">`
- **Elementos semánticos**: `<h1>`, `<p>`, `<div>`, `<img>`
- **Atributos**: `class`, `src`, `alt` para accesibilidad

#### CSS
- **Selectores**:
  - Selector de elemento: `h1`, `p`
  - Selector de clase: `.image-container`
  - Selector descendente: `.image-container img`
- **Propiedades de texto**:
  - `color`: Define el color del texto
  - `text-align`: Alineación del texto
  - `font-size`: Tamaño de la fuente
  - `line-height`: Altura de línea para mejorar legibilidad
- **Modelo de caja (Box Model)**:
  - `padding`: Espacio interno
  - `margin`: Espacio externo
  - `border`: Borde del elemento
- **Flexbox**:
  - `display: flex`: Activa el layout flexible
  - `justify-content: space-around`: Distribuye elementos horizontalmente
- **Dimensiones**:
  - `width`: Ancho de elementos

### Cómo Visualizar
1. Abre el archivo `index.html` en tu navegador web
2. Los estilos se aplicarán automáticamente desde `styles.css`

### Buenas Prácticas Aplicadas
- ✅ Separación de contenido (HTML) y presentación (CSS)
- ✅ Uso de CSS externo para reutilización y mantenimiento
- ✅ Comentarios descriptivos en CSS
- ✅ Nombres de clases semánticos (`.image-container`)
- ✅ Atributos `alt` en imágenes para accesibilidad
- ✅ Estructura HTML5 válida
- ✅ Uso de unidades relativas (`em`) para mejor escalabilidad

### Tecnologías Utilizadas
- **HTML5**: Estructura y contenido
- **CSS3**: Estilos y presentación
- **Flexbox**: Sistema de layout moderno
