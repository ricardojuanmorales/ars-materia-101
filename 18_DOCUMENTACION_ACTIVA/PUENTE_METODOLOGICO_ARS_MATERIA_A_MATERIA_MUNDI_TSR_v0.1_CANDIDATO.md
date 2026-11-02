# Puente metodológico · Ars Materia → Materia Mundi · Kit TSR/Laboratorio integrado/REC
**Fecha:** 2026-11-02 · **Estado:** DISEÑO PRELIMINAR CANDIDATO; NO AUTORIZACIÓN DE PRODUCCIÓN MATERIA MUNDI.
**Procedencia verificada:** Ars Materia, kit piloto `03_METODOLOGIA_Y_FLUJO_DE_TRABAJO/PROTOCOLOS/PILOTO_MONTAJE_OVAT_H_v0.3/`, 27 archivos publicados en `main` (21 prompts).
**Límite de verificación:** no se ha localizado un repositorio o corpus documental canónico accesible de Materia Mundi en conexiones consultadas; ninguna caracterización formal de TSR, Laboratorio integrado o REC queda confirmada por fuentes primarias de ese proyecto. Sus nombres son aportados por el docente y se consideran **entradas de trabajo, no definiciones inferidas**.

## 1. Problema y meta
El piloto H10 mostró que es posible preparar piezas bajo contrato autosostenido con fuente canónica, control de autoridad, parámetros editoriales, trazabilidad, QA y validación humana, pero también mostró fallos de autosuficiencia visual en F2/F3 y PM3-05, cambios no deseados de formato de descripciones y binarios sin archivo canónico. Materia Mundi requiere construir un kit transferible **por TSR**, preservando **Laboratorio integrado** y **REC** como subsistemas propios, sin extrapolar FD, PROEMA o MDS-H10 por parecido nominal.

**Pregunta de transferencia:** ¿Puede un kit por TSR recuperar patrones editoriales y decisiones de la fuente de verdad sin exigir subida reiterada de ejemplos, sostener calidad de mediación y laboratorio/REC, reducir retrabajo y preservar gates?

## 2. Principios preservados del piloto
1. Separar **función curricular** de **paquete operativo**; no imponer F1–F6 literalmente a Materia Mundi.
2. Fuente de verdad del proyecto destino, decisiones humanas, versiones y gates por encima de prompts.
3. Protocolo de Preproducción proporcional, corpus y licencias, mapa de requisitos de evidencia antes de montaje.
4. Cada prompt autosostenido: referencia de modelo editorial con **ruta verificable** y criterios del diseño, no frase «igual que la vez pasada».
5. Producción pieza por pieza, candidato → revisión → montaje reportado → QA situado → Gate integral; no confundir estados.
6. Un producto central reutilizable por TSR **solo si** lo dispone la autoridad de Materia Mundi; decidir integración vs objeto autónomo, sin entregas duplicadas.
7. Lab: seguridad, equipo, preparación, residuos, accesibilidad y evidencias dependen de especificación aprobada; **nunca inventar protocolos ni materiales peligrosos**.
8. REC: conservar sigla sin expandir; requerir definición y función canónica antes de redacción de módulos específicos.
9. Archivo de binarios con SHA-256, licencia, alt text y correspondencia Moodle para evitar deudas H10.
10. Congelar kit piloto en prueba; cambios propuestos en bitácora, versión siguiente solo tras Gate.

## 3. Arquitectura propuesta, NO validada
### Capa A: núcleo transversal de producción asistida
- `T00` Activación, reconstrucción de autoridad y matriz de funciones.
- `T01` Preproducción TSR: fuentes históricas/materiales, experimentalidad, seguridad, imágenes y DUA.
- `T02` Gate de suficiencia editorial y científica antes de producción.
- `T03` Ficha autosostenida de pieza: objetivo, fuentes, ejemplo canónico, parámetros de profundidad/visualidad, formatos, citación y QA.
- `T04` Revisión editorial, registro de versiones, montaje, verificación y huellas.
- `T05` Auditoría inversa y Gate Integral TSR con lecciones de transferencia.

### Capa B: módulos TSR (nombres provisionales hasta cotejo)
- `TSR-P01` Apertura/activación conceptual si existe en arquitectura TSR.
- `TSR-P02` Presentación FEHE o marco histórico-epistemológico, si corresponde.
- `TSR-P03` Lectura/recursos de profundización, según formato aprobado.
- `TSR-P04` Actividad nuclear, caso/criterio reusable y guía; determinar integración con Lab y REC antes de separar recursos.
- `TSR-LAB` **Laboratorio integrado**: planificación, evidencias, seguridad, accesibilidad, protocolo de registro e interpretación, de acuerdo con autoridad propia; no inventar procedimientos.
- `TSR-REC` **REC**: nomenclatura y función a establecer al leer el documento rector; no asumir foro, evaluación, ensayo o rúbrica.
- `TSR-P05` Transferencia / integración / continuidad, si está prevista.
- `TSR-P06` Cierre y síntesis TSR, si está previsto.
- Cada pieza puede ser **OBLIGATORIA, CONDICIONAL AUTORIZADA, INTEGRADA EN [recurso], OMITIDA POR AUTORIDAD o RESERVADA**. Los módulos no equivalen automáticamente a funciones canónicas del curso.

### Capa C: biblioteca editorial que sustituye ejemplos subidos
- Archivo de referencia por **tipo** (presentación ilustrada, lectura, guía, laboratorio, REC, Moodle, cierre), con su ruta canónica y versión humana aprobada.
- Cada modelo debe indicar **qué transferir** (estructura, densidad, navegación, rigor, estilos, extensión aceptada) y **qué NO copiar** (tema, caso, resultados, extensión arbitraria).
- Índice de figuras originales, derechos y texto alternativo, diagramas con trazabilidad de fuente.
- Manifiesto SHA-256 y mapas `modelo → prompt → resultado candidato → versión aprobada → archivo LMS`.
- Si el modelo no está accesible o carece de aprobación: **BLOQUEO EDITORIAL**, no pedir al docente re-subirlo por defecto hasta haber buscado repositorio/archivo.

## 4. Contrato maestro candidato de un prompt TSR
```text
ROL: Diseñador instruccional y auditor de Materia Mundi según fuentes aprobadas.
FUENTE: descubrir y leer ESTADO MAESTRO, DECISIONES, FEHE/TSR, LAB, REC,
        matriz evaluativa, modelos editoriales, protocolos/puertas en repo destino.
NO INVENTAR: expansión de REC; orden de TSR; componente obligatorio;
            experimentos, datos, requisitos, número de páginas, carga o puntos.
ACTIVACION: registrar Gate humano habilitante y clasificación por pieza.
ENTRADA: TSR y elemento, versión, evidencia, riesgos, modelo de diseño y derechos.
PRODUCCION: una pieza por turno; primero contrato editorial, luego candidata.
VALIDACION: fuentes/citas, diferenciación evidencia-modelo, seguridad Lab,
            DUA, carga, coherencia TSR+Lab+REC, revisión de visuales, QA.
SALIDA: archivo editable + render si procede; ficha QA; metadatos y SHA;
        ruta real; estado CANDIDATO; siguiente Gate, sin montaje supuesto.
PARADA: revisión humana antes de la pieza siguiente.
```

## 5. Prueba de transferencia controlada
- Elegir **una TSR piloto**, no las demás; verificar que su FEHE, laboratorio y REC estén definidos, con docentes/criterios aprobados y un conjunto de modelos editoriales publicados.
- Reconstruir autoría/rutas en repositorio Materia Mundi, comparar con ejemplares reales y **congelar kit v0.1 piloto**.
- Basal H10: retrabajo F2/F3 de 17/6 a 25/10, PM3-05 v0.1→v0.2 y PM3-06 v0.1→v0.2; medir de forma proporcional retrabajo, suficiencia, QA y solicitudes de ejemplos.
- Prueba: una pieza de marco, una de laboratorio integrado y una de REC, más su montaje/QA si autorizados.
- Éxito: no subir ejemplos, al menos un recurso de cada subsistema pasa revisión humana con trazabilidad, ninguna invención científica/evaluativa, y las piezas se recuperan del repositorio por ruta.

## 6. Bloqueos reales antes de canonizar / implementar en Materia Mundi
1. **Ubicación inequívoca del repositorio canónico Materia Mundi**, rama y permisos.
2. Documento rector, FEHE/TSR aprobada, mapa/carga por TSR; **definición canónica de Laboratorio integrado y REC**.
3. Matriz de tareas/evaluación y Gates, bibliografía y seguridad del laboratorio.
4. Modelos finales aprobados archivados (MD y binarios) con su formato real Moodle.
5. Resolución separada del Gate metodológico H10 y autorización para piloto de transferencia. No colocar archivos de Materia Mundi en ruta arbitraria de Ars Materia.

**Recomendación:** aprobar solo la **fase de reconstrucción/ficha editorial del destino**, nunca producción de piezas de TSR sin documentación. El kit H10 v0.3 permanece congelado.
