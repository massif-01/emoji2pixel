# 🎨 Emoji2Pixel

Transforma emojis e imágenes en hermoso arte de píxeles con este poderoso conversor web. Crea animaciones impresionantes, personaliza cada detalle y exporta tus creaciones como imágenes o GIFs.

**Función Principal**: Vista previa profesional de animaciones y arte de píxeles para pantallas de matriz LED WS2812, con simulación realista de renderizado LED.

![Emoji2Pixel Badge](https://img.shields.io/badge/Emoji2Pixel-v1.0-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue) ![Languages](https://img.shields.io/badge/languages-8-orange)

## ✨ Características

### 🖼️ **Entrada Multi-Fuente**
- **Soporte de Emoji**: Ingresa emojis directamente o navega desde una biblioteca completa
- **Importación de Imágenes**: Sube cualquier archivo de imagen para pixelizar
- **Modo Auto-Ajuste**: Ajusta automáticamente la escala del emoji para encajar perfectamente en el lienzo
- **Búsqueda y Filtro**: Búsqueda rápida de emoji con navegación por categorías

### 🎬 **Sistema de Animación**
- **Animación por Fotogramas Clave**: Crea animaciones suaves con múltiples fotogramas clave
- **Interpolación Tween**: Generación automática de fotogramas de transición entre fotogramas clave
- **Controles de Reproducción**: Reproduce, pausa y ajusta la velocidad de animación en tiempo real
- **Exportación GIF**: Exporta animaciones como archivos GIF animados

### 🎛️ **Controles de Transformación Avanzados**
- **Escala**: Redimensiona tu obra de arte del 0% al 200%
- **Posición**: Ajusta finamente el desplazamiento X/Y para una alineación perfecta
- **Rotación**: Gira en cualquier dirección (0-360°)
- **Lienzo Interactivo**: Manipulación directa con clic y arrastre + Mantén Shift para rotar

### 🎨 **Potente Motor de Renderizado (Vista Previa Profesional Matriz LED WS2812)**
- **Dos Modos de Renderizado**:
  - **Modo Ideal**: Simula WS2812 con difusor - la luz de cada LED se difunde uniformemente para un efecto de visualización profesional
  - **Modo Bare**: Simula la apariencia WS2812 desnuda - puntos de píxeles LED directos sin difusión, mostrando el efecto LED crudo
- **Lienzo Flexible**: Tamaño de cuadrícula ajustable (8x8 a 128x128 píxeles)
- **Estilos de Píxeles**: Elige entre píxeles cuadrados, redondeados o circulares
- **Cuantización de Color**: Reduce la paleta de colores a 2-256 colores para estética retro
- **Filtros de Nitidez**: Mejora la definición de bordes con intensidad ajustable

### 🖌️ **Herramientas de Edición**
- **Eliminación de Fondo**: Eliminación inteligente de fondo con control de tolerancia
- **Herramientas de Selección**: Selección rectangular con relleno, borrado, copiar y pegar
- **Sistema de Capas**: Flujo de trabajo de edición no destructivo
- **Soporte de Deshacer**: Revierte operaciones de selección de color y eliminación de fondo

### 📏 **Opciones de Exportación Profesional**
- **Múltiples Unidades**: Trabaja en milímetros, pulgadas o unidades de cuadrícula
- **Preajustes de Tamaño**: Preajustes rápidos para tamaños de pantalla comunes
- **Formatos de Exportación**:
  - PNG (con transparencia)
  - GIF (animado o estático)
  - Datos de píxeles en bruto
- **Renderizado de Marco**: Visualiza el diseño físico de píxeles con dimensiones del mundo real

### 🌍 **Soporte Internacional**
Traducciones integradas para 8 idiomas:
- 🇨🇳 简体中文 (Chino simplificado)
- 🇺🇸 English (Inglés)
- 🇫🇷 Français (Francés)
- 🇩🇪 Deutsch (Alemán)
- 🇮🇹 Italiano
- 🇯🇵 日本語 (Japonés)
- 🇰🇷 한국어 (Coreano)
- 🇪🇸 Español

## 🚀 Inicio Rápido

### Demo en Línea
Visita la demo en vivo: [https://thomas-hiddenpeak.github.io/emoji2pixel](https://thomas-hiddenpeak.github.io/emoji2pixel)

### Desarrollo Local

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/thomas-hiddenpeak/emoji2pixel.git
   cd emoji2pixel
   ```

2. **Servir localmente**
   
   Usando Python:
   ```bash
   python -m http.server 8000
   ```
   
   O usando Node.js:
   ```bash
   npx http-server -p 8000
   ```

3. **Abrir en el navegador**
   ```
   http://localhost:8000
   ```

¡No se requiere proceso de compilación! Esta es una aplicación web estática pura.

## 📖 Guía de Uso

### Flujo de Trabajo Básico

1. **Entrada**: Ingresa un emoji o sube una imagen
2. **Transformar**: Ajusta la escala, posición y rotación a tu gusto
3. **Agregar Fotograma**: Haz clic en el botón `+` para agregar a tu animación
4. **Personalizar**: Ajusta la configuración de renderizado, estilo de píxeles y colores
5. **Exportar**: Descarga como PNG o GIF

### Atajos de Teclado

| Atajo | Acción |
|-------|--------|
| `Espacio` | Alternar reproducción de animación |
| `Enter` | Agregar vista actual como fotograma clave |
| `Supr` / `Retroceso` | Eliminar fotograma seleccionado |
| `←` / `→` | Navegar entre fotogramas |
| `Esc` | Cancelar selección/selección de color |
| `Ctrl/Cmd + C` | Copiar selección |
| `Ctrl/Cmd + V` | Pegar selección |

### Consejos Pro

- 🎯 **Mantén presionado Shift** mientras arrastras en el lienzo para rotar en lugar de mover
- 🔍 Usa **Cuantización de Color** (8-64 colores) para arte de píxeles retro auténtico
- ⚡ Activa la **Nitidez** (30-50% de intensidad) para mejorar la claridad de los bordes
- 🎬 Establece **Fotogramas Tween** en 5-10 para animaciones suaves
- 📐 Usa el **Modo de Renderizado de Marco** para visualizar diseños de matrices LED físicas

## 🛠️ Stack Tecnológico

- **Frontend Puro**: HTML5, CSS3, JavaScript Vanilla
- **Sin Dependencias**: Cero bibliotecas o frameworks externos
- **API Canvas**: Manipulación de píxeles de alto rendimiento
- **GIF.js**: Codificación GIF del lado del cliente
- **Diseño Responsivo**: Funciona en dispositivos de escritorio y tableta

## 📁 Estructura del Proyecto

```
emoji2pixel/
├── index.html          # Estructura HTML principal
├── app.js              # Lógica de aplicación principal
├── styles.css          # Estilo y diseño
├── locales/            # Internacionalización
│   ├── index.json      # Manifiesto de idiomas
│   ├── es-ES.json      # Traducciones al español
│   ├── en-US.json      # Traducciones al inglés
│   └── ...             # Otros idiomas
├── docs/               # Documentación multiidioma
│   ├── README.es.md    # Documentación en español
│   ├── README.en.md    # Documentación en inglés
│   └── ...             # Otros idiomas
└── scripts/            # Utilidades de compilación
    └── generate_locales_index.py
```

## 🌐 Agregar Nuevos Idiomas

1. Crea un nuevo archivo de idioma en `locales/` (ej. `pt-BR.json`)
2. Copia la estructura de un archivo de idioma existente
3. Traduce todas las claves a tu idioma objetivo
4. Agrega un campo `selfName` con un emoji de bandera
5. Ejecuta el generador de índice de idiomas:
   ```bash
   python scripts/generate_locales_index.py
   ```

¡El nuevo idioma aparecerá automáticamente en el selector de idiomas!

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Así es como puedes ayudar:

- 🐛 Reportar errores y problemas
- 💡 Sugerir nuevas características
- 🌍 Agregar o mejorar traducciones
- 📝 Mejorar la documentación
- 🎨 Enviar muestras de arte de píxeles

### Directrices de Desarrollo

1. Haz un fork del repositorio
2. Crea una rama de característica (`git checkout -b feature/amazing-feature`)
3. Confirma tus cambios (`git commit -m 'Add amazing feature'`)
4. Empuja a la rama (`git push origin feature/amazing-feature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está licenciado bajo la Licencia MIT - consulta el archivo [LICENSE](../LICENSE) para más detalles.

## 🙏 Agradecimientos

- Datos de emoji procedentes de estándares Unicode
- Inspirado en herramientas de arte de píxeles clásicas y pantallas de matriz LED
- Construido con ❤️ para la comunidad de arte de píxeles

## 📮 Contacto y Soporte

- **Problemas**: [GitHub Issues](https://github.com/thomas-hiddenpeak/emoji2pixel/issues)
- **Discusiones**: [GitHub Discussions](https://github.com/thomas-hiddenpeak/emoji2pixel/discussions)

---

<div align="center">

**Hecho con 🎨 y ⌨️**

Si encuentras útil este proyecto, ¡considera darle una ⭐!

[English](README.en.md) | [简体中文](README.zh-CN.md) | [Français](README.fr.md) | [Deutsch](README.de.md) | [Italiano](README.it.md) | [日本語](README.ja.md) | [한국어](README.ko.md)

</div>
