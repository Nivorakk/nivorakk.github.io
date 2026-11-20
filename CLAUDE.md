# Contexto del proyecto

Página de portafolio de **Nivorak** (Joan Cervera): https://nivorakk.github.io
Ofrece webs a medida para negocios locales de Alicante. El objetivo de la página es conseguir clientes.

## Cómo hablar con el usuario
- En español, paso a paso y sin tecnicismos: está aprendiendo.
- Las capturas de pantalla que envía son de GitHub, LinkedIn o Google en español.

## Estructura
- HTML y CSS sin dependencias ni build. GitHub Pages publica la rama `main` desde la raíz.
- `index.html`: portada, Proyectos, Servicios, Cómo trabajo y Contacto. Incluye datos estructurados `ProfessionalService` (schema.org), etiquetas Open Graph y el script de GoatCounter al final del `body`.
- `assets/css/estilos.css`: colores y tipografías en `:root`.
- `assets/img/`: capturas en WebP (1200 px de ancho las de ordenador, 600 px las de móvil), `favicon.svg` y `og.png` (1200 × 630, imagen para compartir).
- `sitemap.xml` y `robots.txt` en la raíz. Si se añade una página o un proyecto, hay que añadirlo también al sitemap.
- `google644f0caf98e39005.html` en la raíz: verificación de Google Search Console. No borrarlo nunca ni añadirlo al sitemap.

## Marca
- Colores: azul noche `#08101D` y cian `#22D3EE` / `#67E8F9`. Fondo claro de secciones `#F4F7FA`.
- Tipografías: Space Grotesk (títulos) e Inter (texto), desde Google Fonts.
- Mismo estilo que su banner de GitHub y su portada de LinkedIn.

## Enlaces
- Proyectos: https://nivorakk.github.io/Cafeter-a_Web/ y https://nivorakk.github.io/Drones_web/ (repositorios aparte).
- Perfiles: https://www.linkedin.com/in/nivorak, https://github.com/Nivorakk, https://www.instagram.com/nivorak.ai/
- Visitas: GoatCounter, cuenta `nivorak` (https://nivorak.goatcounter.com).

## Forma de trabajar
1. Hacer los cambios en una rama nueva, nunca directamente en `main`.
2. Probar la página en local y revisar capturas a 1366 px y 390 px de ancho: sin errores de consola ni desplazamiento horizontal.
3. Abrir un PR con el resumen en español. El usuario lo fusiona, o pide que lo fusione Claude.

## Pendiente
- Google Search Console (propiedad "Prefijo de la URL" `https://nivorakk.github.io/`, método "Archivo HTML"): el archivo de verificación ya está en la web. Falta que el usuario pulse "Verificar" y enviar `sitemap.xml` en Search Console.
- Preparar paquetes con precio y un mensaje para contactar con negocios locales.
