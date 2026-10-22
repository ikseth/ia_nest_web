# ia_nest_web

La cara del ente IA_NEST: toda su interfaz, de usuario y de administracion.

Estado: semilla
Version: 0.1 - 2026-10-22

## Que es

Zona **Ente** del registro: es la pieza que PRESENTA (`core ADR 0033`, "GUI de
gestion y de usuario"). Empieza siendo un webchat y acaba reuniendo todo el
frontal del ente: conversacion, cuentas de usuario, administracion de las capas
(incluida la del borde) y el estado de conscience y pulse.

Se le habla a traves de `ia_nest_edge`, como a cualquier otra superficie
(meta ADR 0011). La web no autentica por su cuenta ni guarda la identidad.

## Estado

Semilla documental, sin codigo. Mientras no haga falta mostrar algo que una
interfaz de terceros no sepa, el webchat lo cubre **Open WebUI** tras el borde
(meta ADR 0013).

Frontera falsable con el borde: el dia que esta web sustituya a Open WebUI, no se
edita ningun fichero de `ia_nest_edge`.

Base previa, a releer antes de adoptarla: los documentos `FRONTEND_V2_*`,
`FRONTEND_V3_*` y `UX_*` del repo `ia_nest` antiguo
(`docs/desarrollo/arquitectura/`). Son anteriores al ente por capas.

## Orden de lectura

Ver `AGENTS.md`.
