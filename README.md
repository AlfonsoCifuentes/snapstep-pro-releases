# SnapStep Pro — Descargas oficiales

**Capturas limpias, vídeos con zoom automático y guías paso a paso en Windows. Privacidad local total.**

🌐 Web: https://snapstep-pro.vercel.app

⬇ **[Descargar SnapStep Pro para Windows 10/11 (x64)](https://github.com/AlfonsoCifuentes/snapstep-pro-releases/releases/latest/download/SnapStepPro-Setup-x64.exe)**

- 📷 Captura con **Auto-Blur PII**: emails, tarjetas, IBAN, claves API, JWT, IPs y DNI/NIE se difuminan con OCR 100 % local.
- 🎥 Vídeo con **Auto-Zoom** cinematográfico que sigue tus clics. Exporta MP4 H.264 o GIF.
- 📋 **Guías paso a paso** automáticas en Markdown, HTML único o PDF.

Prueba gratuita de 14 días con todas las funciones, sin registro. El instalador no necesita permisos de administrador e incluye .NET 8 y FFmpeg.

## Verificar la descarga

Cada versión publica `SnapStepPro-Setup-x64.exe.sha256`. En PowerShell:

```powershell
Get-FileHash .\SnapStepPro-Setup-x64.exe -Algorithm SHA256
```

El hash debe coincidir con el del archivo `.sha256` de la misma versión.

> Durante la beta el instalador aún no está firmado con certificado de código: Windows SmartScreen puede mostrar «Windows protegió su PC». Pulsa **Más información → Ejecutar de todas formas** tras verificar el hash.

## Privacidad

SnapStep Pro no envía capturas, vídeos, texto OCR ni telemetría a ningún servidor. Solo se conecta para validar tu licencia y, si lo permites, para comprobar si hay versión nueva (lee la última release de este repositorio).

Este repositorio solo contiene los instaladores publicados; el código fuente es privado.
