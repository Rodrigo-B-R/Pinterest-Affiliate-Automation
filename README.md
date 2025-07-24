# Pinterest Affiliate Automation Tool

Este proyecto tiene como objetivo automatizar la publicación de pines de productos en Pinterest utilizando descripciones generadas con inteligencia artificial y enlaces de afiliado de Amazon. Está pensado para creadores de contenido, bloggers y marketers que desean compartir ofertas de productos con sus audiencias de manera eficiente.

## ✨ Propósito de la aplicación

- Automatizar la creación de pines a partir de información de productos obtenida de fuentes como la API de Keepa (Amazon).
- Utilizar inteligencia artificial para generar descripciones relevantes, útiles y únicas para cada pin.
- Promover productos de forma honesta, con transparencia mediante el uso de etiquetas como `#ad`.
- Dirigir a los usuarios a enlaces de afiliado personalizados, respetando las políticas de cada plataforma.

## 🧠 ¿Cómo funciona?

1. Cada día, el sistema selecciona productos con descuentos significativos.
2. Genera descripciones atractivas y hashtags optimizados con IA (GPT).
3. Publica automáticamente un pin en Pinterest usando la API oficial.
4. Cada publicación incluye:
   - Imagen del producto.
   - Descripción generada con AI.
   - Hashtags relevantes.
   - Etiqueta obligatoria `#ad` para indicar contenido patrocinado.
   - Un enlace de afiliado correctamente etiquetado.

## ✅ Cumplimiento con las políticas de Pinterest

Esta aplicación ha sido diseñada cuidadosamente para cumplir con las políticas de la plataforma, incluyendo:

- **Publicidad Transparente**: Cada publicación incluye la etiqueta `#ad` o `#affiliate`, según lo requerido por Pinterest y la ley.
- **Contenido original y de calidad**: Las descripciones son generadas dinámicamente por IA para evitar spam y duplicación.
- **Enlaces de afiliado permitidos**: Solo se usan programas de afiliados aprobados por Pinterest (como Amazon Associates).
- **No se realiza scraping ni automatizaciones prohibidas**: Toda interacción con Pinterest se realiza a través de su API oficial, con una cuenta de empresa verificada.

## 🚧 Estado actual

Actualmente, el sistema funciona localmente con `n8n` en Docker. Se está evaluando la API de Keepa para extracción de datos de productos.

## 📌 Importante

Este proyecto no está afiliado oficialmente con Pinterest ni Amazon. El uso de esta herramienta debe seguir las políticas de ambas plataformas.

## 👨‍💻 Desarrollado por

Rodrigo Betancourt – [GitHub](https://github.com/rodrigobetancourt)

