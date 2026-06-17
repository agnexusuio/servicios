# AGNEXUSUIO - Sitio Web Corporativo

Sitio web de alta conversión para AGNEXUSUIO, empresa especializada en soluciones tecnológicas para PYMES en Quito, Ecuador.

## Características

- **Diseño Profesional**: Tema oscuro con tonos azules, minimalista y moderno
- **Multi-página**: Página principal + 5 páginas de servicios individuales
- **Responsive**: Adaptado para móviles, tablets y escritorio
- **CTA WhatsApp**: Botón flotante de WhatsApp en todas las páginas
- **Formulario de Leads**: Con validación y mensajes de éxito
- **FAQ**: Sección de preguntas frecuentes con acordeón interactivo
- **Diferenciadores**: Comparación clara frente a instaladores comunes
- **Copywriting Persuasivo**: Textos orientados a conversión

## Estructura del Proyecto

```
agnexus-landing/
├── index.html          # Página principal
├── redes.html          # Redes Empresariales
├── telefonia.html      # Telefonía IP / PBX
├── wifi.html           # WiFi Profesional
├── cableado.html       # Cableado Estructurado
├── iot.html            # Monitoreo IoT / LoRaWAN
├── equipos.html        # Venta de Equipos (redirección a tienda)
├── css/
│   └── styles.css      # Estilos globales
└── js/
    └── main.js         # Funcionalidad JavaScript
```

## Servicios

1. **Redes Empresariales**: Infraestructura de red robusta y segura
2. **Telefonía IP / PBX**: Sistemas de comunicación modernos
3. **WiFi Profesional**: Cobertura de alta capacidad
4. **Cableado Estructurado**: Instalación certificada
5. **Monitoreo IoT / LoRaWAN**: Control operativo inteligente
6. **Venta de Equipos**: Redirección a www.agnexusuio.store

## Información de Contacto

- **Celular/WhatsApp**: +593 99 221 7314
- **Email**: contacto@agnexusuio.com
- **Ubicación**: Quito, Ecuador

## Cómo Usar

### Opción 1: Abrir directamente
Simplemente abre `index.html` en tu navegador web.

### Opción 2: Servidor local (recomendado)
Para una mejor experiencia, usa un servidor local:

**Con Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Con Node.js (http-server):**
```bash
npx http-server -p 8000
```

Luego abre `http://localhost:8000` en tu navegador.

### Opción 3: VS Code Live Server
Si usas VS Code, instala la extensión "Live Server" y haz clic derecho en `index.html` > "Open with Live Server".

## Personalización

### Cambiar colores
Edita las variables CSS en `css/styles.css`:
```css
:root {
    --accent-primary: #3b82f6;
    --bg-primary: #0a0e17;
    /* ... otras variables */
}
```

### Modificar textos
Edita directamente los archivos HTML correspondientes.

### Configurar formulario
El formulario actualmente simula el envío. Para integrarlo con un backend:
1. Edita `js/main.js`
2. Reemplaza la simulación con una llamada real a tu API
3. Configura el endpoint de tu servidor

## Optimización para Producción

Antes de desplegar, considera:

1. **Minificar CSS y JS**: Usa herramientas como cssnano y terser
2. **Optimizar imágenes**: Comprime y usa formatos modernos (WebP)
3. **Habilitar compresión**: Configura gzip/brotli en tu servidor
4. **CDN**: Considera usar un CDN para archivos estáticos
5. **HTTPS**: Asegura tu sitio con SSL/TLS

## Despliegue

### Netlify
1. Sube los archivos a GitHub
2. Conecta tu repositorio a Netlify
3. Configura el directorio de publicación

### Vercel
1. Sube los archivos a GitHub
2. Importa el proyecto en Vercel
3. Despliega automáticamente

### Hosting tradicional
Sube todos los archivos a tu servidor FTP/SFTP.

## Soporte

Para consultas sobre el sitio web, contacta a:
- Email: contacto@agnexus.com
- WhatsApp: +593 99 221 7314

## Licencia

© 2024 AGNEXUSUIO. Todos los derechos reservados.
