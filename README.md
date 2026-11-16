# FenixTerm

Terminal para trabajar con agentes de IA (Claude Code, opencode, Hermes) en varios proyectos a la vez: pestañas y split por proyecto, aviso cuando un agente te necesita, uso de tus planes, panel Git, editor y navegador integrados.

Este repositorio solo contiene los **instaladores**. Descarga la última versión en **[Releases → Latest](../../releases/latest)**.

## Instalar

### Linux (Ubuntu 22.04+, Debian 12+)
- **.deb** (recomendado):
  ```bash
  sudo apt install ./FenixTerm_*_amd64.deb
  ```
- **AppImage** (sin instalar):
  ```bash
  chmod +x FenixTerm_*.AppImage && ./FenixTerm_*.AppImage
  ```

### Windows 10/11
Ejecuta `FenixTerm_*_x64-setup.exe`. Si Windows muestra «Windows protegió su PC», pulsa **Más información → Ejecutar de todas formas** (el instalador aún no tiene firma de Microsoft).

## Primeros pasos
1. Añade la carpeta de un proyecto (**+ Añadir**).
2. Instala al menos un agente: la app trae una guía con el comando oficial de cada uno (Claude Code, opencode, Hermes). Cada agente guarda su propio login; FenixTerm no guarda claves.
3. Abre una terminal con el botón **+**.

## Actualizaciones
FenixTerm busca versiones nuevas sola y se actualiza con un clic. Cada actualización va firmada: la app rechaza cualquier archivo que no venga de aquí.

## Problemas o sugerencias
Abre un *issue* en este repositorio.
