# Práctica MCP: Filesystem y Playwright en Google Antigravity

Repositorio con la configuración, salidas generadas y evidencias visuales de la práctica de servidores **Model Context Protocol (MCP)** ejecutada en **Google Antigravity** sobre **CachyOS**.

## Servidores MCP Configurados

- **`filesystem` (`@modelcontextprotocol/server-filesystem`)**: Acceso controlado al directorio del proyecto (`~/Documentos/ITCM/MCP`) para lectura y escritura de archivos.
- **`playwright` (`@playwright/mcp@latest`)**: Automatización de navegador web usando Chromium (`/usr/bin/chromium`) para navegación y extracción de contenido DOM.

## Actividades Realizadas

1. **Actividad A (`filesystem`)**: Lectura de `datos/calificaciones.csv`, cálculo de promedios individuales y grupales, determinación de estado (`Aprobado` / `Reprobado`) y generación de `salida/reporte.md`.
2. **Actividad B (`playwright`)**: Navegación automatizada hacia `https://example.com`, extracción del título, encabezado principal y enlaces visibles, guardando el resultado en `salida/web_info.md`.

## Estructura del Repositorio

```
MCP/
├── .agents/mcp_config.json
├── datos/
│   └── calificaciones.csv
├── evidencias/
│   ├── 01_servidores_mcp_activos.png
│   ├── 02_actividad_a_reporte.png
│   └── 03_actividad_b_playwright.png
├── salida/
│   ├── reporte.md
│   └── web_info.md
└── README.md
```
