# Repaso MIA

Simulador estático con un banco de 60 preguntas sobre los tres PDF del temario.

## Uso local

Abre `index.html` directamente o ejecuta un servidor local:

```bash
python -m http.server 8000
```

## Despliegue en Render

1. Sube esta carpeta a un repositorio de GitHub.
2. En Render, crea un **Static Site** conectado al repositorio.
3. Deja vacío **Build Command**.
4. Usa `.` como **Publish Directory**.

El archivo `render.yaml` también permite crear el servicio como Blueprint.
