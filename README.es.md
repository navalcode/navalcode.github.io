# Recursos de GitHub Pages

[English](README.md) · [Web personal](https://navalcode.github.io/personal-website/es.html) · [Perfil GitHub](https://github.com/navalcode)

Recursos estáticos utilizados para asociación de aplicaciones, políticas de privacidad y ejemplos de autenticación. La web personal se mantiene en [personal-website](https://github.com/navalcode/personal-website).

| Ruta | Función |
|---|---|
| `.well-known/assetlinks.json` | Datos de asociación de aplicaciones Android |
| `privacy/` | Páginas de privacidad de aplicaciones |
| `app-ads.txt` | Declaración existente de publicidad de aplicaciones |
| `AuthFromServer.json`, `RegFromServer` | Recursos existentes del ejemplo de autenticación |
| `index.html` | Página de prueba anterior conservada por compatibilidad |
| `portfolio/` | Redirecciones de compatibilidad para las URL anteriores de la web personal |

GitHub Pages sirve `main` desde la raíz en `https://navalcode.github.io/`. Se ha retirado el dominio personalizado anterior. Las configuraciones de aplicaciones que todavía utilicen ese host necesitan su propia migración; conservar estos archivos no actualiza las aplicaciones instaladas.

Los recursos existentes conservan su contenido e historial. Los cambios de asociación o configuración de servicios deben revisarse con la aplicación que los consume.

## Navegación de compatibilidad

La entrada anterior [inglesa](https://navalcode.github.io/portfolio/) y [española](https://navalcode.github.io/portfolio/es.html) abren inmediatamente la versión correspondiente de la web personal. Si se bloquea la navegación automática, el fallback accesible ofrece enlace manual, perfil GitHub y cambio de idioma. Las [decisiones de diseño](DESIGN.md) y el [aviso de la fuente](THIRD_PARTY.md) explican esta superficie de compatibilidad.
