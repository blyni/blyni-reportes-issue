<p align="center">
  <img src="https://raw.githubusercontent.com/blyni/.github/main/profile/marca/blyni-logotipo-horizontal-d-sticker-transparente.svg" alt="Blyni" width="320">
</p>

# Reportes de Blyni

Aquí se reportan los errores de [Blyni](https://github.com/blyni). Un reporte bien escrito nos ahorra días de trabajo: con él podemos ver lo mismo que tú viste y arreglarlo.

<p align="center">
  <a href="https://github.com/blyni/blyni-reportes-issue/issues/new/choose"><strong>Abrir un reporte nuevo</strong></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/blyni/blyni-reportes-issue/issues?q=is%3Aissue">Ver los reportes que ya hay</a>
</p>

> Blyni está en desarrollo y todavía no tiene versiones públicas para descargar: este espacio es para quienes prueban las versiones de prueba.

## Qué tipo de reporte elegir

Al hacer clic en **Abrir un reporte nuevo** eliges el tipo, y el formulario ya trae los campos y un texto de ejemplo para rellenar:

| Tipo | Cuándo |
|---|---|
| **Reporte de error** | Algo de Blyni no funciona como debería. |
| **Sugerencia** | Una idea para mejorar Blyni. |
| **Problema de accesibilidad** | No lo puedes usar con tu teclado, lector de pantalla u otra ayuda. |
| **Pregunta** | Una duda sobre cómo usar Blyni o sobre un reporte. |

## Antes de reportar

1. **Busca si ya está reportado.** Entra a [los reportes](https://github.com/blyni/blyni-reportes-issue/issues?q=is%3Aissue) (abiertos y cerrados) y busca con dos o tres palabras de lo que viste. Si ya existe, reacciona con un pulgar arriba y agrega lo que sepas en un comentario, en vez de abrir otro.
2. **Un problema, un reporte.** Si encontraste dos errores, abre dos reportes: se pueden arreglar y probar por separado.
3. **Todo lo que escribes aquí es público.** Lo puede leer cualquiera. No pongas contraseñas, claves, tokens ni datos personales tuyos o de otras personas. Más abajo está cómo tapar lo que no debe verse en una captura.
4. **Si es un problema de seguridad, no lo publiques.** Abre un reporte que diga solo «Quiero reportar un problema de seguridad», **sin detalles**, y te diremos cómo mandarlo en privado.

## Cómo es un buen reporte

Un buen reporte lleva estas partes, en este orden:

| Parte | Qué poner | Para qué sirve |
|---|---|---|
| **Título** | `[Plataforma] Qué pasa, al hacer qué`. Por ejemplo: `[Windows] La barra de pestañas deja de responder al arrastrar una pestaña`. | Se ve en la lista y se encuentra al buscar duplicados. |
| **Qué pasó** | Una o dos frases, con lo que **viste**, no con lo que crees que lo causa. | Que entendamos el problema sin adivinar. |
| **Pasos para reproducirlo** | Una lista numerada, desde que abres Blyni. Un paso por línea. | Es lo más valioso: si podemos repetirlo, lo podemos arreglar. |
| **Qué esperabas** | Lo que debería haber pasado. | Para saber dónde está la diferencia. |
| **Con qué frecuencia** | Siempre, a veces (¿cuándo?) o solo una vez. | Un error que siempre pasa y uno que pasa a veces se buscan distinto. |
| **Tu equipo** | Sistema, versión del sistema y versión de Blyni (ver [Tu equipo](#tu-equipo)). | Algunos errores solo pasan en una versión. |
| **Captura o video** | Lo que se veía en pantalla (ver [Capturas y videos](#capturas-y-videos)). | Una imagen evita párrafos de explicación. |

### Plantilla para copiar

Los formularios ya traen estos campos. Esta plantilla es por si lo escribes a mano: cópiala en el reporte y rellénala. Lo que no sepas, déjalo escrito como «no sé»: es mejor que borrarlo.

````markdown
**Plataforma:** macOS / Windows / iPhone / iPad / Android / TV

**Qué pasó**
(Lo que viste, en una o dos frases.)

**Pasos para reproducirlo**
1. Abro Blyni.
2. …
3. …

**Qué esperaba**
(Lo que debería haber pasado.)

**Con qué frecuencia**
(Siempre / a veces / una sola vez.)

**Tu equipo**
- Sistema y versión:
- Versión de Blyni:
- Modelo del equipo (si es un teléfono, una tableta o una tele):

**Captura o video**
(Arrastra aquí la imagen o el video.)

**Algo más**
(Qué pestañas tenías abiertas, si lo acabas de instalar, si antes funcionaba…)
````

## Capturas y videos

Una captura casi siempre vale más que un párrafo. Un video corto es lo mejor cuando el problema es algo que **se mueve**: un parpadeo, una animación, un salto de la barra o una pestaña que no responde.

### Cómo tomarlas

| Sistema | Captura | Video |
|---|---|---|
| **macOS** | `⌘ ⇧ 4` (un recuadro) o `⌘ ⇧ 3` (toda la pantalla) | `⌘ ⇧ 5` y «Grabar pantalla» |
| **Windows** | `Win ⇧ S` (recorte) | La app **Recortes**, o `Win Alt R` |
| **iPhone y iPad** | Botón lateral + subir volumen (en los que no tienen botón de inicio) | Centro de control › Grabación de pantalla |
| **Android** | Encendido + bajar volumen (cambia según la marca) | Ajustes rápidos › Grabar pantalla |
| **TV** | Una foto con el teléfono, de frente y sin reflejos | Un video corto con el teléfono |

### Cómo adjuntarlas

Arrastra el archivo al cuadro de texto del reporte, o pégalo con `⌘ V` / `Ctrl V`. GitHub lo sube y pone el enlace solo. También sirve el clip de la barra del cuadro de texto. GitHub limita el tamaño de lo que se adjunta (para imágenes y videos, del orden de 10 MB): si tu video no cabe, grábalo más corto o más pequeño.

### Qué mostrar

- **La ventana completa de Blyni**, no solo un pedazo: la barra, las pestañas y el indicador de memoria y bloqueos también cuentan.
- **Lo que pasó y, si ayuda, cómo estaba antes** (dos capturas, antes y después).
- **Una flecha o un recuadro** sobre lo que falla. Los editores de capturas de tu sistema lo hacen en dos clics.
- **Videos de menos de 30 segundos**, que empiecen un momento antes del problema.

### Qué tapar

Antes de subirla, mira la imagen entera y **tapa con un recuadro opaco** (no con desenfoque, que a veces se puede deshacer):

- correos, nombres, teléfonos y direcciones;
- el contenido de otras pestañas, y las direcciones (URL) con nombres de usuario, números de cuenta o códigos en ellas;
- cualquier contraseña, clave o código que se vea.

Si no puedes tapar algo y es necesario para entender el problema, dilo en el reporte y lo vemos sin publicarlo.

## Tu equipo

Anota dónde estás corriendo Blyni. Estos son los caminos más cortos para encontrar los datos:

| Sistema | Dónde ver la versión |
|---|---|
| **macOS** | Menú Apple › Acerca de este Mac |
| **Windows** | `Win R`, escribe `winver` y Enter |
| **iPhone y iPad** | Ajustes › General › Información |
| **Android** | Ajustes › Acerca del teléfono |
| **TV** | Ajustes › Acerca de (marca y modelo de la tele) |

Para la **versión de Blyni**, pon la que te hayan dado al entregarte la versión de prueba. Si no sabes dónde verla, escribe «no sé» y te ayudamos.

## Un ejemplo

> Es un ejemplo inventado, solo para mostrar el formato.

**Título:** `[Windows] La barra de pestañas deja de responder al arrastrar una pestaña`

**Qué pasó**
Al arrastrar una pestaña hacia la derecha, la barra se queda congelada unos segundos y después la pestaña vuelve a su lugar.

**Pasos para reproducirlo**
1. Abro Blyni con cuatro pestañas.
2. Presiono la segunda pestaña y la arrastro hacia la derecha.
3. Suelto antes de llegar a la última.

**Qué esperaba**
Que la pestaña se quedara donde la solté.

**Con qué frecuencia**
Siempre, con más de tres pestañas.

**Tu equipo**
- Sistema y versión: Windows 11, 23H2
- Versión de Blyni: la de prueba que me dieron el lunes

**Captura o video**
Un video de 10 segundos, con la barra completa a la vista (adjunto).

## Qué pasa después

- Revisamos el reporte y le ponemos una etiqueta (por ejemplo `bug`, `enhancement`, `question` o `accessibility`).
- Si nos falta algo, te lo pedimos **en el mismo reporte**: respóndenos ahí.
- Los reportes repetidos se marcan como duplicados y se enlazan al original.
- Enviar un reporte no obliga a responderlo ni a corregirlo en un plazo.

## Licencia

Lo que envías aquí (el texto, las capturas y los videos) es **público**, y le das a Blyni permiso para usarlo con el fin de diagnosticar, corregir y documentar problemas, como dice el artículo 8 de la [Licencia Blyni](LICENSE-BLYNI.md). Sigue siendo tuyo. Si no puedes publicar algo, no lo adjuntes.

El texto de esta documentación y la [Licencia Blyni](LICENSE-BLYNI.md) son de Blyni.
