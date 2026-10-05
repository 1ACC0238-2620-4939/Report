# Auditoría general TB1

Fecha: 05/10/2026, America/Lima. Fuentes: `../README.md`, `../../Enunciado.pdf` V4.0 (52 páginas), los cinco documentos de `../deliverables/` y el código/configuración de los productos. Se revisó el alcance específico TB1 de la página 34 y los requisitos transversales de las páginas 3-5, 20-30 y 32-33. **Resultado: PARTIAL; no está listo para entrega completa.**

## Hito TB1 y documentos

| Requisito | Evidencia actual | Estado / acción de cierre |
|---|---|---|
| Registro de versiones, colaboración y Student Outcome actualizados (p.34) | Secciones al inicio de README; actividad y contribuciones TB1 registradas | PARTIAL: Cesar y Jose no tienen evidencia personal TB1 suficiente; no inventar contribuciones |
| Mejoras de artefactos previos, capítulo III (p.34; detalle pp.20-23) | Wireframes, mock-ups, siete wireflows, siete user flows y prototipo | PARTIAL: SG-01/02/03, IA-01/02 y NAV-01/02/03 figuran `NOT_VERIFIED` en README. Verificar fuentes y herramientas prescritas (Figma, LucidChart/Overflow) |
| Capítulo IV, Sprint 1 (p.34; pp.24-30) | Configuración, planning, backlog, commits, capturas, ejecución, endpoints, deployment y colaboración | PARTIAL: planning reconstruido y LACX pendientes de validación; pruebas, tablero y videos incompletos |
| Landing desplegada (p.34) | Railway raíz HTTP 200 revalidado en esta auditoría | PASS para disponibilidad; no prueba por sí sola i18n/a11y ni cumplimiento de toda la experiencia |
| Backend desplegado al 70% (p.34) | OpenAPI público HTTP 200 revalidado; viajes, tracking, flota y perfiles; prueba MySQL previa documentada | NOT_VERIFIED: un endpoint disponible o cuatro contextos no demuestran 70% funcional. Crear matriz de historias/criterios y verificar cada capacidad; IAM no implementado |
| Pantallas core de aplicación (p.34) | Capturas y ejecución Android Emulator documentadas | PASS para alcance UI; datos provienen de DemoTraktoRepository. Integración REST y aceptación end-to-end pendientes; no confundir con requisito TB1 de mostrar pantallas |
| Conclusiones (p.34) | Cinco conclusiones técnicas, limitaciones explícitas | PARTIAL: no hay contraste de hipótesis con validaciones reales; conclusiones del producto dependen de entrevistas |
| Bibliografía y anexos (pp.5,32,34) | Cinco enlaces de documentación y anexos de herramientas/entrevistas/videos | PARTIAL: faltan categorías y citas APA completas; revisar referencias del dominio y métodos. Cuatro papers Q1/Q2 recientes se exigen expresamente al informe final (p.32), no se presentan aquí como un bloqueo exclusivo del hito TB1 |
| Informe PDF (p.3) | 215 páginas, publicado en release v2.0.0 | PARTIAL: existe, pero su contenido y formato conservan pendientes |
| Presentación PPTX/PDF (p.3) | Exportaciones Canva recibidas: 14 diapositivas/páginas, PPTX ZIP íntegro; PDF inspeccionado en conjunto | PARTIAL: no hay diapositiva introductoria de integrantes con fotos, nombres, apellidos y carreras. Contenido: portada, Product Backlog, siete User Flows, tres vistas de prototipado, landing y cierre; falta presentar la evidencia de implementación/backend y gestión del Sprint 1 |
| Participación Word/PDF (p.4, Anexo B p.41) | Ambos archivos preparados, Alexander identificado como Team Leader | PARTIAL: propuesta de calificaciones, no evaluación confirmada por Alexander; validar contenido y firma |
| ZIP de artefactos y proyectos (pp.3-4) | Paquete local de cuatro repositorios | Disponible; actualizar con las exportaciones Canva y con cada corrección posterior |
| Exposición MP4, enlace privado, máximo 15 minutos (p.4) | Anexo C identifica el video como bloqueado | BLOCKED: falta grabación real con presentación ante cámara de cada integrante, archivo y enlace |

## Brechas documentales concretas

1. **Entrevistas:** 2.2 contiene seis entrevistas de descubrimiento del AV1. No sustituyen las entrevistas de validación de 4.3.2. Allí faltan 3-5 sesiones por cada uno de los dos segmentos (6-10 en total), nombres, edad, distrito, capturas, URL institucional, inicio, duración y resumen observado (p.30). La evaluación heurística 4.3.3 está pendiente de esas sesiones.
2. **Fotos:** Cesar (`miembro1.png`) y Jose (`miembro4.png`) continúan con placeholders. La presentación oficial de Canva no incluye una diapositiva del equipo, por lo que las fotos disponibles de los otros integrantes tampoco aparecen allí.
3. **Pruebas:** 4.2.1.5 reconoce ausencia de suite de aceptación; la evidencia de un test de carga de contexto no cubre reglas de negocio. El enunciado pide pruebas unitarias, de integración y aceptación automatizadas ligadas al Sprint; para BDD, `.feature` y Steps (pp.28-29).
4. **Tablero:** el reporte usa una captura de un tablero consolidado local y un enlace de invitación Trello; la presentación muestra `https://trello.com/b/YlramyOI`. Contrastar que ambos corresponden al mismo tablero y que el Sprint Board es accesible y actualizado en la herramienta exigida (p.28). No se verificó acceso autenticado a Trello.
5. **Deployment:** 4.1.4 contiene la configuración y enlaces, pero no incrusta el Deployment Diagram C4 requerido en esa misma sección (p.25); el informe tiene un diagrama en 2.5.3.3. Referenciarlo e incorporarlo en la sección requerida.
6. **Contradicciones:** 4.1.2 afirma que no existen tags SemVer, aunque ya se publicaron v1.0.0/v2.0.0. 4.2.1.7 dice que no está verificada la ejecución con MySQL/request-response, contradiciendo `docs/railway-deployment.md` y 4.2.1.8. Actualizar texto y exportación antes de entregar.
7. **APA/formato:** el exportador vigente usa párrafos justificados, interlineado 1.45 y no establece la sangría de primera línea de 0.5 pulgadas ni la sangría francesa bibliográfica. El enunciado exige alineación izquierda e interlineado 1.5 (p.5). La existencia de números de página y control de viudas/huérfanas no acredita todo APA. No se realizó una inspección nueva página por página de las 215 páginas en esta auditoría.
8. **Colaboración y participación:** validar las celdas LACX no verificadas, estimaciones, fechas/lugar del planning y calificaciones con Alexander; respaldar aportes reales individuales. No basta que el informe compile o que haya commits de integración.

## Alcance que no debe adelantarse ni confundirse

App Validation, About-the-Product y About-the-Team tienen su primera versión exigida en AV2 y versión final en TB2 (pp.34-35). No son tres videos adicionales obligatorios para declarar cumplido el hito TB1. Sí es obligatorio el video de exposición para cada entrega (p.4), además de la evidencia de ejecución del Sprint (p.29).

Los requisitos globales de app física, almacenamiento local, recurso del dispositivo, servicio de terceros, feature de aprendizaje autónomo, i18n/a11y y experiencia multiplataforma siguen dentro del trabajo final (pp.2,32-33). TB1 pide pantallas core; su cierre completo no se presupone para este hito. Aun así, la landing ya publicada debe revisarse contra los constraints aplicables, incluido idioma inglés por defecto. No se efectuó una auditoría completa de accesibilidad ni de i18n en esta revisión.

## Orden recomendado de cierre

1. Corregir inconsistencias del informe, completar evidencia visual III y diagrama de deployment IV; revisar fuentes/herramientas.
2. Completar pruebas y contrastar el 70% del backend con historias y criterios de aceptación verificables.
3. Incorporar la diapositiva del equipo y evidencia del Sprint 1 en la presentación oficial, con fotos reales.
4. Obtener entrevistas de validación y desarrollar evaluación heurística/conclusiones desde evidencia real.
5. Validar con Alexander el planning, LACX y participación; grabar exposición y completar enlaces.
6. Ajustar APA y exportar/revisar nuevamente informe y presentación; reconstruir ZIP con los archivos finales.
7. Entregar solo cuando Jean lo indique. No se ha enviado nada a Teams/Aula Virtual ni al OneDrive del docente.
