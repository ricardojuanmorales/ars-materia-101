# Registro de Refactorización Canónica Express v1.0

**Proyecto:** Ars Materia 101  
**Fecha:** 2026-09-07  
**Estado:** EJECUTADA EN RAMA DE REFACTORIZACIÓN  
**Rama:** `refactor/framework-canonical-routes`  
**Motivo:** corregir deuda técnica/documental antes de continuar FEHE-H1.

## 1. Contradicción detectada

El proyecto declaraba Framework Genérico V4.1.0 activo, pero la raíz del repositorio utilizaba una taxonomía ad hoc basada en tipos de producto (`DOCUMENTO_RECTOR`, `FEHE_H1-H10`, `PROTOCOLOS`, etc.). Esa estructura era útil localmente, pero no preservaba de forma estable la ontología funcional del Framework.

Riesgo: crecimiento acelerado de rutas paralelas, duplicación semántica, enlaces frágiles y mayor carga cognitiva a medida que FEHE, PROEMA, OVAt, Moodle, DUA, evaluación, IA y auditoría crecieran.

## 2. Decisión humana

Adoptar la estructura raíz completa del Framework V4.1.0, usando Materia Mundi como referencia de implementación avanzada y no como plantilla curricular.

Principio aprobado:

> estructura completa + activación según necesidad + mínima ceremonia útil.

La trazabilidad de procesos y metodologías se declara tan importante como la producción de materiales educativos.

## 3. Alcance ejecutado

Se mantuvo `00_CONTROL_MAESTRO/` y se normalizaron las raíces `01`–`21` + `99_ARCHIVO_HISTORICO` según Framework V4.1.0.

### Migraciones principales

| Ruta anterior | Ruta canónica nueva |
|---|---|
| `01_FUNDAMENTOS/` | `02_ARQUITECTURA_CONCEPTUAL/FUNDAMENTOS_FEHE/` |
| `02_DOCUMENTO_RECTOR/` | `02_ARQUITECTURA_CONCEPTUAL/DOCUMENTO_RECTOR/` |
| `03_FEHE_H1-H10/` | `08_CURSOS_PROGRAMAS_Y_TRAYECTORIAS/FEHE_H1-H10/` |
| `04_ALINEACION_Y_EVALUACION/` | `08_CURSOS_PROGRAMAS_Y_TRAYECTORIAS/ALINEACION_Y_EVALUACION/` |
| `05_PROEMA/` | `13_INVESTIGACION_Y_EVIDENCIA/PROEMA/` |
| `06_OVAT_Y_MOODLE/` | `19_IMPLEMENTACION_Y_DESPLIEGUE/OVAT_Y_MOODLE/` |
| `07_PROTOCOLOS/` | `03_METODOLOGIA_Y_FLUJO_DE_TRABAJO/PROTOCOLOS/` |
| `08_FUENTES_Y_REFERENCIAS/FUENTES_DE_APOYO/` | `13_INVESTIGACION_Y_EVIDENCIA/FUENTES_DE_APOYO/` |
| `08_FUENTES_Y_REFERENCIAS/INVENTARIO_FUENTES.md` | `13_INVESTIGACION_Y_EVIDENCIA/INVENTARIO_FUENTES.md` |
| `08_FUENTES_Y_REFERENCIAS/Prontuario...md` | `08_CURSOS_PROGRAMAS_Y_TRAYECTORIAS/FUENTES_INSTITUCIONALES/` |
| `10_BITACORA_Y_DECISIONES/` | `18_DOCUMENTACION_ACTIVA/` |
| `99_ARCHIVO/` | `99_ARCHIVO_HISTORICO/` |

## 4. Qué no cambió

- No se modificó contenido sustantivo de FEHE, Documento Rector, PROEMA, prontuario, Tabla V2.0 ni protocolo operativo por motivo de esta migración.
- No se promovieron estados documentales.
- No se abrió H2-H10.
- No se rediseñó la ponderación 60/40.
- No se convirtió Materia Mundi en plantilla curricular de Ars Materia.

## 5. Instrumentos de reducción de carga cognitiva

La interfaz humana queda concentrada en:

1. `00_CONTROL_MAESTRO/ESTADO_MAESTRO.md`
2. `00_CONTROL_MAESTRO/MAPA_RUTA_MAESTRO_F0-F10.md`
3. `00_CONTROL_MAESTRO/MAPA_REPOSITORIO.md`

Las demás rutas se consultan sólo según la función activa.

## 6. Aprendizaje metodológico transferible

La estructura completa del Framework no implica implementación máxima. Su valor es estabilizar la ontología documental para que los proyectos puedan crecer sin inventar nuevas categorías raíz cada vez que surge un artefacto.

Patrón transferible:

```text
Framework completo en raíz
→ funciones activadas proporcionalmente
→ productos ubicados por función
→ Estado/Mapa como interfaz humana
→ Git como genealogía
```

Este aprendizaje queda candidato para futura incorporación al Protocolo de Virtualización Lúdica Transdisciplinaria cuando exista Gate específico para actualizarlo.

## 7. Frontera de continuidad

Al cerrar y verificar esta refactorización, el próximo trabajo sustantivo sigue siendo:

**FEHE-H1 profunda CANDIDATA → Gate humano → propagación H2-H10 sólo si H1 es aprobada.**
