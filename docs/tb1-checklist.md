# Checklist cronológico de cierre TB1

Fecha de corte: 04/10/2026.

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
- [x] **11. Verificar el informe actualizado.** Se validaron 92 referencias locales sin archivos faltantes y se revisó visualmente el PDF final de 218 páginas.
- [ ] **12. Completar evidencias humanas.** `BLOCKED`: requiere entrevistas reales, videos, timing, consentimiento y hallazgos del equipo.
- [ ] **13. Completar gestión del Sprint.** `BLOCKED`: requiere fecha, hora, lugar, responsable, estimaciones y Board reales acordados por el equipo.
- [ ] **14. Demostrar integración end-to-end.** `NOT_VERIFIED`: mobile-app usa `DemoTraktoRepository`; falta el adaptador REST y una API pública saludable.
- [ ] **15. Publicar video de exposición.** `BLOCKED`: requiere grabación y carga con una cuenta del equipo; duración máxima indicada por el enunciado.
- [ ] **16. Completar entrega externa.** `BLOCKED`: requiere archivos de presentación, evaluación de participación y carga final en la plataforma del curso.

## Evidencia verificada

| Producto | Estado | Evidencia |
|---|---|---|
| Landing Page | `PASS` | Build estático, ejecución HTTP local y GitHub Pages configurado desde `main` |
| Backend | `PASS` parcial | `./mvnw test`: 1 test, 0 fallos; imagen Docker construida; runtime público nuevo aún `NOT_VERIFIED` |
| Android | `PASS` parcial | `clean assembleDebug lintDebug`; APK instalado; navegación verificada en Android Emulator |
| Informe | `PASS` técnico | Versiones, Student Outcome TB1, capítulos III/IV, artefactos UX/UI, prototipo, videos, capturas, endpoints, conclusiones, bibliografía y estados explícitos |

## Releases

| Repositorio | Release en `main` |
|---|---|
| backend | `3d2cad9` |
| landing-page | `3af2425` |
| mobile-app | `5641a0f` |

Los ítems bloqueados no pueden cerrarse de forma válida solo con cambios de código: dependen de evidencia obtenida por el equipo y de acciones en cuentas externas.
