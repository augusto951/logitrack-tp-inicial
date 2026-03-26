# ADR 001 – Arquitectura en capas

## Contexto
El sistema LogiTrack se diseña como un MVP que debe ser simple de mantener,
extensible y coherente con el trabajo incremental del equipo.
Es necesario separar responsabilidades para facilitar la evolución del sistema.

## Decisión
Se adopta una arquitectura en capas en el backend, separando:
- Controladores (exposición de endpoints)
- Servicios (lógica de negocio)
- Repositorios (acceso a datos)

## Consecuencias
- Mejora la mantenibilidad y organización del código
- Facilita pruebas y cambios futuros
- Introduce una estructura clara desde etapas tempranas del MVP
