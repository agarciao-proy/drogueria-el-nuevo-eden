# Droguería El Nuevo Edén · Prototipo web

**Proyecto de grado – Fase 4 | Ingeniería de Sistemas, UNAD**  
**Caso de estudio:** Droguería El Nuevo Edén, Magangué (Bolívar).

## Propósito

Demostrar el flujo de gestión de productos, lotes, existencias, vencimientos y ventas, así como la consulta de alertas y reportes operativos en pesos colombianos (COP).

## Cómo abrir la demostración

- **En línea:** abrir la URL de GitHub Pages que aparece en **Settings → Pages** del repositorio.
- **En local:** abrir `index.html` en el navegador. Si el HTML carga datos o módulos que requieren servidor HTTP, ejecutar `python -m http.server 8000` en la carpeta del proyecto y abrir `http://localhost:8000`.

## Recorridos propuestos

| Perfil de demostración | Recorrido |
|---|---|
| Administración | Ingreso → productos → lotes y existencias → vencimientos y alertas → reportes. |
| Ventas y Dispensación | Ingreso → consultar existencia → registrar venta → confirmar → consultar el saldo. |

Estos recorridos describen el alcance esperado. La matriz de pruebas permite registrar cuáles se comprobaron en la versión publicada.

## Alcance y datos

La demo usa datos de demostración. GitHub Pages aloja archivos estáticos: no añade servidor de aplicación, base de datos compartida ni autenticación segura. Si la versión usa estados preparados o almacenamiento del navegador, describir ese comportamiento en el registro de pruebas. No cargar datos comerciales privados, credenciales reales, consentimientos ni firmas.

## Documentación

- [Publicación y entrega](docs/publicacion.md)
- [Trazabilidad, backlog y sprints](docs/trazabilidad-scrum.md)
- [Diseño y arquitectura](docs/diseno.md)
- [Matriz de pruebas funcionales](docs/pruebas-funcionales.md)
- [Guion del video](docs/guion-video.md)
