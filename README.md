# Prompts de exhibidores

Generador de prompts para crear en ChatGPT renders de exhibidores en el local del cliente. Es una página estática: no necesita servidor, base de datos ni claves de API.

## Contenido

```
index.html            Página completa (HTML, estilos y lógica)
img/logotipo.png      Logotipo de Febeca
```

## Publicar con GitHub Pages

1. Cree un repositorio nuevo en GitHub (por ejemplo, `prompts-exhibidores`).
2. Suba los archivos de esta carpeta a la raíz del repositorio, conservando la carpeta `img`.
3. En el repositorio, vaya a **Settings → Pages**.
4. En **Build and deployment**, elija **Deploy from a branch**, rama `main` y carpeta `/ (root)`. Guarde.
5. En uno o dos minutos la página queda disponible en `https://<usuario-u-organizacion>.github.io/prompts-exhibidores/`.

Para actualizarla, reemplace `index.html` en el repositorio; GitHub Pages vuelve a publicar solo.

## Tipografía

La página usa Arial, la alternativa a Myriad Pro definida en el sistema de diseño de Febeca. No incluye archivos de fuentes con licencia.
