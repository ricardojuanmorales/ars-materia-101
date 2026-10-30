# CIFI 4074 · Ars Materia 101
# Catálogo Autosostenido de Prompts Maestros por Elemento · v0.3 CANDIDATO

**Fecha:** 2026-10-30  
**Estado:** CANDIDATO PARA REVISIÓN HUMANA Y PILOTO H10, NO APROBADO  
**Naturaleza:** complemento operativo del Patrón OVAt-H v1.0 VALIDADO (D-027) y del Protocolo de Preproducción v1.0 APROBADO (D-056). No sustituye FEHE/OVAt ni Gates.  
**Procedencia:** patrones H8/H6 provistos por el profesor y producción situada H9; instrucciones nuevas inferidas señaladas en sus módulos.  
**Versión congelable:** no editar estos módulos durante la prueba H10; registrar cambios propuestos en la bitácora experimental.

## Modo de uso en H10

1. Leer estado y autoridad en GitHub `main`: FEHE-H10, OVAt-H10 **aprobadas**, decisiones y gates, y matriz de componentes; **H10 FEHE aprobada para piloto por sí sola NO equivale a autorización para producir OVAt/Moodle**.
2. Construir correspondencia de funciones OVAt F1–F6 con los paquetes PM1–PM6. **PM4 es nodo FD condicional, no F4 canónica.**
3. Clasificar cada elemento: `OBLIGATORIO / CONDICIONAL AUTORIZADO / RESERVADO / NO APLICABLE`; añadir `INTEGRADO EN` para funciones satisfechas sin nuevo objeto.
4. Abrir **solo el prompt necesario**, sin exigir subir ejemplos H8/H9; completar datos desde fuentes canónicas.
5. Producir una candidata, revisar con docente, montar con confirmación y hacer QA situado antes de abrir el siguiente elemento.
6. Conservar desviaciones en bitácora, sin alterar el prompt congelado hasta Gate de transferencia.

**Codificación de paquetes:** PM1 bienvenida = F1; PM2 presentación y lectura = F2+F3; PM3 actividad y guía = F4; PM4 foro/tarea opcional = FD de Espiral (condicional); PM5 transferencia = F5; PM6 cierre = F6. Esta clasificación es **operativa** y no modifica la arquitectura curricular.

## Inventario de prompts disponibles (cada archivo es autónomo)

| Módulo | Pieza | Función | Activación | Archivo |
|---|---|---|---|---|
| PM1-01 | PM1 · Página de bienvenida | F1 · Apertura | según OVAt aprobado; no presume microactividad | `PM1-01_BIENVENIDA_PROMPT_v0.3_CANDIDATO.md` |
| PM1-02 | PM1 · Ilustración conceptual de apertura | F1 · Apertura | condicional: imagen pertinente y derechos/representación resueltos | `PM1-02_IMAGEN_APERTURA_PROMPT_v0.3_CANDIDATO.md` |
| PM1-03 | PM1 · Descripción de la ilustración de apertura | F1 · Apertura | solo si PM1-02 se aprobó para montaje | `PM1-03_DESCRIPCION_IMAGEN_PROMPT_v0.3_CANDIDATO.md` |
| PM2-01 | PM2 · Presentación Base FEHE ilustrada | F2 · Marco común FEHE | obligatorio si OVAt exige presentación; formato final autorizado | `PM2-01_PRESENTACION_PROMPT_v0.3_CANDIDATO.md` |
| PM2-02 | PM2 · Descripción Moodle de la presentación | F2 · Marco FEHE | si la presentación forma parte del paquete | `PM2-02_DESCRIPCION_PRESENTACION_PROMPT_v0.3_CANDIDATO.md` |
| PM2-03 | PM2 · Lectura Oficial Ilustrada | F3 · Profundización | obligatorio si OVAt contempla lectura; formato según especificación | `PM2-03_LECTURA_OFICIAL_PROMPT_v0.3_CANDIDATO.md` |
| PM2-04 | PM2 · Descripción Moodle de la Lectura Oficial | F3 · Profundización | si la lectura está autorizada y disponible | `PM2-04_DESCRIPCION_LECTURA_PROMPT_v0.3_CANDIDATO.md` |
| PM3-01 | PM3 · Página de Actividad Central | F4 · Actividad central | obligatoria para H con producto central aprobado | `PM3-01_PAGINA_ACTIVIDAD_PROMPT_v0.3_CANDIDATO.md` |
| PM3-02 | PM3 · Descripción Moodle de Actividad Central | F4 · Actividad central | si existe página de actividad aprobada | `PM3-02_DESCRIPCION_ACTIVIDAD_PROMPT_v0.3_CANDIDATO.md` |
| PM3-03 | PM3 · Guía de Auto-Estudio ilustrada con instrumento | F4 · Actividad central | si el andamiaje OVAt requiere guía; no universalizar guía separada | `PM3-03_GUIA_AUTOESTUDIO_PROMPT_v0.3_CANDIDATO.md` |
| PM3-04 | PM3 · Descripción Moodle de Guía de Auto-Estudio | F4 · Actividad central | si existe guía independiente | `PM3-04_DESCRIPCION_GUIA_PROMPT_v0.3_CANDIDATO.md` |
| PM3-05 | PM3 · Ilustración conceptual problematizadora | F4 · Actividad central | opcional según valor explicativo y control de representación | `PM3-05_ILUSTRACION_PROBLEMATIZADORA_PROMPT_v0.3_CANDIDATO.md` |
| PM3-06 | PM3 · Descripción de ilustración problematizadora | F4 · Actividad central | solo después de producir y revisar PM3-05 | `PM3-06_DESCRIPCION_ILUSTRACION_PROMPT_v0.3_CANDIDATO.md` |
| PM4-01 | PM4 · Foro de Discusión longitudinal | Espiral de Casos / nodo FD, NO F4 canónica | SOLO nodo autorizado por Tabla de Alineación y decisiones vigentes | `PM4-01_FORO_DISC_PROMPT_v0.3_CANDIDATO.md` |
| PM4-02 | PM4 · Descripción breve del Foro | Espiral de Casos / nodo FD | solo si foro autorizado y redactado | `PM4-02_DESCRIPCION_FORO_PROMPT_v0.3_CANDIDATO.md` |
| PM4-03 | PM4 · Tarea Opcional de consolidación | Espiral de Casos / nodo FD | solo cuando tarea opcional esté autorizada junto a su FD | `PM4-03_TAREA_OPCIONAL_PROMPT_v0.3_CANDIDATO.md` |
| PM4-04 | PM4 · Descripción Moodle de Tarea Opcional | Espiral de Casos / nodo FD | si tarea se autoriza; subpatrón sin ejemplo directo | `PM4-04_DESCRIPCION_TAREA_PROMPT_v0.3_CANDIDATO.md` |
| PM5-01 | PM5 · Transferencia breve integrada o autónoma | F5 · Transferencia/reutilización | función presente salvo excepción canónica; objeto Moodle solo si hace falta y está autorizado | `PM5-01_TRANSFERENCIA_PROMPT_v0.3_CANDIDATO.md` |
| PM5-02 | PM5 · Descripción Moodle de transferencia autónoma | F5 · Transferencia/reutilización | solo si PM5-01 produjo página autónoma autorizada | `PM5-02_DESCRIPCION_TRANSFERENCIA_PROMPT_v0.3_CANDIDATO.md` |
| PM6-01 | PM6 · Página de Cierre longitudinal | F6 · Cierre y continuidad | obligatoria salvo decisión curricular explícita | `PM6-01_CIERRE_PROMPT_v0.3_CANDIDATO.md` |
| PM6-02 | PM6 · Descripción Moodle del Cierre | F6 · Cierre y continuidad | si existe cierre terminado | `PM6-02_DESCRIPCION_CIERRE_PROMPT_v0.3_CANDIDATO.md` |

## Origen y advertencias específicas

- **Observados y refinados directamente:** bienvenida, presentación, lectura, actividad central, guía, ilustraciones, sus descripciones; cierre; foro FD4 y tarea opcional.
- **Derivados sin precedente independiente completo:** descripciones independientes de foro y tarea; transferencia autónoma y descripción de transferencia. Marcar éstos como `SUBPATRÓN INFERIDO` hasta validación.
- **No adoptar como universales:** 25 diapositivas H9, ~10 páginas de lectura H9, 5 páginas/16 apartados de guía H8, 225–300 palabras/75–125 palabras/3 puntos de FD4; el número de elementos y cargas depende de OVAt-H.
- **Cuidado de fuentes:** una imagen generada con IA no sustituye obra, evidencia documental, análisis técnico o fotografías originales.

## Condiciones de aceptación del catálogo antes de piloto

| Prueba | Umbral/indicador | Tipo de fallo |
|---|---|---|
| Cobertura | Todas las piezas del inventario y reglas de exclusión están descritas | Mayor si falta pieza autorizada |
| Autoridad | No producir antes de Gates; FEHE/OVAt prevalecen | Crítico |
| Autonomía | No se necesita re-subir ejemplos previos | Mayor si depende de ejemplo |
| Identidad | Caso/operación/producto propios de H destino, no clon H8/H9 | Mayor |
| Calidad editorial | Lectura desarrolla argumentos; presentación no es monotema visual; guía integrada | Mayor |
| Riesgo de representación | No presentar IA como evidencia, licencias revisadas | Crítico/Major |
| Carga | Sin duplicaciones o tareas inventadas | Mayor |
| Evidencia Moodle | Montado ≠ QA verificado; fuente del reporte identificada | Mayor |
| Estado de protocolo | Candidato hasta decisión humana documentada | Crítico si se promueve por IA |

## Rutas de persistencia candidatas (NO canónicas todavía)

Proponer alojamiento semántico bajo `03_METODOLOGIA_Y_FLUJO_DE_TRABAJO/PROTOCOLOS/PRODUCCION_Y_MONTAJE_OVAT_H/` para este catálogo y sus módulos, y anexos de ejecución bajo `19_IMPLEMENTACION_Y_DESPLIEGUE/OVAT_Y_MOODLE/H10/` **solo tras verificar convenciones de `main` y aprobación humana**. El ZIP local de esta respuesta no es un commit ni archivo canónico.
