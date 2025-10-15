# Encuesta de Necesidades – Humic Solutions

Este proyecto permite a los usuarios identificar el mejor producto **Humic Solutions** para su tipo de cultivo, espacio y etapa de crecimiento. Utiliza un formulario interactivo en HTML y obtiene los resultados desde una hoja de cálculo de Google Sheets.

## 🧪 Funcionalidad

- Los usuarios responden **3 preguntas clave**:
  1. ¿Qué tipo de espacio tienes?
  2. ¿Qué estás cultivando?
  3. ¿En qué etapa está tu cultivo?

- Con base en estas respuestas, se consulta una hoja de cálculo pública de Google Sheets (`Planes`) y se muestra:
  - Producto recomendado
  - Imagen
  - Dosis para fertilriego, drench y dron
  - Frecuencia de uso
  - Concentración de microorganismos (UFC/mL)

## 🌿 Tecnologías usadas

- **HTML5 + CSS3** (estilo oscuro, diseño centrado)
- **JavaScript (fetch + DOM)** para procesar respuestas
- **Google Sheets** como base de datos dinámica

## 📁 Archivos importantes

- `index.html`: Contiene todo el formulario, estilos, lógica y renderizado.
- Google Sheet pública: `Planes` (https://docs.google.com/spreadsheets/d/1OMX3GpmgRDtO__q_t4HsTlnek48rLobLvsc94yiQyF4)

## 📝 Cómo funciona

1. Al seleccionar el tipo de espacio, se filtran dinámicamente las opciones de cultivo disponibles.
2. Se elige el cultivo y la etapa.
3. Al dar clic en **Consultar Plan**, se hace una consulta a la hoja de cálculo usando `fetch`.
4. Si se encuentra una coincidencia exacta, se muestra toda la información del plan.
5. Incluye botones de contacto por **WhatsApp** y **Telegram**.

## 📷 Captura de ejemplo

![Encuesta Humic](https://raw.githubusercontent.com/piztian/HumicEvaluacion/main/screenshot.png)

## 💬 Contacto

Puedes personalizar los botones de contacto en el HTML para redirigir a tus canales oficiales de soporte.

---

© Humic Solutions - Última actualización: 2025-10-15
