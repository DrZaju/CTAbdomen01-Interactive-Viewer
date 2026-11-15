# CTAbdomen01 — visor anatómico 3D del tubo digestivo

**Estado:** etapa de diagnóstico; las funciones independientes de visibilidad y opacidad todavía no se habilitan hasta verificar los nombres internos del modelo.

## Modelo de Sketchfab

- Nombre: CTAbdomen01
- UID: `8c9d611b96aa409db80f74ca5ebae2c5`
- Enlace: https://sketchfab.com/3d-models/ctabdomen01-8c9d611b96aa409db80f74ca5ebae2c5

## Estructuras solicitadas

| Archivo de origen | Etiqueta | Visibilidad | Opacidad |
|---|---|---|---|
| CTesofago | Esófago | Independiente | 0–100 % |
| CTestomago | Estómago | Independiente | 0–100 % |
| CTduodeno | Duodeno | Independiente | 0–100 % |
| CTdelgado | Intestino delgado | Independiente | 0–100 % |
| CTcolon | Colon | Independiente | 0–100 % |

Se utilizarán incrementos de opacidad del 5 %, con opciones de mostrar todas y restaurar.

## Publicar el diagnóstico en GitHub Pages

1. Crear un repositorio público, por ejemplo `CTAbdomen01-Interactive-Viewer`.
2. Subir `index.html` y `README.md` a la raíz de la rama `main`.
3. En **Settings → Pages**, elegir **Deploy from a branch**, rama **main** y carpeta **/(root)**.
4. Abrir el enlace publicado.
5. En computadora, presionar `F12` y elegir **Console**.
6. Buscar `DIAGNÓSTICO SKETCHFAB`. Copiar la tabla de nodos (nombre, tipo, ID) y la tabla de materiales (nombre, ID, canal de opacidad). Compartirla para completar la configuración.

En esta versión, los controles aparecen deshabilitados por diseño: todavía no hay nombres de objetos/materiales verificados. No suponer que un nombre STL coincide con el de Sketchfab.

## Seguridad y uso

Uso para visualización anatómica. No constituye por sí mismo un dispositivo médico validado, ni garantiza precisión métrica. No publicar datos identificables de pacientes.
