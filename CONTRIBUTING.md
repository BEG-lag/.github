# Cómo contribuir / Contributing

[English below](#english)

Gracias por darte el tiempo. Estos repositorios son herramientas abiertas sobre derecho mexicano, datos públicos y uso diario. Toda ayuda cuenta, sobre todo la que corrige un dato.

## Antes de abrir un issue

- **Corrección legal o de datos:** usa la plantilla "Corrección legal o de datos". Indica el artículo, la ley o el dato, qué está mal y la fuente oficial (DOF, Cámara de Diputados, SAT, INEGI, Gaceta Oficial) con su fecha. Sin fuente oficial no podemos cambiarlo.
- **Error:** usa la plantilla "Reporte de error" con los pasos para reproducirlo. Nunca pegues datos personales, RFC, facturas reales, placas ni montos de una persona real.
- **Idea:** usa la plantilla "Idea o mejora".

## Pull requests

1. Haz un fork y una rama con un nombre corto (`fix/tope-prima-antiguedad`).
2. Corre las pruebas del repo antes de enviar (`npm run check` en los de TypeScript, `uv run pytest` en los de Python). Si cambias una regla legal, agrega la prueba y cita la fuente en el código o en `docs/`.
3. Mensajes de commit en formato convencional, en inglés (`fix: ...`, `feat: ...`, `docs: ...`).
4. Algunos repos revisan en CI que no haya guion largo (U+2014); usa comas, dos puntos o paréntesis.

Nada de lo que se publica aquí constituye asesoría legal ni fiscal, y las contribuciones tampoco.

## English

Thanks for taking the time. Legal or data corrections are the most valuable contributions: use the "Corrección legal o de datos" template and always cite the official source (DOF, Cámara de Diputados, SAT, INEGI, Gaceta Oficial) with its date. For bugs, include steps to reproduce and never paste real personal data (RFCs, invoices, plates, amounts). Pull requests: fork, short branch name, run the repo's tests (`npm run check` or `uv run pytest`), add a test and a source for any rule change, and use conventional commit messages in English. Some repositories reject the em-dash character in CI. Nothing here is legal or tax advice.
