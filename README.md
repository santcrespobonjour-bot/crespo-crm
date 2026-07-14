# CRM Crespo Real State

CRM de análisis de mercado inmobiliario (metodología ACM). Aplicación de un solo archivo (`index.html`), sin backend propio: los datos viven en Supabase.

## Cómo usarlo

1. Abrir la URL de GitHub Pages.
2. Ir a la pestaña **Base de datos**.
3. Pegar el **Project URL** y la **anon key** de Supabase (se piden al administrador; quedan guardadas solo en el navegador de cada uno, nunca en este repo).
4. **Conectar** → **Traer base ↓**.

A partir de ahí se ven zonas, propiedades, valorización (IV), histórico 5 años y proyección 5 años.

## Sincronización

- **Traer base ↓** (nube → local): trae el estado actual. Reemplaza la base local.
- **Subir base ↑** (local → nube): sube lo local. El último que sube pisa. Coordinar quién escribe.

## Nota

Este repositorio **no contiene datos**: la base semilla está vacía y no hay credenciales en el código.
