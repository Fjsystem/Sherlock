# Jampa X64 Eyes 0.1

Primera versión Android con el icono del ojo, logotipo completo y controles compactos. Es independiente de Sherlock.

## Descargar

- [APK ARM64 — mayoría de teléfonos actuales](https://raw.githubusercontent.com/Fjsystem/Sherlock/main/Eyes/JampaX64_Eyes-0.1-arm64-v8a.apk)
- [APK ARM de 32 bits — modelos antiguos](https://raw.githubusercontent.com/Fjsystem/Sherlock/main/Eyes/JampaX64_Eyes-0.1-armeabi-v7a.apk)

Abre en Chrome para descargar.

## Uso

1. Autoriza la cámara. Una sola etiqueta completa debe ocupar el marco blanco, con luz constante y buena nitidez.
2. Elige Textos, Dibujos y/o Color. Se pueden combinar. Textos viene activado al inicio.
3. Pulsa Capturar patrón y revisa la foto y el texto leído. Confirma Usar patrón solo si se han leído correctamente.
4. Enseña otras etiquetas completas dentro del marco. Pellizca con dos dedos para acercar la cámara si lo necesitas.
5. Verde: coincidencia confirmada dentro de las comprobaciones/tolerancias activas. Rojo: diferencias confirmadas y recuadros. Gris: esperando, borroso o no alineable; no significa que la etiqueta sea correcta.

Ver patrón muestra la referencia. Capturar patrón permite cambiarla. La referencia y los ajustes se conservan al cerrar la app.

## Modos

- Textos compara letras, números y signos de forma literal, incluidos mayúsculas, acentos y ceros iniciales. Compara códigos escritos; no decodifica barras ni QR.
- Dibujos evalúa estructura después de alinear las imágenes y excluye regiones identificadas como texto. Para logotipos con letras, activar también Textos.
- Color evalúa diferencias locales de color/luminosidad compensando variaciones moderadas de luz. No es un instrumento colorimétrico calibrado.
- Detalle visual 0–100 % ajusta la sensibilidad de las comparaciones visuales. Más alto detecta detalles menores, pero también más ruido. No hace que se ignoren dígitos o letras distintos.

Sin casillas activas no se da un verde. Una etiqueta totalmente distinta, desenfocada, curva, con reflejos o parcialmente visible puede dar gris si no se puede alinear con fiabilidad. Una comparación a resolución limitada puede omitir detalles pequeños: comprobar con tus propias etiquetas y defectos conocidos.

## Estado y privacidad

APK de prueba firmados y compilados. 22 comprobaciones automáticas de texto y estados aprobadas; OCR, alineación, cámara y color pendientes de prueba en móvil real. No validado como sistema de inspección industrial ni como garantía absoluta de igualdad.

Patrón almacenado solo dentro de la app en el móvil. Sin permisos de Internet/estado de red en el APK. Modelo OCR latino y OpenCV incluidos. Firma de depuración; todavía no es una publicación final en Google Play.
