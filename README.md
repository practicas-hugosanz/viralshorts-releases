<p align="center">
  <img src="docs/img/logo.png" width="96" alt="Viral Shorts">
</p>

<h1 align="center">Viral Shorts</h1>

<p align="center">
  <b>De un pódcast de horas a shorts verticales con subtítulos, en unos clics.</b><br>
  Encuentra los mejores momentos, los recorta siguiendo la cara y los deja listos para TikTok, Reels y YouTube Shorts.
</p>

<p align="center">
  <a href="https://github.com/practicas-hugosanz/viralshorts-releases/releases/latest"><img src="https://img.shields.io/github/v/release/practicas-hugosanz/viralshorts-releases?label=versi%C3%B3n&color=ff7a1a" alt="Última versión"></a>
  <a href="https://github.com/practicas-hugosanz/viralshorts-releases/releases"><img src="https://img.shields.io/github/downloads/practicas-hugosanz/viralshorts-releases/total?label=descargas&color=1f6feb" alt="Descargas"></a>
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011-1f6feb" alt="Windows 10 y 11">
  <img src="https://img.shields.io/badge/se%20ejecuta-en%20tu%20ordenador-3ddc97" alt="Se ejecuta en tu ordenador">
</p>

<p align="center">
  <a href="https://github.com/practicas-hugosanz/viralshorts-releases/releases/latest"><b>⬇ Descargar la última versión para Windows</b></a>
</p>

<p align="center">
  <img src="docs/img/crear.png" alt="Pantalla Crear de Viral Shorts, con el monitor 9:16 a la derecha" width="900">
</p>

## Qué es

Viral Shorts convierte un pódcast largo en una tanda de shorts verticales. Le das el enlace del pódcast y un vídeo de fondo (un gameplay, por ejemplo) y se encarga del resto:

1. **Encuentra los momentos buenos** con lo que más rebobina la gente en YouTube, la energía del audio y la transcripción.
2. **Los monta en vertical**: recorta siguiendo la cara, quita silencios, pone un zoom lento y quema los subtítulos palabra a palabra.
3. **Te deja cada short listo**, con su título, gancho y hashtags para copiar y publicar.

Todo se hace **en tu ordenador**: no hace falta cuenta ni suscripción. Con una clave de Claude los textos de publicación salen redactados; sin ella, se extraen de lo que ya dice el invitado.

## Qué incluye

- **Elegir bien**: preselección por *most replayed* y energía del audio, para no transcribir un pódcast de 3 horas entero; arranca donde empieza el tema; modo *revisar antes de montar*.
- **Montar bien**: reencuadre que sigue la cara, recorte de silencios, subtítulos con la palabra activa resaltada y aceleración por tarjeta gráfica cuando la hay.
- **Hacerlo tuyo**: composición (dividido, solo el pódcast o en el centro), cinco estilos de subtítulos, tu logo y tu usuario, y perfiles de ajustes con nombre.
- **Antes de montar**: corrige el texto de los subtítulos, recorta cada clip y elige su estilo; añade música que baja sola cuando habla alguien y una barra de progreso.
- **Acertar más con el texto**: afina los clips elegidos con un modelo de voz mayor, con nombres difíciles y correcciones fijas.
- **Cómodo**: aplicación de escritorio con instalador, transcripción en directo, cola de trabajos, biblioteca con búsqueda y actualizaciones automáticas.

## Capturas

<table>
  <tr>
    <td width="50%"><img src="docs/img/en-curso.png" alt="Progreso por pasos con la transcripción en directo y la cola"><br><sub><b>En curso.</b> Cada paso, la transcripción en directo y la cola de trabajos.</sub></td>
    <td width="50%"><img src="docs/img/revision.png" alt="Revisión de los momentos encontrados"><br><sub><b>Revisión.</b> Marca los momentos que valen y corrige títulos y ganchos.</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="docs/img/mis-shorts.png" alt="Biblioteca de shorts con búsqueda"><br><sub><b>Mis shorts.</b> Todo lo generado, con búsqueda, título editable y texto para copiar.</sub></td>
    <td width="50%"><img src="docs/img/crear-claro.png" alt="Tema claro con composición en el centro y subtítulos neón"><br><sub><b>Tema claro u oscuro</b>, según tu Windows.</sub></td>
  </tr>
</table>

## Instalación

1. Descarga **`viralshorts-setup-<versión>.exe`** desde [la última versión](https://github.com/practicas-hugosanz/viralshorts-releases/releases/latest) y ejecútalo. Se instala para tu usuario, sin permisos de administrador.
2. Abre **Viral Shorts** desde el menú Inicio. La primera vez descarga ffmpeg, yt-dlp y whisper.cpp (unos 120 MB); las siguientes abre al momento.
3. Los modelos de voz (de 75 MB a 3 GB, según la calidad) se descargan solos, con barra de progreso, cuando hacen falta.

> Windows puede mostrar un aviso de SmartScreen porque el instalador todavía no está firmado: pulsa **Más información → Ejecutar de todos modos**.

**Requisitos:** Windows 10 o 11 de 64 bits y conexión a internet la primera vez. Necesita el *WebView2 Runtime* de Microsoft, que ya trae Windows 11 y las versiones recientes de Windows 10; si falta, se abre en el navegador.

## Tu primer short

1. En **Crear**, pega el enlace del pódcast y el del vídeo de fondo.
2. Elige cuántos shorts quieres, cuánto duran y la calidad del análisis (*Equilibrada* va bien para empezar).
3. Pulsa **Generar mis shorts** y mira cómo avanza en **En curso**. Cuando termina, están en **Mis shorts**.

## Actualizaciones

La aplicación mira sola si hay una versión nueva (al abrir y cada 3 horas) y ofrece instalarla con un clic: descarga el instalador, comprueba su huella SHA-256 y se reinicia ya actualizada. Las notas de cada versión están en [Releases](https://github.com/practicas-hugosanz/viralshorts-releases/releases).

## Desinstalar

Desde **Aplicaciones instaladas** de Windows. Al terminar pregunta si también quieres borrar las herramientas y modelos descargados (varios cientos de MB); tus shorts, en `Vídeos\viralshorts`, nunca se tocan.

## Problemas y sugerencias

Abre una [incidencia](https://github.com/practicas-hugosanz/viralshorts-releases/issues) contando qué pasó y la versión que usas (está abajo a la izquierda en la aplicación).

## Aviso legal

Montar un pódcast ajeno con gameplay ajeno y subirlo entra de lleno en Content ID y en las políticas de contenido no original de YouTube y TikTok. Con contenido propio, o con permiso, sin problema; si no, cuenta con reclamaciones y con posibles retiradas.
