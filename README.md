# camino-de-fe-legal

Sitio público mínimo de **Camino de Fe Diario** (sitio oficial + Términos de Servicio + Política de Privacidad).

Se usa como:

- **Web/Desktop URL** del app de TikTok for Developers
- **Terms of Service URL**
- **Privacy Policy URL**

## Estructura

| Ruta | Contenido |
|---|---|
| `/` | Sitio oficial |
| `/terminos.html` | Términos de Servicio |
| `/privacidad.html` | Política de Privacidad |

## Despliegue

Estático servido con nginx (`Dockerfile`). Desplegado en Dokploy.
