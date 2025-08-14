# san-jose-cuadernillos

Este proyecto permite combinar archivos `.docx` en documentos por secciones, según el grado escolar, usando una interfaz web sencilla con Streamlit.

## Requisitos
- Python 3.8 o superior
- Las dependencias listadas en `requirements.txt`

## Instalación

1. **Instala Python** si no lo tienes: [Descargar Python](https://www.python.org/downloads/)
2. Abre una terminal en la carpeta del proyecto.
3. (Opcional pero recomendado) Crea y activa un entorno virtual:
   ```pwsh
   python -m venv venv
   .\venv\Scripts\activate
   ```
4. Instala las dependencias:
   ```pwsh
   pip install -r requirements.txt
   ```

## Ejecución

1. Ejecuta la aplicación con Streamlit:
   ```pwsh
   streamlit run app.py
   ```
2. Se abrirá una interfaz web en tu navegador.

## Uso

1. Selecciona el grado escolar.
2. Sube los archivos `.docx` que deseas combinar (en el orden deseado).
3. Haz clic en **Generar documentos**.
4. Descarga el archivo ZIP con los documentos generados.

## Notas
- La plantilla base debe estar en `docs/FORMATO_COGNITIVAS.docx`.
- Si necesitas cambiar la plantilla, reemplaza ese archivo por el tuyo.
- Si tienes problemas con dependencias, revisa que `requirements.txt` esté completo y actualizado.