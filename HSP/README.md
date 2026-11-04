# Heart Scanner Patch

Repositorio académico con los avances 1 al 11 del prototipo web, organizado por carpetas y ejecutable sin Node.js ni npm.

## Estructura

- `index.html`: menú principal del repositorio.
- `Avance_01/` a `Avance_11/`: cada avance tiene su propio `index.html`.

## Cómo probar

1. Descarga o clona este repositorio.
2. Abre `index.html` para ver el menú o entra directamente a cualquier carpeta `Avance_XX`.
3. Abre el archivo `index.html` de ese avance con Chrome, Edge o Firefox.
4. Para avances que guardan información, utiliza el mismo navegador y perfil.

No requiere Node.js, npm ni instalación de dependencias. Puede publicarse con GitHub Pages.

## Avance 11

Incluye exportación de respaldo JSON, validación de archivo e importación con dos modos: agregar registros sin duplicados exactos o reemplazar la lista actual. Usa la clave local `heartScannerPatchAvance9`, compartida con los avances 9 y 10.

## Limitaciones importantes

- Es un prototipo académico con datos de demostración; no mide signos vitales reales.
- No se conecta a sensores, ESP32, Bluetooth BLE, Firebase ni servicios clínicos.
- El almacenamiento es local al navegador y dispositivo; no es una base de datos en la nube.
- Las alertas y valores son demostrativos y no sirven para diagnosticar ni tomar decisiones médicas.
- El avance 7 incluye elementos PWA que requieren servidor/HTTPS para algunas funciones; el HTML principal se puede abrir localmente.
