# Fuente o Humo

App web didáctica lista para GitHub Pages.

## Qué hace

- Presenta 10 casos para discutir en qué saber confiar.
- Permite clasificar cada caso como **Fuente**, **Humo** o **Revisar mejor**.
- Obliga a justificar cada decisión.
- Guarda resultados por grupo en el navegador.
- Muestra un **tablero de aula** para comparar acuerdos y desacuerdos entre grupos.
- Permite **imprimir** el informe final y **descargar** un JSON con las respuestas.

## Archivos

- `index.html` → contiene toda la app (HTML + CSS + JavaScript).

## Cómo subirla a GitHub Pages

1. Creá un repositorio nuevo en GitHub.
2. Subí el archivo `index.html` al root del repositorio.
3. Si querés, subí también este `README.md`.
4. En GitHub, andá a **Settings > Pages**.
5. En **Build and deployment**, elegí:
   - **Source**: Deploy from a branch
   - **Branch**: `main` (o la rama que uses)
   - **Folder**: `/root`
6. Guardá y esperá a que GitHub publique el sitio.

## Personalizaciones rápidas

Dentro de `index.html` podés editar:

- El nombre de la app: buscá `FUENTE O HUMO`
- Los casos: buscá `const CASES = [`
- Los colores: buscá `:root {`
- Los textos de ayuda: buscá `help-list`

## Recomendación

Como la app guarda datos en el navegador, conviene usarla siempre en el mismo dispositivo si querés comparar varios grupos durante una clase.
