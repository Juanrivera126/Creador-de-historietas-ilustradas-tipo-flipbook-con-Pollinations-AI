# Diseñador de Historietas tipo flipbook con Pollinations AI

Una aplicación web interactiva que utiliza inteligencia artificial para crear historietas y cuentos ilustrados personalizados con texto e imágenes generadas automáticamente.

## Características

- **Generación automática de historias**: Crea narrativas completas con personajes, trama y capítulos
- **Ilustraciones con IA**: Genera imágenes consistentes usando modelos de IA avanzados
- **Múltiples estilos artísticos**: Elige entre más de 30 estilos (Anime, Disney, Manga, Pixar, etc.)
- **Temas visuales personalizables**: 13 paletas de colores diferentes
- **Experiencia de libro interactivo**: Navegación con efecto de volteo de páginas
- **Exportación**: Descarga tu historieta en formato PDF o HTML
- **Edición de imágenes**: Regenera o elimina ilustraciones individuales
- **Multiidioma**: Soporte para español e inglés

## Tecnologías

- HTML5, CSS3, JavaScript vanilla
- API de Pollinations para generación de texto e imágenes
- Modelos de IA: Gemini, GPT, Claude, Grok, Deepseek y más
- html2canvas y jsPDF para exportación

## Uso

1. Abre `index.html` en tu navegador
2. Ingresa tu API Key de Pollinations (obtén una en [pollinations.ai](https://pollinations.ai))
3. Escribe una idea para tu historieta (ej: "Un fantasma amigable que le teme a la oscuridad")
4. Selecciona:
   - Idioma
   - Modelo de texto
   - Modelo de imagen
   - Paleta de colores
   - Estilo artístico
   - Estilo de fuente
   - Número de capítulos (3-6)
5. Haz clic en "✨ Crear Historieta"
6. Navega por tu libro usando los botones de navegación
7. Descarga tu creación en PDF o HTML

## Modelos Disponibles

### Texto
- Gemini 2.5 Flash / 3 Pro
- GPT-5 Nano
- Claude 4.5 Haiku / Sonnet
- Grok 4 Fast
- Deepseek V3.1
- Perplexity Sonar
- Kimi K2

### Imagen
- Flux
- Z Image
- Kontext
- Nano Banana / Pro
- Seedream / Pro

## Estructura del Proyecto

```
.
├── index.html              # Aplicación principal
├── cuentos.txt            # Ideas y títulos de ejemplo
├── historietas/           # Historietas generadas guardadas
│   ├── El_amanacer_podrido.html
│   ├── El_eco_de_la_luna_roja.html
│   └── ...
└── README.md
```

## Créditos

Diseñado por Juan Guillermo Rivera Berrío con tecnología Gemini 2.5 Pro y las API de Pollinations.

## Licencia

Este proyecto es de código abierto y está disponible para uso personal y educativo.
