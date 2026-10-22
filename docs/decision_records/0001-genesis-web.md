# Decision 0001: genesis de la web

Fecha: 2026-10-22

## Decision

Se siembra `ia_nest_web` como semilla documental, sin codigo ni contrato
publico, con su alcance declarado: toda la interfaz del ente, de usuario y de
administracion (`core ADR 0033`).

## Motivo

El usuario crea el repo junto al borde y la capa agentica, para que el ente
tenga ya su sitio para la cara aunque hoy la cubra Open WebUI (meta ADR 0013).

## Consecuencia

- La fila de la capa en `meta docs/REGISTRO_CAPAS.md` pasa a semilla.
- `core docs/FRONTERAS.md` no tiene doctrina de esta capa que mudar: solo su
  costura, que se queda alli. No se toca el core.
- No se escribe codigo hasta que haga falta mostrar algo que Open WebUI no sepa.
- Sin SemVer ni tag hasta que exista contrato publico.

## Impacto de version

Ninguno: no hay contrato publico.
