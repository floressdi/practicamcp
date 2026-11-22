# Información Extraída de https://example.com

Este documento contiene la información extraída de **https://example.com** utilizando las herramientas del servidor MCP **Playwright**.

---

## 1. Título de la Página
- **Título:** `Example Domain`

---

## 2. Encabezado Principal
- **Etiquetas `<h1>` - `<h6>`:** *Ninguna presente en la versión actual del DOM.*
- **Detalle de la estructura:** En la versión actual servida por IANA (gestor oficial de `example.com`), la página ha sido modernizada y no incluye etiquetas semánticas de encabezado (`<h1>` a `<h6>`) ni elementos con atributo `role="heading"`. El mensaje principal se muestra a través de un ícono SVG y párrafos multilingües destacados. *(En la versión clásica anterior del sitio, el encabezado `<h1>` correspondía a `Example Domain`)*.
- **Párrafo principal visible (idioma detectado/español):**
  > "Este dominio está destinado al uso en ejemplos de documentación sin necesidad de permiso. Esto no es un servicio; evitar utilizarlo para realizar pruebas o monitoreos."
- **Párrafo en inglés predeterminado:**
  > "This domain is for use in documentation examples without needing permission. This is not a service; avoid relying on it for testing and monitoring purposes."

---

## 3. Enlaces Visibles
Se identificó y verificó la visibilidad del siguiente enlace en la página:

| Texto del Enlace | URL de Destino | Visibilidad en Pantalla |
| :--- | :--- | :--- |
| **Learn more** | [https://iana.org/help/example-domains](https://iana.org/help/example-domains) | `true` (Visible) |

---

## 4. Contenido Completo del Cuerpo (DOM Renderizado)
A continuación se detalla el contenido textual completo procesado por el navegador:

```text
Este dominio está destinado al uso en ejemplos de documentación sin necesidad de permiso. Esto no es un servicio; evitar utilizarlo para realizar pruebas o monitoreos.

This domain is for use in documentation examples without needing permission. This is not a service; avoid relying on it for testing and monitoring purposes.

هذا النطاق مُخصص للاستخدام في أمثلة التوثيق دون الحاجة إلى إذن. هذه ليست خدمة، يُرجى تجنب الاعتماد عليها لأغراض الاختبار والمراقبة.

该域名仅用于文档示例，无需获得许可。这并非一项服务，请勿将其用于测试和监控目的。

L’usage de ce domaine est réservé à des exemples de documentation, sans autorisation préalable. Il ne s’agit pas d’un service ; son utilisation à des fins de test ou de surveillance est à éviter.

Данный домен предназначен для использования в примерах документации без необходимости получения предварительного разрешения. Это не сервис; не рекомендуется его использование для тестирования и мониторинга.

Learn more
```

---

## 5. Herramientas MCP Utilizadas
- **Playwright MCP Server:**
  - `browser_navigate` / enrutamiento y carga de la URL `https://example.com`.
  - `browser_snapshot`: Captura del árbol de accesibilidad del DOM.
  - `browser_evaluate`: Ejecución de JavaScript en el contexto del navegador para inspeccionar títulos, selectores de encabezados (`h1`–`h6`, `[role="heading"]`), y propiedades computadas de visibilidad en enlaces `<a>`.
