# Frontend

Esta carpeta contiene la interfaz de usuario de la aplicación web.

## Archivos

- **`app.py`**: Aplicación web principal desarrollada con Streamlit.

## Ejecución

Para ejecutar la aplicación:

```bash
streamlit run frontend/app.py
```

Si necesitas apuntar el frontend a un backend local diferente (por defecto usa el dominio desplegado en Railway), define la variable `API_BASE_URL` antes de ejecutar:

```bash
set API_BASE_URL=http://localhost:8000   # Windows
export API_BASE_URL=http://localhost:8000  # macOS / Linux
streamlit run frontend/app.py
```

La aplicación se abrirá automáticamente en `http://localhost:8501`.

## Características

- Interfaz intuitiva con Streamlit
- Formularios interactivos para cada modelo
- Visualización de resultados en tiempo real
- Manejo de errores y validaciones

