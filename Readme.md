# AURVO OS — Gaming Performance Edition

Repositoro de referencia: distribución mínima optimizada para gaming. Incluye scripts de compilación, configuración de kernel 'gaming' y rootfs base.

## Estructura
- kernel/: config del kernel optimizado
- rootfs/: archivos mínimos del sistema de archivos
- scripts/: build / install / crear ISO
- docs/: documentación mínima

## Requisitos para construir
- Host Linux (Arch recommended)
- `git`, `archiso` (si usas Arch), `gcc`, `make`

## Instrucciones rápidas
1. Clona repo
2. Revisa `scripts/build.sh`
3. Ejecuta `chmod +x scripts/*.sh` y `./scripts/build.sh` en un host compatible

## Disclaimer
Proyecto en fase experimental. No usar en máquinas de producción sin pruebas.
