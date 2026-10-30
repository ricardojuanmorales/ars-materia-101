# CIFI 4074 · Ars Materia 101
# Protocolo Maestro de Producción y Montaje OVAt-H

**Versión:** 0.3 CANDIDATO CONSOLIDADO · NO APROBADO  
**Fecha:** 30 de octubre de 2026  
**Procedencia:** experiencia situada de producción y montaje H9; patrones extraídos de ejemplos H8 y H6  
**Alcance:** producción, revisión, montaje y trazabilidad de paquetes Moodle de una unidad H  
**Autoridad:** subordinado a FEHE/OVAt aprobadas, decisiones y gates canónicos  
**Estado de repositorio:** archivo local candidato; contraste selectivo con GitHub `main` el 2026-10-30; sin commit ni aprobación formal

> **Regla rectora:** El protocolo de producción debe ser completo; la activación curricular de componentes debe ser selectiva, proporcional y expresamente autorizada.

## 1. Propósito y condiciones de uso

Este documento permite producir la siguiente unidad, inicialmente H10, **sin volver a cargar los documentos modelo de H8**. Conserva los patrones editoriales, pedagógicos, de composición visual, de descripción Moodle, QA y montaje extraídos durante H9. No reemplaza ni altera especificaciones FEHE/OVAt, decisiones D-XXX, acuerdos del Portafolio/Espiral, políticas de evaluación o instrucciones de Moodle.

Para producir deben existir **FEHE y OVAt vigentes y aprobadas, preproducción pertinente y Gate humano de Realización que autorice Carril B**, además de las **fuentes canónicas vigentes de la unidad destino** y las decisiones específicas que autorizan, reservan o excluyen actividades. Si faltan o son contradictorias, detener solamente la pieza afectada y solicitar decisión humana; no completar vacíos imaginando una autoridad.

### 1.1 Insumos mínimos para H10

1. FEHE-H10 vigente, título, movimiento intelectual, objetivos, caso central, fuentes y transferencia.
2. OVAt-H10 aprobada, funciones F1–F6, carga cognitiva, productos, acuerdos de evaluación y gate.
3. Estado de los nodos FD y PROEMA y reglas de Portafolio de Casos.
4. Restricciones del entorno Moodle y recursos ya existentes; plantilla visual/editorial cuando aplique.
5. Inventario de materiales H10 ya elaborados para impedir duplicados.

**No requeridos:** volver a subir las presentaciones, lecturas, guías, foros y cierres H8 usados para construir este prototipo.

## 2. Dos nomenclaturas: arquitectura curricular vs. montaje

**Funciones OVAt-H (canónicas):** F1 bienvenida; F2 presentación FEHE; F3 lectura/profundización; F4 actividad central; F5 transferencia breve; F6 cierre y continuidad. Estos nombres deben cotejarse contra la especificación aprobada de la H destino.

**Paquetes de montaje (operativos, no canónicos):**

| Código propuesto | Paquete práctico | Correspondencia funcional | Evidencia de la experiencia H9 |
|---|---|---|---|
| PM1 | Bienvenida | F1 | Texto, imagen conceptual, descripción |
| PM2 | Marco conceptual y lectura | F2 + F3 | Presentación, lectura ilustrada, descripciones |
| PM3 | Actividad central | F4 | Página, descripción, guía, ilustración, descripción de guía e imagen |
| PM4 | Foro y tarea opcional | Espiral de Casos / nodo FD; **no renumerar como F4 canónica** | Patrones extraídos, no aplicables a H9 |
| PM5 | Transferencia breve | F5 | Integrada en guía H9; recurso independiente no requerido |
| PM6 | Cierre | F6 | Página y descripción |

El código PM evita que un paquete operativo altere la numeración aprobada de funciones. **PM4 no es automáticamente una función adicional de OVAt** y su activación depende de los acuerdos de la Espiral.

## 3. Estados y decisiones de activación

Para **cada elemento**, registrar uno de cuatro estados: **OBLIGATORIO**, **CONDICIONAL AUTORIZADO**, **RESERVADO** o **NO APLICABLE**. La condición no se infiere por conveniencia editorial, sino de la autoridad curricular.

Para **cada entrega**, registrar: `SIN INICIAR → CANDIDATO → REVISADO POR DOCENTE → APROBADO PARA MONTAJE → MONTADO → QA VERIFICADO`. No convertir “montado” en “QA verificado” sin evidencia. Los prompts siguen siendo candidatos hasta revisión y aprobación independiente.

**Regla antirredundancia:** una función ya satisfecha en un recurso existente no obliga a crear otra página; registrar `INTEGRADO EN [recurso]`, con evidencia comprobable.

## 4. Flujo operativo reproducible por unidad

### Gate 0. Reconstrucción de autoridad y habilitación
Leer desde GitHub `main` la documentación canónica vigente: control maestro/estado, mapa de ruta, manifiesto de autoridad y estados, bitácora de decisiones, FEHE/OVAt y gates específicos. Resolver divergencias con decisión humana y conservar rutas/commit consultado. **No activar producción por poseer este protocolo ni por FEHE aprobada para piloto experimental: exigir Gate OVAt, preproducción proporcional y Gate de Realización vigentes.** **No usar el recuerdo conversacional como fuente canónica.**

### Paso 1. Matriz de activación
Antes de producir archivos, elaborar tabla por PM y pieza: función, fuente de autoridad, estado, producto, destino Moodle, dependencias, duración/carga, responsable de aprobación. Marcar qué funciones ya se cumplen dentro de otros recursos.

### Paso 2. Inventario constitutivo
Confirmar con el profesor el inventario del paquete **antes de producir contenido**. Inventarios observados en H9: PM1 bienvenida/imagen/descripción; PM2 presentación/lectura/descripciones; PM3 seis piezas; PM4 foro y tarea opcional con descripciones si existen; PM5 transferencia condicional; PM6 cierre/descripción. No declarar estos inventarios universales sin cotejo.

### Paso 3. Una pieza cada vez
Para cada pieza: (a) recuperar especificación, (b) ejecutar el módulo de prompt correspondiente, (c) entregar candidata, (d) recibir comentarios docentes, (e) revisar, (f) preparar texto/archivo para Moodle, (g) registrar resultado. **No avanzar automáticamente a otra pieza.**

### Paso 4. QA editorial, pedagógico y técnico
Aplicar la lista de §7. En recursos descargables, revisar archivo y renderizado real; en Moodle, comprobar visualización, enlaces, permisos, instrucciones, accesibilidad y que descripciones correspondan a los archivos definitivos.

### Paso 5. Montaje y verificación
El docente confirma el montaje. Registrar `MONTADO REPORTADO`, sin atribuir al sistema una inspección de Moodle que no ocurrió. Registrar `QA VERIFICADO` sólo cuando haya comprobación explícita. No crear modificaciones en repositorio sin autorización.

### Paso 6. Bitácora viva
Durante H10 capturar patrón aplicado, ajustes, problema detectado, decisión humana, impacto y versión. Mantener observaciones separadas de cambios normativos. Evitar nuevas decisiones D-XXX para ajustes editoriales menores.

### Paso 7. Gate final
Auditar cobertura FEHE/OVAt, carga real, productos existentes, trazabilidad, calidad, consistencia, ausencias y estado de publicación; someter para aprobación humana antes de promover el protocolo.

## 5. Prompt de arranque autosostenido para H10

> **ACTIVACIÓN · Producción y montaje OVAt-H10**  
> Trabajaremos en Ars Materia 101 · CIFI 4074, usando **Protocolo Maestro de Producción y Montaje OVAt-H v0.3 CANDIDATO CONSOLIDADO** como herramienta de trabajo, y GitHub `ricardojuanmorales/ars-materia-101` rama `main` como autoridad documental. Antes de producir, reconstruye el estado canónico, lee FEHE-H10, OVAt-H10, los gates/decisiones pertinentes y la trayectoria longitudinal; **no promuevas un candidato a aprobado**. Presenta (1) matriz de correspondencia de funciones F1–F6 y paquetes PM1–PM6, (2) estados obligatorio/condicional/reservado/no aplicable, (3) inventario de piezas para el primer paquete, (4) dependencias y contradicciones, si existen. Reutiliza los módulos §6 de este documento: **no pidas subir nuevamente ejemplos H8**. Produce **una pieza cada vez** siguiendo aprobación humana, QA, montaje y bitácora. No dupliques productos ni actives foros/tareas sin autorización. Las imágenes generadas por IA son conceptuales, nunca sustituyen pruebas históricas o científicas. Usa fuentes institucionales verificadas y separa hechos de ilustraciones. Al terminar cada paquete, indica exactamente qué está producido, montado, verificado y pendiente, sin afirmar commits o QA que no ocurrieron.

## 6. Catálogo autosostenido por elemento · SEPARADO Y COMPLETO

El texto compacto de §6 en v0.2 fue útil para orientar, pero insuficiente como sustituto estable de los ejemplos H8. **En v0.3 se sustituye por 21 prompts independientes**, incluidos en el directorio `prompts/` y listados en `00_INDICE_CATALOGO_PROMPTS_v0.3_CANDIDATO.md`.

**Ejecución:** abrir sólo el archivo del elemento que se va a producir, y obedecer su contrato de autoridad, su instrucción completa, su entregable y su QA. **Nunca generar todas las piezas por leer este índice.** Si un módulo contradice una decisión aprobada prevalece la decisión y se registra discrepancia para revisión humana. Los prompts ya integran la economía de tareas y el registro de piezas `NO APLICABLES` o `RESERVADAS`.

**Regla de versión:** los módulos son v0.3 CANDIDATOS. Antes de la prueba H10 deberán aprobarse y congelarse mediante Gate humano; las observaciones de H10 se registran externamente sin mutar esa versión durante el ensayo.

**Referencias internas:** ver índice para PM1 (bienvenida e imagen); PM2 (presentación y lectura con descripciones); PM3 (página, guía, imagen y descripciones); PM4 (foro, tarea y descripciones condicionales); PM5 (transferencia integrada/autónoma); PM6 (cierre y descripción).

## 7. QA transversal obligatorio

### A. Fidelidad curricular
- [ ] FEHE/OVAt vigentes leídas; versión y autoridad identificadas.
- [ ] Movimiento intelectual, caso, transferencia y producto coinciden con especificación.
- [ ] No se duplican tareas ni se abren componentes reservados.
- [ ] La función pedagógica es reconocible incluso cuando el recurso está integrado.

### B. Calidad intelectual
- [ ] Problema auténtico y operación cognitiva explícita.
- [ ] Contexto histórico, material y cultural suficiente; no profundidad aparente.
- [ ] Diferencia entre hipótesis, inferencia, observación, evidencia, dato y límite.
- [ ] Decisiones justificadas, incertidumbre expresada sin falsa certeza.
- [ ] Fuentes localizables, con atribuciones y límites de copyright.

### C. Experiencia estudiantil
- [ ] Una tarea central y producto reusable cuando corresponda.
- [ ] Instrucciones en secuencia manejable; extensión/duración proporcionadas.
- [ ] No exigir nuevos documentos o investigación que no estén autorizados.
- [ ] Transferencia y PROEMA conectados sin convertirse en tareas adicionales.

### D. Editorial y visual
- [ ] Presentaciones: variedad de composición y valor explicativo de cada visual.
- [ ] Lecturas: desarrollo sustantivo, no sinopsis de presentación.
- [ ] Imágenes IA: aviso de recreación conceptual, sin fingir evidencias reales.
- [ ] Tipografía y resolución legibles en Moodle y dispositivos móviles.
- [ ] DOCX/PDF/PPTX renderizados e inspeccionados, no sólo guardados.
- [ ] Accesibilidad: encabezados, contraste, texto alternativo y enlaces útiles.

### E. Montaje Moodle y registro
- [ ] Archivo final correcto, descripción correspondiente, enlaces abiertos.
- [ ] Orden, visibilidad, configuración de foro/tarea y permisos comprobados.
- [ ] Estado `MONTADO` respaldado por confirmación docente.
- [ ] `QA VERIFICADO` sólo si existe revisión explícita.
- [ ] Ajustes anotados con fecha; candidatos no promovidos silenciosamente.

## 8. Plantilla mínima de bitácora y matriz de piezas

| Unidad | Paquete | Pieza | Estado activación | Versión artefacto | Estado producción/montaje | Evidencia QA | Nota/decisión | Ruta canónica prevista |
|---|---|---|---|---|---|---|---|---|
| H10 | PM1 | Bienvenida | Por determinar | — | Sin iniciar | — | Requiere FEHE-H10 | Por definir con repositorio |

Formato de entrada de bitácora: `fecha · unidad/PM/pieza · entrada canónica · candidato elaborado · revisión humana · ajuste · decisión/estado · archivo/ruta · estado Moodle · evidencia QA · siguiente acción`.

## 9. Registro retrospectivo de H9 y pendientes no resueltos

- PM1: bienvenida e imagen/descripción trabajadas. Se confirmó en conversación montaje/verificación de la **imagen y descripción**, sin afirmar QA global de toda bienvenida.
- PM2: presentación y lectura oficiales, con descripciones, **montaje reportado**. Se observaron problemas iniciales de monotonía visual de presentación y profundidad de lectura; segundas versiones mejoraron el patrón.
- PM3: seis piezas (página/descripcion, guía/descripcion, ilustración/descripcion), **montaje reportado**.
- PM4: ejemplo FD4-H7+H8 y tarea opcional analizados para extraer patrón; **no se implementaron Foro ni Tarea Opcional en H9**. La frase «F4 montado» fue interpretada como cierre de paquete metodológico, no publicación de actividades.
- PM5: transferencia a pintura acrílica integrada en guía H9. No se requiere página autónoma; candidato separado existente.
- PM6: página de cierre y descripción trabajadas, **montaje reportado**.
- **Pendientes de reconciliación:** cotejar inventarios y designaciones operativas con la especificación OVAt aprobada; precisar rutas canónicas; verificar en Moodle cuando sea posible; compilar y aprobar formalmente el catálogo.
- **No consta aquí:** commit GitHub de este protocolo, actualización de índices canónicos, gate de aprobación ni verificación independiente de todo Moodle.

## 10. Prueba de transferencia H10 · Criterios de aceptación

Ejecutar en H10 **sin volver a cargar los ejemplos H8**. Comparar cada pieza con los siguientes indicadores:

1. **Autonomía:** producción a partir de FEHE/OVAt + este protocolo, sin documentos ejemplares antiguos.
2. **Fidelidad:** no desviaciones de arquitectura, secuencia, casos o productos aprobados.
3. **Calidad:** profundidad académica, andamiaje, riqueza visual y trazabilidad de fuentes.
4. **Carga:** ninguna tarea duplicada ni obligación artificial.
5. **Activación:** foros/tareas/transferencia sólo cuando autoriza la matriz.
6. **Montabilidad:** archivos, descripciones, enlaces y configuración Moodle correctos.
7. **Trazabilidad:** versión, origen, revisión humana, estado, evidencias y ruta.

**Registro de desviación:** `[Pieza] · [fallo] · [causa probable] · [ajuste candidato] · [impacto] · [validación docente]`. No corregir silenciosamente el protocolo rector durante la prueba.

**Gate propuesto:** `GO`, `GO CON CONDICIONES` o `NO GO`, determinado por revisión humana; cualquier promoción de v0.3 a aprobado requiere acta/decisión conforme al marco documental vigente.

## 11. Política de consolidación y persistencia

**Antes de H10:** presentar este documento, su catálogo y una matriz de cobertura a revisión humana; cotejar con repositorio `main`; acordar rutas canónicas; registrar versiones y cambios; **hacer commits sólo con autorización**. Una vez aprobado, usar una copia versionada y congelada durante la prueba H10, manteniendo las observaciones separadas.

**Después de H10:** analizar resultados frente a criterios §10 y decidir si se aprueba, revisa o expande el patrón a otras unidades. No confundir `prototipo probado` con `estándar institucional aprobado`.

## 12. Registro de procedencia del patrón

- Bienvenida: ejemplo H8, revisiones de ilustración de F1-H9 y decisiones docentes de estilo.
- Presentación: patrón H8 y aprendizaje de dos iteraciones H9 (diversidad de gramáticas visuales).
- Lectura oficial: patrón H8 y necesidad de mayor sustancia y apoyos visuales en H9.
- Actividad/Guía/Imagen: ejemplo H8, DCM-H9, descripciones Moodle y QA de cinco páginas de la guía.
- Foro: texto completo «FD4 · Discriminar/Diseñar · H7+H8», facilitado por el profesor.
- Tarea: ejemplo «Documenta tu Diseño de Investigación o Caracterización», facilitado por el profesor.
- Transferencia: decisión de integración en Guía H9, sin antecedente de página Moodle autónoma.
- Cierre: página H8 y descripción breve H6 facilitadas por el profesor.

**Advertencia de alcance:** este documento sintetiza las evidencias conversacionales y archivos accesibles durante la sesión. No sustituye una auditoría de los textos canónicos completos ni una inspección directa de Moodle/GitHub. Las instrucciones inferidas se señalan como tales y deben validarse en H10.


## 13. Addendum de auditoría de suficiencia y transferencia · 2026-10-30

**Estado:** observaciones de auditoría; no equivalen a decisión humana, enmienda del Patrón OVAt-H ni aprobación del protocolo. **Dictamen recomendado: GO CON CONDICIONES para revisión; NO AUTORIZA por sí mismo producir H10.**

### 13.1 Evidencia documental contrastada en GitHub `main`

- `00_CONTROL_MAESTRO/ESTADO_MAESTRO.md` · SHA blob `2307c89ab72fca4874376104805d6f5994575876`.
- `00_CONTROL_MAESTRO/MANIFIESTO_AUTORIDAD_Y_ESTADOS.md` · SHA blob `e70dfe4a7f7e5a48b293d9f7984b1054a97bfe2e`.
- `19_IMPLEMENTACION_Y_DESPLIEGUE/OVAT_Y_MOODLE/H9/CIFI4074_OVAt_H9_Especificacion_v0.1_APROBADA.md` · SHA blob `9d23642e8901e0ebdbe68c7790c89ea0b2374953`.
- `03_METODOLOGIA_Y_FLUJO_DE_TRABAJO/PROTOCOLOS/PATRON_OVAT_H_TRANSFERIBLE_v1.0_VALIDADO.md` · SHA blob `63f778d03809dea33afd44de0781e4d1a69318f3`.
- `03_METODOLOGIA_Y_FLUJO_DE_TRABAJO/PROTOCOLOS/PROTOCOLO_PREPRODUCCION_OVAT_H_v1.0_APROBADO.md` · SHA blob `f6e2fd1a0cd5977d9d5516420b10f1d6ee66dad3`.
- `00_CONTROL_MAESTRO/PROMPT_CONTINUIDAD_H9_PRODUCCION_F1_2026-10-23.md` · consultado como registro de continuidad, subordinado a las decisiones canónicas.

El cotejo de estos archivos **no sustituye** auditoría exhaustiva del repositorio, inspección del Moodle ni verificación del commit preciso de la rama. No se han certificado versiones Moodle de cada artefacto.

### 13.2 Hallazgos y tratamiento

| Código | Severidad | Hallazgo | Control antes de H10 |
|---|---|---|---|
| A01 | MAYOR preventivo | La existencia del prompt no constituye autorización de producir H10. | Gate 0 exige FEHE/OVAt aprobadas, preproducción aplicable y Gate de Realización. |
| A02 | MENOR estructural | PM son paquetes operativos H9, no funciones OVAt. | Proteger F1-F6 y registrar matriz de correspondencia por H. |
| A03 | MAYOR de suficiencia | Algunas subplantillas no incluyen parámetros suficientes de acabado editorial/visual ni ejemplos internos de calidad. | Completar fichas de diseño por artefacto, especificación de salida y QA verificable antes de congelar para H10. |
| A04 | MENOR de evidencia | Montaje reportado ≠ inspección independiente. | Conservar estatus y pedir evidencia de recorrido QA. |
| A05 | MENOR de cobertura | No se suministró ejemplo independiente de descripción de tarea opcional ni de transferencia autónoma. | Marcar tales prompts INFERIDOS/NO VALIDADOS, no afirmar transferencia probada. |
| A06 | MENOR curricular | FD5 reservado a H10 no equivale a activación automática. | Confirmar nodo, puntuación y modalidad en documentos aprobados de H10. |
| A07 | MENOR editorial | El cierre H9 candidato tendió a formular el puente a H10 en términos genéricos. | Cotejar explícitamente la frontera H10: diagnosticar / decidir / conservar; no sustituir FEHE-H10. |

### 13.3 Ficha autosostenida por pieza, obligatoria durante el piloto

Cada elemento debe llevar encabezado documental con: código PM; función OVAt o FD; estado curricular; fuente canónica (ruta, versión, decisión); resultado esperado; formato Moodle; audiencia; tiempo; estructura; detalles disciplinares no negociables; fuente y licencias; gramática visual (si aplica); citación y aviso IA; especificación exacta de salida; prueba QA; estado y aprobación docente. Ninguna ficha puede rellenar supuestos no documentados.

**Presentación Base:** exigir variación compositiva deliberada, diagramas originales con función explicativa, dimensión histórica/material situada, referencias por afirmación, guion de profundidad proporcionado y revisión diapositiva a diapositiva. No fijar números de diapositivas H8/H9 como norma.

**Lectura oficial:** desarrollar un argumento legible autónomo, con contexto histórico, problema técnico-material situado, análisis de evidencia e inferencia, ilustraciones/diagramas pertinentes, preguntas selectivas y referencias; no reducirla a transcripción de la presentación. La extensión depende de carga OVAt, no del número de páginas del ejemplo.

**Guía de Auto-Estudio:** enlazar problema/caso, dossier, preguntas orientadoras y producto reusable en una única ruta; preservar los campos exactos del producto de la H destino, instrucciones de citación y uso de IA; inspección de documento renderizado.

**Ilustración conceptual:** elaborar un concepto visual original específico a la operación intelectual, no volver al mismo diagrama repetitivo; diferenciar mediación visual de dato histórico o científico; crear descripción Moodle y alt text funcional como piezas distintas.

**Foro y tarea opcional:** recuperar nodo FD, función longitudinal y producto Portafolio; interacción sustantiva, evaluación autorizada, consolidación no redundante; si está reservado, registrar **OMITIDO POR AUTORIDAD**, sin montar.

**Transferencia breve:** comprobar satisfacción mediante recurso existente; si integrada, registrar lugar exacto y evidencia; si autónoma, justificar por qué agrega aprendizaje no duplicado.

**Cierre:** verificar estados reales de Espiral, PROEMA y productos, progreso longitudinal, recursos opcionales y puente fiel a la siguiente H; sin nuevas tareas.

### 13.4 Criterios de aceptación durante H10

Para cada pieza registrar: `AUTÓNOMA SIN EJEMPLO H8: SÍ/NO`, `ALINEACIÓN OVAt: SÍ/NO`, `DUPLICACIÓN: SÍ/NO`, `QA DE RENDER: SÍ/NO/NO APLICA`, `QA MOODLE: REPORTADO/VERIFICADO/PENDIENTE`, `ITERACIONES`, `INTERVENCIÓN DOCENTE` y `DESVIACIÓN`. Un fallo de autonomía o alineación impide declarar el protocolo validado, aunque el material haya podido montarse con corrección humana.

### 13.5 Secuencia de decisión recomendada

1. Revisión humana del dictamen y de esta versión 0.2 candidata.
2. Completar fichas robustas de los artefactos que aún dependan de instrucciones genéricas.
3. Confrontar con requisitos vigentes H10; definir rutas canónicas sin inventarlas.
4. Aprobar, si procede, **PARA PILOTO EXPERIMENTAL**, no como protocolo validado.
5. Versionar/congelar y registrar la versión aprobada antes de H10.
6. Ejecutar H10 sin ejemplos H8; documentar desviaciones; someter a Gate de transferencia posterior.

**Ningún archivo de esta auditoría ha sido promovido, comprometido en GitHub o montado en Moodle.**

## 14. Acciones para congelación experimental H10

1. Confirmar revisión humana de los 21 prompts, con énfasis en módulos inferidos PM4-02, PM4-04 y PM5-02.
2. Verificar que ningún módulo modifica FEHE/OVAt ni exige contenido reservado. Confirmar identidad específica H10 al momento de uso.
3. Aprobar versión de piloto mediante decisión humana; **no equivale** a autorizar producción H10 sin sus propios Gates.
4. Fijar ubicación y commit de referencia en GitHub `main` cuando se autorice escritura; registrar hash/versión del ZIP congelado.
5. Aplicar al primer paquete H10 sin re-subir ejemplos H8/H9, registrar desviaciones y ejecutar QA por pieza.
6. Después de H10 someter autonomía y calidad a Gate de transferencia.
