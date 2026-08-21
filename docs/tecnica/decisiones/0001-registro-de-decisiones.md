# 0001 - Registro de decisiones de arquitectura

- **Estado:** aceptada
- **Fecha:** 2026-08-21

## Contexto

Necesitamos un lugar consistente para registrar decisiones técnicas importantes, su contexto y las alternativas consideradas, para que el equipo (y una IA colaborando en el proyecto) pueda entender el "por qué" detrás de la arquitectura sin depender de memoria oral.

## Decisión

Usaremos el formato ADR (Architecture Decision Record) en `docs/tecnica/decisiones/`, un archivo por decisión, numerados secuencialmente.

## Consecuencias

- Cada cambio de arquitectura relevante debe venir acompañado de un ADR.
- Los ADR no se editan retroactivamente para cambiar la decisión; si una decisión cambia, se crea un ADR nuevo que referencia al anterior.
