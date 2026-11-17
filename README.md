# CargaFuego 2.0

Calculadora de carga combustible y evaluación de resistencia al fuego basada en NCh1916, NCh1993 y artículos 4.3.3 y 4.3.4 de la OGUC de Chile.

## Publicación con GitHub Pages

1. Inicia sesión en https://github.com y crea un repositorio público llamado `cargafuego` (o el nombre que prefieras).
2. En el repositorio pulsa **Add file > Upload files**. Sube **`index.html`**, **`README.md`** y **`.nojekyll`** de esta carpeta. Deben quedar en la raíz del repositorio. Guarda con **Commit changes**.
3. Ve a **Settings > Pages**. En **Build and deployment**, selecciona **Source: Deploy from a branch**. Elige **main** y **/(root)**, luego **Save**.
4. Cuando GitHub termine la publicación, abre `https://TU-USUARIO.github.io/cargafuego/` o el enlace que aparezca en **Settings > Pages > Visit site**.

## Notas de funcionamiento

- `index.html` contiene la aplicación completa, sin dependencias externas de CSS/JS.
- Se ejecuta en el navegador y no necesita servidor propio ni base de datos.
- Los datos guardados en almacenamiento local del navegador no se sincronizan entre dispositivos ni se trasladan automáticamente desde la versión abierta como archivo local. Usa la función de exportar/importar proyectos para transferirlos.
- Los informes se pueden generar/imprimir desde la aplicación en el navegador.
- Esta herramienta es de apoyo técnico. La clasificación, datos caloríficos, exigencias y respaldos se deben verificar en estudios formales por profesionales competentes.

## Actualizaciones

Sustituye `index.html` por la nueva versión en la raíz de tu repositorio y confirma el cambio. GitHub Pages volverá a publicar automáticamente.
