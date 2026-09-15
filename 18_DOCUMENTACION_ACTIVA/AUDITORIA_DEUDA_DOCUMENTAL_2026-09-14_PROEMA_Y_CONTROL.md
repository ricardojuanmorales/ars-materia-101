# AUDITORÍA DE DEUDA DOCUMENTAL — Ars Materia 101
## PROEMA, control maestro y continuidad

**Fecha:** 2026-09-14  
**Estado:** VIGENTE COMO REGISTRO DE PAGO DE DEUDA DOCUMENTAL  
**Fuente de verdad:** GitHub `main`

## 1. Propósito

Registrar la pausa deliberada de producción realizada para reconciliar el estado real del proyecto con su documentación canónica y evitar que la velocidad de implementación produzca deriva documental.

## 2. Hallazgos antes del pago

1. `README.md` permanecía congelado en la etapa FEHE-H1 y declaraba como próximo Gate desarrollar y validar H1, aunque H1 ya estaba aprobado como modelo operativo y H2 había sido montado y verificado.
2. `BITACORA_DECISIONES.md` estaba correctamente actualizada hasta D-025.
3. La reflexión PROEMA producida en sesión no estaba todavía incorporada a GitHub.
4. La Guía del Estudiante · Ruta PROEMA v0.1 existía como artefacto local, pero no como documento Markdown versionado.
5. El prompt de continuidad PROEMA existía localmente, sin incorporación a control maestro.
6. La arquitectura interna definitiva de PROEMA seguía abierta y no debía resolverse mediante una taxonomía improvisada.
7. No existe evidencia desde este entorno de que una copia local externa del repositorio en la computadora del usuario esté sincronizada con `main`.

## 3. Decisión humana registrada

Se formaliza como **D-026** la decisión provisional de:

> concentrar todo material sustantivo PROEMA bajo `13_INVESTIGACION_Y_EVIDENCIA/PROEMA/` mientras se completa una reflexión estratégica sobre arquitectura documental, rutas canónicas y nombres semánticos.

La decisión NO aprueba una nueva taxonomía interna, NO convierte U13/U14 en carpetas y NO convierte automáticamente E1-E5 en estructura de repositorio.

## 4. Acciones ejecutadas

- actualizar `README.md` al estado real H1-H2;
- registrar D-026 en `18_DOCUMENTACION_ACTIVA/BITACORA_DECISIONES.md`;
- incorporar cierre de reflexión PROEMA en `18_DOCUMENTACION_ACTIVA/`;
- incorporar prompt de activación/continuidad PROEMA en `00_CONTROL_MAESTRO/`;
- incorporar Guía del Estudiante · Ruta PROEMA v0.1 como **CANDIDATO** en `13_INVESTIGACION_Y_EVIDENCIA/PROEMA/`;
- preservar PROEMA 1 en su ruta actual;
- no crear subcarpetas nuevas dentro de PROEMA;
- no alterar el próximo Gate curricular real: Auditoría Inversa H2 → Gate Integral H2 → decisión sobre Patrón OVAt-H.

## 5. Deuda que permanece abierta

- completar auditoría inversa final H2;
- cerrar Gate Integral H2;
- decidir VALIDADO / VALIDADO CON AJUSTES / NO VALIDADO para Patrón OVAt-H;
- revisar arquitectura documental PROEMA desde documentos canónicos antes de crear nuevas rutas;
- decidir integración exacta de U13 Investigación PROEMA y U14 Producción PROEMA;
- sincronizar nombres físicos/metadatos heredados H1/H2 señalados en Estado Maestro;
- verificar incorporación/repositorio de artefactos finales actualmente en Moodle/local;
- verificar manualmente que la copia local externa del repositorio, si existe, esté sincronizada con GitHub `main`.

## 6. Criterio de cierre de esta deuda

La deuda documental inmediata se considera pagada cuando:

- README, bitácora y cierres expresan el estado real;
- los nuevos materiales PROEMA tienen una ubicación versionada y un estado explícito;
- no existe una nueva taxonomía interna no aprobada;
- la próxima sesión puede reconstruir el punto exacto de reflexión desde GitHub sin depender de memoria conversacional.
