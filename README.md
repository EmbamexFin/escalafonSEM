# Escalafón · Servicio Exterior Mexicano

Sistema de consulta del Escalafón de la Rama Diplomática del Servicio Exterior Mexicano.

## 🚀 GitHub Pages

Este sitio está diseñado para funcionar directamente como **GitHub Pages** — sin servidor, sin backend.

### Despliegue

1. Sube `index.html` a tu repositorio de GitHub
2. Ve a **Settings → Pages**
3. Selecciona la rama `main` y carpeta `/ (root)`
4. En unos segundos estará disponible en `https://tu-usuario.github.io/nombre-repositorio/`

## 🔍 Funcionalidades

- **Búsqueda por nombre o apellido**
- **Búsqueda por rango diplomático** (Embajador, Ministro, Consejero, etc.)
- **Búsqueda por idioma** (Inglés, Francés, Ruso, Alemán, Japonés, etc.)
- **Panel de detalle completo** al hacer clic en cada miembro:
  - Datos personales y académicos
  - Trayectoria de rangos con fechas
  - Adscripciones en el exterior
  - Adscripciones internas / SRE
  - Idiomas

## 📄 Actualización de datos (PDF)

Los datos están estructurados en el archivo `index.html` dentro del bloque `HARDCODED`.

**Para actualizar cuando haya un nuevo Escalafón:**
1. Carga el nuevo PDF usando el botón "Cargar PDF" (valida que el archivo sea correcto)
2. Actualiza el bloque `HARDCODED` en `index.html` con los nuevos registros siguiendo el mismo formato JSON
3. Sube el `index.html` actualizado a GitHub — el sitio se actualiza automáticamente

## 📋 Registros actuales (9 miembros — versión de prueba)

| # | Nombre | Rango |
|---|--------|-------|
| 1 | Font López Edmundo | Embajador |
| 2 | Piña Rojas José Ignacio | Embajador |
| 3 | Pérez Bravo Alfredo Rogerio | Embajador |
| 4 | Del Río López Francisco Eduardo | Embajador |
| 5 | Ruiz-Cabañas Izquierdo Miguel | Embajador |
| 6 | Pujalte Piñeiro Carlos | Embajador |
| 7 | Salas Lotfe Federico | Embajador |
| 8 | Gómez-Robledo Verduzco Juan Manuel | Embajador |
| 9 | Macedo Riba Pablo | Embajador |

## 🛠 Tecnología

- HTML / CSS / JavaScript puro — sin frameworks
- PDF.js (CDN) para validación de archivos PDF
- Google Fonts (Cormorant Garamond, DM Mono, Libre Baskerville)
- 100% estático — compatible con GitHub Pages
