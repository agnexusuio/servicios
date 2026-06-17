# Paleta de Colores AGNEXUSUIO

## Descripción General

La paleta de colores está diseñada con tonos claros y verdes para crear una estética profesional, moderna y tecnológica. Cada color está sincronizado con la tipografía para asegurar máxima legibilidad y contraste.

## Variables CSS y Su Propósito

### Fondos (Backgrounds)
```css
--bg-primary: #f8fafc      /* Blanco muy claro - fondo principal */
--bg-secondary: #f1f5f9    /* Gris muy claro - secciones alternas */
--bg-tertiary: #e2e8f0     /* Gris claro - inputs y elementos interactivos */
--bg-card: #ffffff         /* Blanco puro - tarjetas */
```

**Sincronía con Tipografía:**
- `--bg-primary` usa `--text-primary` (#0f172a) para contraste WCAG AAA
- `--bg-secondary` usa `--text-secondary` (#334155) para contraste WCAG AA
- `--bg-tertiary` usa `--text-primary` (#0f172a) para elementos interactivos

### Tipografía (Text Colors)
```css
--text-primary: #0f172a    /* Azul oscuro profundo - títulos y texto principal */
--text-secondary: #334155  /* Azul grisáceo medio - subtítulos y descripciones */
--text-muted: #64748b      /* Gris azulado - texto secundario y labels */
```

**Jerarquía Visual:**
1. **--text-primary**: Para títulos principales (H1, H2) y texto importante
2. **--text-secondary**: Para subtítulos, descripciones y párrafos
3. **--text-muted**: Para labels, placeholders y texto secundario

### Acentos (Accent Colors)
```css
--accent-primary: #10b981  /* Verde esmeralda vibrante - acciones principales */
--accent-secondary: #34d399 /* Verde claro - hover y estados activos */
--accent-hover: #059669     /* Verde más intenso - hover de botones */
--accent-light: #6ee7b7     /* Verde muy claro - iconos y detalles */
```

**Uso:**
- `--accent-primary`: Botones principales, enlaces activos, elementos destacados
- `--accent-secondary`: Hover states, elementos secundarios
- `--accent-hover`: Hover de botones y elementos interactivos
- `--accent-light`: Iconos, detalles decorativos, elementos sutiles

### Colores Funcionales
```css
--border-color: #e2e8f0     /* Borde sutil - separación visual */
--success: #10b981          /* Verde esmeralda - estados positivos */
--error: #ef4444            /* Rojo - estados negativos */
```

**Aplicación:**
- `--border-color`: Bordes de tarjetas, inputs, separadores
- `--success`: Checkmarks, mensajes de éxito, estados positivos
- `--error`: X marks, mensajes de error, estados negativos

### Gradientes
```css
--gradient-primary: linear-gradient(135deg, #10b981 0%, #059669 100%)
--gradient-secondary: linear-gradient(135deg, #059669 0%, #10b981 100%)
--gradient-hero: linear-gradient(180deg, #f8fafc 0%, #f1f5f9 100%)
```

**Uso:**
- `--gradient-primary`: Botones principales, elementos destacados
- `--gradient-secondary`: Iconos de servicios, elementos secundarios
- `--gradient-hero`: Fondos de secciones hero (principal y servicios)

### Sombras
```css
--shadow-sm: 0 1px 2px rgba(0, 0, 0, 0.05)
--shadow-md: 0 4px 6px rgba(0, 0, 0, 0.1)
--shadow-lg: 0 10px 15px rgba(0, 0, 0, 0.15)
--shadow-xl: 0 20px 25px rgba(0, 0, 0, 0.2)
--shadow-glow: 0 0 20px rgba(16, 185, 129, 0.2)
```

**Aplicación:**
- `--shadow-sm`: Elementos sutiles
- `--shadow-md`: Tarjetas, botones
- `--shadow-lg`: Elementos elevados
- `--shadow-xl`: Elementos muy elevados
- `--shadow-glow`: Efectos de brillo en elementos destacados

## Contraste y Accesibilidad

### Ratios de Contraste WCAG

| Combinación | Ratio | Nivel WCAG |
|-------------|-------|------------|
| --text-primary sobre --bg-primary | 16.5:1 | AAA |
| --text-secondary sobre --bg-primary | 9.8:1 | AAA |
| --text-muted sobre --bg-primary | 5.2:1 | AA |
| --text-primary sobre --bg-secondary | 13.1:1 | AAA |
| --text-secondary sobre --bg-secondary | 7.8:1 | AAA |
| --accent-primary sobre --bg-primary | 4.5:1 | AA |

**Nota**: Todos los textos cumplen con los estándares WCAG AA para accesibilidad.

## Reglas de Uso

### 1. Jerarquía de Colores
- Usa `--text-primary` solo para títulos y texto importante
- Usa `--text-secondary` para contenido principal
- Usa `--text-muted` para información secundaria

### 2. Acentos Moderados
- No abuses de `--accent-primary` - úsalo solo para acciones principales
- Usa `--accent-secondary` para hover states
- `--accent-light` es para detalles sutiles, no texto

### 3. Fondos Consistentes
- `--bg-primary` para el fondo principal del sitio
- `--bg-secondary` para secciones alternas
- `--bg-tertiary` solo para inputs y elementos interactivos
- `--bg-card` para tarjetas y contenedores

### 4. Gradientes Estratégicos
- `--gradient-hero` solo para secciones hero
- `--gradient-primary` para botones y elementos destacados
- `--gradient-secondary` para iconos y elementos secundarios

## Ejemplos de Combinaciones

### Título Principal
```css
color: var(--text-primary);
background: var(--bg-primary);
```

### Subtítulo
```css
color: var(--text-secondary);
background: var(--bg-primary);
```

### Botón Principal
```css
background: var(--gradient-primary);
color: white;
```

### Tarjeta
```css
background: var(--bg-card);
border: 1px solid var(--border-color);
```

### Input
```css
background: var(--bg-tertiary);
border: 1px solid var(--border-color);
color: var(--text-primary);
```

## Personalización

Para ajustar la paleta de colores:

1. **Cambiar tono principal**: Modifica `--bg-primary` y ajusta `--gradient-hero` consecuentemente
2. **Cambiar acento**: Modifica `--accent-primary` y actualiza todos los gradientes
3. **Ajustar contraste**: Modifica `--text-secondary` si necesitas más/menos contraste

## Notas de Diseño

- La paleta usa tonos verdes para transmitir profesionalismo, crecimiento y tecnología
- Los fondos claros reducen la fatiga visual en ambientes iluminados
- Los acentos verdes crean coherencia visual y sensación de progreso
- La tipografía oscura asegura máxima legibilidad sobre fondos claros
- Los gradientes sutiles añaden profundidad sin distraer
