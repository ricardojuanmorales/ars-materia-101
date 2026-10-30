# CONTROL DE ARCHIVO · PILOTO MONTAJE OVAt-H v0.3
**Fecha:** 2026-10-30  
**Decisión:** D-058 · GO PARA PILOTO EXPERIMENTAL CON CONDICIONES DE TRAZABILIDAD  
**Estado de integridad:** VERIFICADO LOCALMENTE  
**Estado de archivo:** PENDIENTE DE PUBLICACIÓN ÍNTEGRA EN GITHUB

## Ruta propuesta
`03_METODOLOGIA_Y_FLUJO_DE_TRABAJO/PROTOCOLOS/PILOTO_MONTAJE_OVAT_H_v0.3/`

El paquete contiene 21 archivos `prompts/PM*-*.md`, un índice, protocolo, prompt de activación H10, manifiesto SHA-256 y dos anexos. Es un protocolo **complementario de producción/montaje**, sin modificación de Patrón OVAt-H v1.0 ni Protocolo de Preproducción v1.0.

## Evidencia local A1
- ZIP: `CIFI4074_PAQUETE_PROMPTS_MONTAJE_OVAT_H_v0.3_CANDIDATO.zip`
- SHA-256: `49a24d30d6fbf8a05c2c0b7d2f438eddd8f362c3a03b1f51818c11dab952f2b8`
- 27 entradas, 21 prompts y 6 documentos complementarios.
- 26/26 archivos declarados en manifiesto validaron tamaño y SHA-256.
- `testzip`: sin error.
- La comprobación de contenido canónico requiere comparar cada blob GitHub con los hashes del manifiesto.

## Control de transición
No marcar ARCHIVADO/VERIFICADO EN MAIN hasta completar 27/27. No iniciar Gate 0 H10 suponiendo disponible un catálogo que no esté publicado íntegramente.


## Control A2 · 2026-10-30 · verificación reproducida

- ZIP original inspeccionado nuevamente: 27 archivos; 21 prompts.
- CRC del ZIP: sin incidencias.
- Manifiesto: 26/26 archivos listados concordantes en tamaño y SHA-256; el manifiesto (entrada 27) presente y legible.
- **Bloqueo de publicación:** el conector de escritura GitHub no puede consumir directamente archivos del sistema de archivos local de esta sesión. No se sustituyen archivos originales por reconstrucciones ni se marca completada la publicación.
- **Estado vinculante:** A1 completo; A2 registro canónico de autorización completo; A2 **archivo íntegro 27/27 PENDIENTE**.
- **Acción de cierre:** publicar 27 originales y verificar el SHA-256 de cada blob recuperado de `main` antes del Gate 0 H10.


## Cierre A2 · 2026-10-30 · PUBLICADO Y VERIFICADO

**Estado vigente de archivo: A2 CERRADO · 27/27 PUBLICADOS Y VERIFICADOS EN `main`.** Esta sección sustituye los estados históricos «pendiente» anteriores, conservados como trazabilidad del proceso.

**Evidencia de ejecución aportada por el docente:** script `publicar_y_verificar_v03_reanudable.py` ejecutado con autenticación `gh`, salida terminal `FINAL: 27/27 publicados y verificados byte a byte en main`. 25 archivos existentes se clasificaron `IGUAL`; los dos archivos PM6 fueron publicados y verificados. La ejecución inicial del script original se detuvo tras el archivo 24 por respuesta vacía, sin alterar la línea base; la reanudación preservó íntegramente lo ya publicado.

**Comprobación adicional del conector GitHub:** manifiesto SHA-256 y ambos archivos PM6 recuperados de `main`. La confirmación byte a byte del conjunto completo proviene de la post-auditoría del script ejecutado localmente, no de una segunda auditoría completa independiente por el conector.

**Resultado:** carpeta publicada en `03_METODOLOGIA_Y_FLUJO_DE_TRABAJO/PROTOCOLOS/PILOTO_MONTAJE_OVAT_H_v0.3/`. Se conserva estado documental **v0.3 CANDIDATO · APROBADO PARA PILOTO EXPERIMENTAL CON CONDICIONES DE TRAZABILIDAD (D-058)**, sin alterar texto ni hashes de los 27 archivos congelados. Protocolo aún NO VALIDADO por transferencia H10.

**Siguiente control:** Gate 0 H10; no abrir producción H10 sin sus Gates curriculares ordinarios. No se crea nueva D-XXX por esta operación técnica.
