# Checklist cronológico de cierre TB1

Fecha de corte: 05/10/2026. Revisión final contra el enunciado TB1, páginas 3-5 y 34.

## Trabajo técnico y documental

- [x] **1. Sincronizar repositorios remotos.** Se incorporó a `develop` el contenido más reciente de `main` en Report.
- [x] **2. Revisar el enunciado.** Se contrastó la entrega TB1 con `Enunciado.pdf`.
- [x] **3. Inventariar productos.** Se revisaron Report, backend y landing-page; se creó mobile-app porque no existía un repositorio Android.
- [x] **4. Auditar el informe.** Se localizaron placeholders, enlaces faltantes y afirmaciones sin evidencia.
- [x] **5. Auditar builds y ejecución.** Backend, Landing Page y Android se probaron en sus entornos reproducibles.
- [x] **6. Aplicar GitFlow.** Los productos usan ramas `feature`, `develop`, `release` y `main`.
- [x] **7. Completar el incremento verificable.** Se construyeron las pantallas Android, se preparó el backend para test/build y se publicó el Landing Page.
- [x] **8. Incorporar evidencia.** Se añadieron capturas reales, commits, repositorios, endpoints, resultados y límites verificables al informe.
- [x] **9. Completar los artefactos UX/UI.** Se incorporaron los wireframes y mock-ups de Landing Page y aplicación móvil, siete Wireflows y siete User Flows trazables a los User Goals.
- [x] **10. Completar el prototipado.** Se añadió un prototipo móvil navegable, una vista general y videos MP4 reproducibles para la aplicación y el Landing Page.
- [x] **11. Verificar el informe actualizado.** Se validaron 105 referencias locales sin archivos faltantes y se revisó el PDF final de 215 páginas, con inspección visual de las secciones modificadas.
- [ ] **12. Completar evidencias humanas.** `BLOCKED`: requiere entrevistas reales, videos, timing, consentimiento y hallazgos del equipo.
- [x] **13. Completar gestión del Sprint.** Se consolidaron fecha, hora, lugar, Team Leader, duración, Story Points, estimaciones, responsables y Sprint Board, manteniendo integración y aceptación como trabajo abierto.
- [ ] **14. Demostrar integración end-to-end.** `NOT_VERIFIED`: mobile-app usa `DemoTraktoRepository`; falta el adaptador REST. La API pública y su persistencia MySQL ya están verificadas.
- [ ] **15. Publicar video de exposición.** `BLOCKED`: requiere grabación y carga con una cuenta del equipo; duración máxima indicada por el enunciado.
- [ ] **16. Preparar los documentos de entrega.** Informe PDF y participación DOCX/PDF generados. La presentación oficial es [el Canva proporcionado por Jean](https://canva.link/kblei7h4yf7tva3); falta exportar sus entregables PPTX/PDF. La presentación generada anteriormente queda como apoyo técnico. Las calificaciones son una propuesta que Alexander debe validar y firmar.
- [x] **17. Desplegar frontend y backend en Railway.** Servicios RUNNING; landing HTTP 200 y `/health`; OpenAPI HTTP 200; POST/GET de vehículo con MySQL verificados. Ver `railway-deployment.md`.
- [ ] **18. Completar fotografías.** Cesar y Jose deben proporcionar fotografías reales para la diapositiva del equipo.
- [ ] **19. Validar participación.** Alexander debe revisar responsabilidades, calificaciones y firma del informe de participación.
- [ ] **20. Acreditar porcentaje de backend.** El enunciado exige 70%; están desplegados Trip Management, Tracking, Fleet Management y Profile. IAM y otros contextos del diseño no están implementados. El porcentaje no se declara aprobado sin contrastar el alcance funcional con la rúbrica.
- [ ] **21. Confirmar datos reconstruidos del Sprint.** Fecha, horario, lugar y estimaciones son una consolidación propuesta, sin acta real comprobada; Alexander debe validarlos.
- [ ] **22. Entregar en la plataforma del curso.** Pendiente por instrucción del usuario: todavía no entregar.

## Evidencia verificada

| Producto | Estado | Evidencia |
|---|---|---|
| Landing Page | `PASS` | Build estático, ejecución HTTP local y GitHub Pages configurado desde `main` |
| Backend | `PASS` deployment; alcance parcial | `./mvnw test`: 1 test, 0 fallos; Docker construido en Railway; OpenAPI HTTP 200 y MySQL write/read PASS |
| Android | `PASS` parcial | `clean assembleDebug lintDebug`; APK instalado; navegación verificada en Android Emulator |
| Informe | `PASS` técnico | Versiones, Student Outcome TB1, capítulos III/IV, artefactos UX/UI, prototipo, videos, capturas, endpoints, conclusiones, bibliografía y estados explícitos |

## Releases

| Repositorio | Release en `main` |
|---|---|
| backend | `915662b` |
| landing-page | `96bead9` |
| mobile-app | `5641a0f` |

Los ítems bloqueados no pueden cerrarse de forma válida solo con cambios de código: dependen de evidencia obtenida por el equipo y de acciones en cuentas externas.
