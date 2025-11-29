# 📄 Ver JSON – Visor Universal Mejorado

Un visor avanzado de archivos **JSON de proyectos** diseñado especialmente para uso **móvil**, con una interfaz moderna, animaciones, detección de errores y sistema de previsualización integrado.  
Permite abrir cualquier archivo JSON, validar su contenido y mostrar proyectos con descripción, etiquetas, vista previa y apertura en ventana externa.

---

## 🚀 Características principales

- 📱 **Optimizado para dispositivos móviles**  
  Detecta si estás en PC y muestra un mensaje indicando que la herramienta solo funciona en móvil.

- 📁 **Selecciona cualquier archivo JSON**  
  Compatible con JSONs de cualquier nombre.

- 🔍 **Validación automática**  
  - Si el archivo no es un JSON válido → ❌ “Este no es un JSON”.  
  - Si la estructura es incorrecta → mensaje de error claro.

- 🗂️ **Vista de proyectos con tarjetas (cards)**  
  Cada proyecto muestra:
  - Título  
  - Descripción  
  - Etiquetas  
  - Botón **Abrir**  
  - Botón **Previsualizar**

- 🧩 **Compatibilidad con:**
  - Proyectos locales  
  - HTML incrustado (`inline`)  
  - Rutas externas (`path`)

- 🖼️ **Logo animado tipo "mascota"**  
  - Forma redonda  
  - Salta continuamente  
  - Efecto de partículas negras al caer  
  - 100% CSS + JS (sin librerías)

- 🖥️ **Previsualizador integrado (iframe)**

---

## 📦 Estructura de un JSON compatible

```json
{
  "projects": [
    {
      "title": "Mi Proyecto",
      "description": "Descripción del proyecto",
      "tags": ["html", "json", "viewer"],
      "entryType": "inline",
      "html": "<h1>Hola</h1>"
    }
  ]
}
