<p align="center">
  <img src="assets/wPhoto-icon.png" width="104" alt="wPhoto logo">
</p>

<h1 align="center">wPhoto</h1>

<p align="center">
  Importa originales de un iPhone a Windows sin esperar a que se cargue toda la fototeca.<br>
  Import original iPhone photos and videos to Windows without waiting for the entire library.
</p>

<p align="center">
  <a href="https://github.com/mariolada/wPhoto/releases/latest"><strong>Descargar / Download</strong></a>
  ·
  <a href="https://apps.microsoft.com/detail/9NP83LWLPZ9K">Apple Devices</a>
  ·
  <a href="https://paypal.me/mariolada">Apoyar / Support</a>
</p>

![wPhoto interface](docs/images/wphoto-overview.png)

## Español

wPhoto es una aplicación de escritorio para Windows que copia fotos y vídeos
originales desde un iPhone por USB. Empieza con un pequeño lote en cuanto encuentra
archivos disponibles, mientras continúa explorando la fototeca en segundo plano.

- Importa originales sin convertirlos ni recomprimirlos.
- Permite elegir toda la fototeca, periodos rápidos o un rango exacto de fechas.
- Trabaja en lotes de 25, 50 o 100 archivos.
- Organiza por año, mes, día y tipo.
- Verifica cada copia y evita duplicados al repetir una importación.
- Puede pausar, detener y reanudar después de cerrar la aplicación o reconectar el iPhone.
- Muestra progreso general, lote, archivo actual, velocidad y tiempo estimado.
- Identifica los originales pendientes y enseña su ruta dentro del iPhone.
- Omite archivos auxiliares `.AAE` y `.XMP`.
- Funciona en local: no usa nube, cuentas ni telemetría.
- Interfaz completa en español e inglés.

### Cómo empezar

1. Instala [Dispositivos Apple][apple-devices] desde Microsoft Store.
2. Descarga el ZIP **Portable** de la [última versión][latest-release].
3. Extrae el ZIP y abre `wPhoto.exe`.
4. Conecta el iPhone con un cable USB de datos, desbloquéalo y acepta **Confiar**.
5. Elige destino, fechas y organización; después pulsa **Importar**.

La edición Portable ya incluye .NET. La edición Lite ocupa menos, pero necesita
[.NET 10 Desktop Runtime x64][dotnet-runtime]. Windows puede mostrar SmartScreen
porque el ejecutable aún no tiene una firma comercial. Compara siempre el SHA-256
con `SHA256SUMS.txt` de la Release.

## English

wPhoto is a Windows desktop app that copies original photos and videos from an
iPhone over USB. It starts with a small batch as soon as files become available,
while discovery of the remaining library continues in the background.

- Imports originals without conversion or recompression.
- Supports the full library, quick periods and exact custom date ranges.
- Uses batches of 25, 50 or 100 files.
- Organizes files by year, month, day and media type.
- Verifies every copy and prevents duplicates on repeated imports.
- Pauses, stops and resumes after closing the app or reconnecting the iPhone.
- Shows overall, batch and per-file progress, speed and an adaptive ETA.
- Lists pending originals together with their path on the iPhone.
- Skips `.AAE` and `.XMP` sidecar files.
- Runs locally with no cloud, account or telemetry.
- Complete Spanish and English interface.

### Getting started

1. Install [Apple Devices][apple-devices] from Microsoft Store.
2. Download the **Portable** ZIP from the [latest release][latest-release].
3. Extract the ZIP and run `wPhoto.exe`.
4. Connect the iPhone with a USB data cable, unlock it and accept **Trust**.
5. Choose the destination, dates and folder layout, then select **Import**.

The Portable edition includes .NET. The smaller Lite edition requires the
[.NET 10 Desktop Runtime x64][dotnet-runtime]. Windows may display a SmartScreen
warning because the executable is not commercially code-signed yet. Always compare
the download against the SHA-256 values in the Release's `SHA256SUMS.txt`.

## Source, issues and privacy

This public repository contains the product documentation, verified downloads and
issue tracker. The development repository is private; source review can be granted
by invitation. This is not an open-source distribution and no public code
contributions are accepted.

Bug reports and feature requests are welcome in [Issues][issues]. Do not attach
personal photos, unsanitized logs, Apple IDs, device identifiers or private paths.
The app itself sends no files, filenames or diagnostics to wPhoto.

See [NOTICE.md](NOTICE.md) for the distribution notice and
[SECURITY.md](SECURITY.md) before reporting a security concern.

[apple-devices]: https://apps.microsoft.com/detail/9NP83LWLPZ9K
[dotnet-runtime]: https://dotnet.microsoft.com/download/dotnet/10.0
[latest-release]: https://github.com/mariolada/wPhoto/releases/latest
[issues]: https://github.com/mariolada/wPhoto/issues
