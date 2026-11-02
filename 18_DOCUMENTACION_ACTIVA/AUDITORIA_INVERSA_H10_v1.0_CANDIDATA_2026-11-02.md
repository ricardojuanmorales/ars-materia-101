# AUDITORÍA INVERSA H10 · Ars Materia 101
**Versión:** 1.0 CANDIDATA · **Fecha:** 2026-11-02  
**Estado:** AUDITORÍA DOCUMENTAL REALIZADA · QA SITUADO PENDIENTE · GATE INTEGRAL H10 NO CERRADO  
**Objeto:** reconstruir la cadena Moodle reportado → PM1–PM6/FD5 → F1–F6 → OVAt-H10 → FEHE-H10 → autoridad de decisiones, e identificar brechas antes del Gate Integral.  
**Limitación:** no se inspeccionó directamente Moodle, ni se verificaron las versiones finales de archivos binarios montados; no afirmar «MONTADO Y VERIFICADO EN MOODLE».

## 1. Evidencia humana de montaje y alcance
El docente ha confirmado sucesivamente **PM2 montado; PM3 montado; FD5 y Tarea Opcional montadas; PM6-01 montado; y el 2 de noviembre PM6-02 montado**. Se había aprobado editorialmente F1 y reportado montaje de componentes parciales. Se documenta el paquete F1/PM1 en GitHub, pero **no se localizó en los registros revisados una confirmación específica y contemporánea de montaje/QA independiente de PM1**, ni acceso a la instancia real Moodle.

**Estado de PM6-02:** «PM6-02 montado» (declaración humana de 2026-11-02) → **MONTADO REPORTADO POR DOCENTE**. No se atribuye aprobación retroactiva, calificación correcta ni QA situado.

Los estados de archivos `CANDIDATO` en GitHub constituyen genealogía documental, no prueba de que esas versiones fueran las que efectivamente quedaron en Moodle.

## 2. Cadena de autoridad
- FEHE-H10 profunda v1.0 **APROBADA CON CONDICIONES** D-059.
- OVAt-H10 v0.1 **APROBADA PARA PREPRODUCCIÓN CON CONDICIONES** D-060.
- Gate Realización H10 **REALIZACIÓN APROBADA CON AJUSTES LOCALES NO BLOQUEANTES** D-061, Carril B activo.
- Espiral de Casos D-024, Tabla de Alineación v2.0: FD5 H9+H10 **DECIDIR/SINTETIZAR**, **3 puntos** y Cierre reflexivo del Portafolio de Casos.
- Gate específico FD5 (2026-11-01): **GO CON CONDICIONES para DISEÑO/PRODUCCIÓN CANDIDATA**, montaje sujeto a revisión. Posteriormente el docente reportó montaje FD5 y PM4-03. Se necesita reconciliar el control editorial, **sin inferir un GO retroactivo**.
- Decisión PM5-01 (2026-11-01): **F5 INTEGRADA EN PM3-03, p.5, CON AJUSTE LOCAL NO BLOQUEANTE**; PM5-02 NO REQUERIDA.
- Patrón OVAt-H v1.0 D-027 **VALIDADO**, Protocolo Preproducción v1.0 D-056 **APROBADO**, Protocolo Maestro Montaje v0.3 D-058 **PILOTO CONGELADO**.

## 3. Arquitectura inversa F / PM y cumplimiento documental

| Función | Paquete y evidencia documental | Estado verificable | Resultado |
|---|---|---|---|
| F1 Orientación | PM1, F1 Bienvenida v1.0 aprobada para montaje, caso *The Night Watch* y pregunta inicial | **Aprobación editorial documentada**, montaje PM1/QA no confirmado expresamente aquí | **PARCIAL: constatar PM1 en LMS** |
| F2 Marco FEHE | PM2-01/02, Presentación v0.3 reconstruida a **25 diapositivas**; registro del docente «PM2 montado» | Binario no archivado; versión LMS no cotejada | **CUMPLE EN DISEÑO; QA/versión PENDIENTE** |
| F3 Lectura Oficial | PM2-03/04, Lectura v0.2 **10 páginas/8 ilustraciones**; PM2 montado reportado | PDF/DOCX no archivados; versión LMS no cotejada | **CUMPLE EN DISEÑO; QA/versión PENDIENTE** |
| F4 Actividad central | PM3-01 a 06; caso real institucional + escenarios explícitamente hipotéticos; MDS-H10 **8 campos/una vista**; guía 5 páginas, imagen PM3-05 v0.2 y descripción PM3-06 v0.2 | PM3 montado reportado; binarios no archivados; contenidos LMS no comprobados | **CUMPLE EN DISEÑO; QA PENDIENTE** |
| F5 Transferencia | PM5-01: **INTEGRADA EN PM3-03 p.5**, obra contemporánea con polímero envejecido; PM5-02 no requerida | Aprobación humana de vía integrada; mejora local no bloqueante no consta aplicada | **CUMPLE CON AJUSTE LOCAL PENDIENTE** |
| FD5 Espiral | PM4-01 H9+H10 Decidir/Sintetizar, caso Portafolio, reflexión y respuesta a par, **3 pts** | FD5 montado reportado; rúbrica efectiva, plazos y visibilidad no comprobados | **CUMPLE EN PROPUESTA, QA EVALUATIVO PENDIENTE** |
| PM4-03 opcional | «Documenta tu decisión y su revisión», consolidación voluntaria, sin puntos adicionales | Montada según docente; configuración y finalización obligatoria no comprobadas | **QA DE OPCIONALIDAD PENDIENTE** |
| F6 Cierre | PM6-01 cierre H1–H10 y PM6-02 descripción; ambas montadas según docente | No QA situado; sin H11 ficticia, PROEMA separada | **CUMPLE EN DISEÑO; QA PENDIENTE** |

**PM4 NO es F4.** F4 corresponde a PM3; PM4 sostiene el nodo longitudinal FD5.

## 4. Fidelidad disciplinar y epistemológica
**Movimiento:** DIAGNOSTICAR, DECIDIR Y CONSERVAR RESPONSABLEMENTE.  
**Concepto:** DECISIÓN CONSERVATIVA SITUADA.  
**Cadena:** valores/contexto → observación/evidencia → inferencia/diagnóstico provisional → incertidumbre → alternativas (incluida no intervención) → consecuencias/compatibilidad/sostenibilidad → decisión argumentada → documentación/monitoreo/revisión.

La página central, la MDS y el cierre vinculan hechos y límites con juicio provisional. No se equipara intervención técnica con justificación patrimonial. El caso rector está situado en Rembrandt, *La ronda de noche* y Operation Night Watch del Rijksmuseum; las alternativas A/B/C se presentan como **deliberación académica hipotética**. No se atribuye uso de geles/nanomateriales a la intervención del Rijksmuseum.

**Dictamen:** CUMPLE EN DISEÑO DOCUMENTADO. La comprobación de lo que realmente ve el estudiante en Moodle queda pendiente.

## 5. Producto reusable y economía
**MDS-H10 = una matriz, ocho campos, una vista**: contexto/valores; condición; evidencia/certeza; materiales/mecanismo/riesgos; alternativas; consecuencias; decisión/voces; monitoreo/revisión/límite. Guía PM3-03 pagina 4. F5 conserva esa matriz sin nueva ficha. FD5 recupera casos A/B/(C) y no convierte Portafolio en investigación paralela ni exige una nueva DCM/MDS. La tarea opcional debe permanecer voluntaria y sin puntuación; requiere confirmación de la configuración Moodle para validar ese requisito.

**Dictamen:** CUMPLE EN DISEÑO; implementación exacta no certificada.

## 6. Caso, fuentes, visualidad y derechos
- Corpus institucional declarado: Rijksmuseum Operation Night Watch, pruebas de retirada de barniz y comunicado de inicio de restauración (2024). En los materiales el expediente documental se distingue de escenas hipotéticas.
- La portada conceptual y los diagramas de F2/F3 y PM3-05 ilustración IA NO son datos de microscopía, documentación histórica o evidencia técnica.
- PM3-05 v0.2 (1672×941, SHA-256 en ficha canónica) es una recreación conceptual; PM3-06 v0.2 recuperó formato Moodle de párrafo único, con alt text separado. **No se ha verificado que la imagen final y descripción montadas sean exactamente las versiones v0.2** ni su legibilidad en teléfonos.
- F2 y F3 se reconstruyeron por intervención docente de 17/6 a **25 diapositivas/10 páginas**, con revisión técnica local, pero binarios quedaron fuera de GitHub. Los archivos de control no prueban publicación del contenido exacto.
- **Desalineación conocida:** PM2-02 archivada describe **17 diapositivas** mientras la F2 corregida es de **25**; una descripción de Moodle que todavía diga 17 sería inconsistente. Debe cotejarse la descripción efectiva, corregirse si procede y reconciliarse con GitHub.
- Derechos/alt texts: enlaces de fuentes institucionales no significan derechos para republicar fotografías; validar alt text y procedencia de cada recurso realmente utilizado.

**Dictamen:** CUMPLE EN INTENCIÓN DOCUMENTAL; CONTROL DE VERSIÓN, REPRESENTACIÓN Y ACCESIBILIDAD ABIERTOS.

## 7. Espiral, evaluación, andamiaje y PROEMA
FD5 integra H9 («DISEÑAR NUEVOS COMPORTAMIENTOS MATERIALES») y H10 («DIAGNOSTICAR/DECIDIR/CONSERVAR»), **DECIDIR/SINTETIZAR**, con andamiaje MÍNIMO SELECTIVO. Producto: **Cierre reflexivo del Portafolio de Casos**. La Tabla de Alineación v2.0 fija **3 puntos de FD5**; el reparto candidato 1+1+1, las bandas 180–250/60–100 palabras, el tipo de foro y calendarios operativos **no fueron decisiones canónicas**, por lo que se deben cotejar con el Moodle realmente montado. PM4-03 es voluntaria, sin puntos ni condición de finalización; verificar que no se convierta inadvertidamente en obligación técnica.

PROEMA mantiene sus propios productos, calendario y evaluación. Cierre PM6 no exige actividad adicional. **Dictamen:** DISEÑO CUMPLE, configuración EVALUATIVA PENDIENTE.

## 8. Carga y DUA
OVAt-H10 propuso **66–84 min F1–F6**, rango operativo **70–85 min sin FD5**. La evaluación del Gate FD5 estimó **20–30 min adicionales** para foro y **8–12 min** para opcional (si elegida), **no medidos**. No presentar 94–127 min como carga real comprobada; son rangos posibles de planificación y pueden solaparse según integración de F5. Coincide en semana 12 con otras entregas de Tabla V2.0 (EI.5 y DR.3).

Pendiente QA situado: lectura móvil; navegación y jerarquía de encabezados; contraste; alt texts efectivos; PDF y enlaces; permisos estudiantiles; ajustes de grupos, respuesta y calificación; visibilidad y fechas; prueba de descarga/edición de MDS; carga real con alumnado o ensayo docente.

## 9. Incidencias clasificadas
### CRÍTICAS: **0 documentadas**
No se detectó en el texto examinado una contradicción sustantiva que exija detener de inmediato el acceso. **No equivale a certificación técnica de 0 fallos en Moodle.**

### MAYORES: **3 de aseguramiento/cierre (no necesariamente defectos del contenido)**
- **H10-AI-01 · QA Moodle NO CERTIFICADO.** Hay montaje reportado de PM2, PM3, FD5/opcional, PM6; falta recorrido final verificable F1–F6, F5 y evaluación real FD5; PM1 montaje no constatado documentalmente aquí. **BLOQUEA declarar H10 «PRODUCIDA, MONTADA Y VERIFICADA» o APROBADA COMO SISTEMA.**
- **H10-AI-02 · Versiones finales no reconciliadas y metadatos F2 inconsistentes.** F2 25 láminas vs descripción PM2-02 de 17; F2/F3/PM3 binarios de sesión sin archivo canónico y sin huellas confirmadas del fichero Moodle. **BLOQUEA trazabilidad final y aprobación integral hasta cotejo y plan de corrección, aunque puede resolverse sin rehacer enseñanza.**
- **H10-AI-03 · Gate de FD5 condicionado frente a montaje posterior, y configuración evaluativa/opcional no verificada.** El Gate autorizó diseño candidato y revisión previa al montaje; el docente reportó montaje de FD5 y PM4-03, pero no hay constancia separada de esa revisión ni QA de puntos/voluntariedad/finalización. **BLOQUEA cierre de cumplimiento evaluativo hasta reconciliación; no presume infracción consumada en Moodle.**

### MENORES / LOCALES: **4 grupos**
- **H10-AI-04:** Ajuste F5 no bloqueante aprobado, no probado en Word/PDF montado; mejorar monitoreo/comparación de alternativas sin crear PM5-02.
- **H10-AI-05:** Alt text y legibilidad móvil de gráficos IA/diagramas aún no cotejados; asegurar avisos de no evidencia y pies de imagen.
- **H10-AI-06:** PM4-02/PM4-04 no documentadas como descripciones autónomas; determinar si la información está integrada en foro/tarea y registrar «NO REQUERIDA» o producir solo si se comprueba necesidad, sin reescribir por inercia.
- **H10-AI-07:** Carga 70–85 min sin FD5, 20–30 min FD5 y 8–12 min opcional son estimaciones sin medición real; registrar prueba proporcional y DUA.

## 10. Matriz de reparación y evidencia esperada
| Prioridad | Acción y responsable | Evidencia para cerrar |
|---|---|---|
| **P0** | Docente: recorrido de Moodle como estudiante por PM1/PM2/PM3/F5 integrada/PM4/PM6, con título, estado y visibilidad | Checklist con captura o confirmación escrita de QA, enlaces y acceso |
| **P0** | Docente: validar FD5 3 pts, participación entre pares, plazos y opcional sin calificación ni finalización obligatoria; identificar si cumplió revisión editorial del Gate | Registro de configuración/decisión, con ajustes si necesarios |
| **P1** | Producción: comparar PPTX 25 y DOCX 10, PDF/MDS/PNG montados con hashes de control; alinear descripción F2 17→25 si aún aplica | Manifiesto de versiones/binaries y descripción actualizada, commit `main` |
| **P1** | Producción: auditar imagen v0.2, alt text, recursos Rijksmuseum, permisos y referencias | Inventario de procedencia/derechos y QA de accesibilidad |
| **P2** | Docente/producción: ajustar F5 en página 5 si conveniente, sin segundo objeto Moodle | Versión DOCX/PDF reconciliada o justificación de no modificación |
| **P2** | Docente: comprobar carga real y experiencia de estudiante | Medición proporcional y observación |

**Criterio de avance:** resolver o documentar suficientemente P0 antes de proponer **GO** en Gate Integral; corregir o aceptar expresamente P1 según riesgo; P2 puede quedar como condición no bloqueante. Sin evidencia P0, el dictamen debe permanecer **PENDIENTE DE QA**, no equipararse al GO de H8.

## 11. Metaevaluación del piloto PM v0.3
**Aprendizajes concretos:**
1. F2 17 y F3 6 fueron demasiado superficiales; corrección a F2 25 y F3 10 demuestra necesidad de **Gate de suficiencia editorial/visual**, no simple economía de páginas.
2. PM3-05 v0.1 fue percibida como demasiado sencilla; recuperación del formato H9 exigió v0.2 y un aviso explícito de representación IA.
3. PM3-06 inicialmente cambió el formato de descripción, corregido a párrafo único v0.2 por ejemplo docente. Necesidad de preservar subpatrones editoriales exactos.
4. PM5-01 mostró que integración puede ser legítima sin página separada, **si hay evidencia de ubicación exacta**.
5. PM4 dejó claro que la autorización de diseñar no implica automáticamente autorización de montar y que la distinción F/PM es obligatoria.
6. Registro canónico fuerte en Markdown, pero archivos de sesión no siempre archivados. Un manifiesto de artefactos y QA por pieza disminuiría esa brecha.

**Interpretación:** experiencia útil para evaluar una eventual versión futura, pero **NO valida ni modifica v0.3, D-027 ni D-056**. Cualquier decisión metodológica posterior exige Gate humano separado.

## 12. Dictamen de la Auditoría Inversa
**CUMPLIMIENTO CURRICULAR Y PEDAGÓGICO DOCUMENTAL: FAVORABLE.** Se observa coherencia FEHE → OVAt → F1–F6 + FD5, movimiento rector, MDS compacta, transferencia integrada y síntesis final sin H11.

**CUMPLIMIENTO DE DESPLIEGUE Y TRAZABILIDAD: NO CERTIFICADO.** Hay 3 hallazgos MAYORES de aseguramiento antes del Gate Integral. Por tanto la recomendación es:

> **GATE INTEGRAL H10: PREPARAR, SIN PROPONER TODAVÍA GO DE CIERRE.**  
> **Estado recomendado:** «AUDITORÍA INVERSA H10 COMPLETADA DOCUMENTALMENTE, CONDICIONADA A QA SITUADO Y RECONCILIACIÓN».  
> Tras evidencias P0 y plan documentado P1, someter al docente opciones GO / GO CON CONDICIONES / NO GO.

No declarar H10 APROBADA COMO SISTEMA ni Carril B CERRADO. No inventar decisión D-XXX.

## 13. Fuentes canónicas de referencia
- `00_CONTROL_MAESTRO/ESTADO_MAESTRO.md`
- `00_CONTROL_MAESTRO/MAPA_RUTA_MAESTRO_F0-F10.md`
- `18_DOCUMENTACION_ACTIVA/BITACORA_DECISIONES.md`
- `18_DOCUMENTACION_ACTIVA/GATE_REALIZACION_H10.md`
- `18_DOCUMENTACION_ACTIVA/DECISION_PM5-01_H10_F5_INTEGRADA_GO_2026-11-01.md`
- `18_DOCUMENTACION_ACTIVA/GATE_FD5_H9-H10_DECISION_HUMANA_2026-11-01.md`
- `19_IMPLEMENTACION_Y_DESPLIEGUE/OVAT_Y_MOODLE/H10/CIFI4074_OVAt_H10_Especificacion_v0.1_APROBADA_CON_CONDICIONES.md`
- `19_IMPLEMENTACION_Y_DESPLIEGUE/OVAT_Y_MOODLE/H10/CIFI4074_F2_F3_RECONSTRUCCION_EDITORIAL_v0.1_CANDIDATA_CONTROL.md`
- `19_IMPLEMENTACION_Y_DESPLIEGUE/OVAT_Y_MOODLE/H10/CIFI4074_OVAt_H10_PM3-03_Guia_Autoestudio_v0.1_CANDIDATA_CONTROL.md`
- `19_IMPLEMENTACION_Y_DESPLIEGUE/OVAT_Y_MOODLE/H10/CIFI4074_OVAt_H10_PM3-05_Ilustracion_Problematizadora_v0.2_ILUSTRADA_CANDIDATA_CONTROL.md`
- `19_IMPLEMENTACION_Y_DESPLIEGUE/OVAT_Y_MOODLE/H10/CIFI4074_H10_PM6-01_Cierre_v0.1_CANDIDATO.md`
- `19_IMPLEMENTACION_Y_DESPLIEGUE/OVAT_Y_MOODLE/H10/CIFI4074_H10_PM6-02_Descripcion_Cierre_v0.1_CANDIDATA.md`
- `18_DOCUMENTACION_ACTIVA/AUDITORIA_INVERSA_H8_v1.0.md` como contraste de umbral de verificación y cadena, sin inferir resultados idénticos.
**Fin. Estado:** AUDITORÍA DOCUMENTAL CANDIDATA COMPLETADA, REVISIÓN HUMANA Y QA SITUADO PENDIENTES.
