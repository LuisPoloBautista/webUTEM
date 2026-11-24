# Portal de Métricas UTEM

Portal estático y responsivo con accesos a las métricas de Koha, DSpace y MyLOFT.

## Vista local

Puedes abrir `index.html` directamente en el navegador o servir la carpeta con cualquier servidor estático, por ejemplo:

```bash
npx serve .
```

## Publicar en GitHub

1. Crea un repositorio vacío en GitHub.
2. Desde esta carpeta, inicializa Git y vincula el repositorio.
3. Sube la rama principal:

```bash
git init
git add .
git commit -m "Crear portal de métricas UTEM"
git branch -M main
git remote add origin URL_DE_TU_REPOSITORIO
git push -u origin main
```

## Desplegar en Render

El archivo `render.yaml` ya contiene la configuración necesaria para un sitio estático.

1. En Render, selecciona **New > Blueprint**.
2. Conecta el repositorio de GitHub.
3. Selecciona el repositorio; Render detectará `render.yaml`.
4. Confirma la creación del servicio.

No se requieren variables de entorno ni un proceso de servidor.
