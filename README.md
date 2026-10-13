# Documentación RPA

Repositorio de recursos y documentación del **Servicio Social de Robotic Process Automation (RPA)**, coordinado por la Dra. Mery Helen Pesantes Espinoza.

Reúne en un solo lugar la documentación de los proyectos de automatización, los estándares del equipo y los materiales de aprendizaje para estudiantes y docentes, con las herramientas **UiPath**, **Automation Anywhere** y **Microsoft Power Automate**.

🌐 **Explorar en línea:** <https://documentacionrpa-organizacion.github.io/Documentacion-rpa/>

---

## Contenido

| Carpeta | Contenido | Estado |
|---|---|---|
| [`0_documentacion_proyecto`](0_documentacion_proyecto) | Documentación del proyecto: análisis As-Is, modelo To-Be, PDD, SDD, entradas y salidas, plan y casos de prueba, diagrama de proceso y checklist de información | ✅ Con contenido |
| [`1_estandares_y_metadatos`](1_estandares_y_metadatos) | Convenciones de nomenclatura y requisitos de metadatos | ✅ Con contenido |
| [`2_recursos_estudiantes`](2_recursos_estudiantes) | Materiales de aprendizaje por nivel: básico, intermedio y avanzado | 🟡 Parcial |
| [`3_recursos_docentes`](3_recursos_docentes) | Guías, presentaciones y rúbricas para la enseñanza de RPA | ⬜ Pendiente |
| [`4_herramienta_rpa`](4_herramienta_rpa) | Manuales y plantillas por herramienta (UiPath, Automation Anywhere, Microsoft Power Automate) | 🟡 Parcial |
| [`5_procesos_academicos_simulados`](6_procesos_academicos_simulados) | Automatizaciones de ejemplo de procesos académicos | ⬜ Pendiente |
| [`6_evaluacion_y_retroalimentacion`](7_evaluacion_y_retroalimentacion) | Criterios de prueba, encuestas y mejora continua | ⬜ Pendiente |
| [`7_informes_y_documentacion`](8_informes_y_documentacion) | Resultados de ejecución, métricas e informes finales | ⬜ Pendiente |
| [`8_Diplomas`](9_Diplomas) | Documentación del bot generador de diplomas (general e individual) | ✅ Con contenido |

### Proyecto documentado

La carpeta `0_documentacion_proyecto` contiene el ciclo completo de documentación de un proceso real, el **Bono de Productividad** (nóminas), siguiendo este orden:

1. **Análisis As-Is** (`0.1.I-01`) — cómo se hace el proceso hoy.
2. **Modelo To-Be** (`0.1.I-02`) — cómo será con el bot.
3. **PDD**, Documento de Diseño de Procesos (`0.1.I-03`) — el proceso desde el punto de vista del negocio.
4. **SDD**, Documento de Diseño de Solución (`0.1.I-04`) — el diseño técnico del bot.
5. **Entradas y salidas** (`0.1.I-05`) — archivos y datos que usa y produce el bot.
6. **Plan y casos de prueba** (`0.1.I-06`) — cómo se valida el bot.
7. **Diagrama de proceso** (`0.1.I-07`).

---

## Convención de nombres

Todos los archivos siguen el esquema definido en [`1.1.N-01_Convenciones_Nomenclatura.pdf`](1_estandares_y_metadatos/1.1.N-01_Convenciones_Nomenclatura.pdf):

```
[ÁREA].[NIVEL].[TIPO]-[CORRELATIVO]_Nombre_Descriptivo.ext
```

| Parte | Significado | Valores |
|---|---|---|
| Área | Carpeta principal | `0` a `8` (número de la carpeta) |
| Nivel | Complejidad | `1` Básico · `2` Intermedio · `3` Avanzado |
| Tipo | Tipo de recurso | `A` Guía/Manual · `B` Video · `C` Caso de estudio · `D` Ejercicio · `E` Encuesta · `I` Informe · `L` Presentación · `M` Metadatos · `N` Norma · `P` Proceso simulado · `R` Rúbrica · `T` Plantilla técnica |
| Correlativo | Número secuencial | `01`, `02`, … `99` |

**Ejemplo:** `2.1.A-01_Guia_Introduccion_RPA.pdf` → guía (A), nivel básico (1), recursos de estudiantes (2), primera de su tipo (01).

**Reglas:**

- El nombre empieza con el ID.
- Guion `-` antes del correlativo y guiones bajos `_` entre palabras.
- Sin espacios, tildes, `ñ` ni caracteres especiales.
- Cada ID es único: no repetir el mismo código en dos archivos.

---

## Cómo contribuir

1. Elige la carpeta según el área del recurso.
2. Nombra el archivo siguiendo la convención y verifica que el ID no exista.
3. Prefiere PDF para documentos finales. Si subes el editable (`.docx`, `.xlsx`), usa el mismo ID.
4. Si la carpeta tiene un `ToDo.txt`, actualízalo con lo que agregaste o propones.
5. Describe en el commit qué recurso agregaste, por ejemplo: `Agrega 2.2.A-01 Guía de modelado de procesos`.

No subas datos personales reales (nombres, nóminas, correos) en archivos de ejemplo: usa datos ficticios.

---

## Sitio web

El sitio se publica con GitHub Pages desde la rama `main`:

- `index.html` — página de inicio con acceso a cada carpeta.
- `contenido.html` — explorador de carpetas que lee el contenido del repositorio desde la API de GitHub, así que los archivos nuevos aparecen sin editar el HTML. Si agregas una carpeta principal nueva, añade su tarjeta en `index.html`.

---

## Herramientas

- [UiPath Studio](https://www.uipath.com/product/studio) y [UiPath Academy](https://academy.uipath.com/)
- [Automation Anywhere Community Edition](https://www.automationanywhere.com/products/community-edition)
- [Microsoft Power Automate](https://www.microsoft.com/power-platform/products/power-automate)
