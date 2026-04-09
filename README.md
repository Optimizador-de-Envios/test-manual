# Pruebas Manuales - Optimizador de Envios

Este repositorio reúne la documentación y las evidencias de la ejecución de pruebas manuales exploratorias realizadas sobre la aplicación **Optimizador de Envíos**.

La intención de este material es dejar registro claro de qué se probó, cómo se recorrieron los flujos principales y qué hallazgos aparecieron durante la sesión.

## Contenido del repositorio

- [REPORTE_EXPLORATORIO.md](REPORTE_EXPLORATORIO.md): documento principal con el detalle de la ejecución, observaciones, hallazgos y prioridades de mejora.
- `evidencias/`: capturas utilizadas para respaldar los casos revisados durante la exploración.

## Alcance de la exploración

Durante la sesión se revisaron los siguientes flujos:

- autenticación, logout e historial;
- registro de usuarios;
- formulario principal, autocompletado y selección de prioridad;
- recomendación de proveedores, alternativas y confirmación;
- visualización del mapa y comportamiento responsive.

## Resultado general

La aplicación permitió completar el flujo principal sin bloqueantes críticos. Los puntos a mejorar quedaron concentrados sobre todo en validaciones del lado cliente y en detalles de experiencia de usuario, como mensajes poco consistentes, riesgo de doble submit y pérdida de contexto al volver atrás en algunos recorridos.

## Nota

Este repositorio contiene artefactos de testing manual. No incluye el código fuente de la aplicación, sino el soporte documental de la ejecución realizada.
