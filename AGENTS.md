# Instrucciones para agentes de IA en ia_nest_web

Las reglas transversales del ente (texto ASCII, identificadores en ingles
snake_case, citas `<repo> ADR NNNN`, repo publico, modo ciego, regla del
registro) viven en `ia_nest_meta` y no se repiten aqui. Lee antes:

1. `meta docs/CONVENCIONES_TRANSVERSALES.md` y `meta docs/DOCTRINA_MULTI_IA.md`
2. `meta docs/REGISTRO_CAPAS.md` y `meta docs/ARQUITECTURA_DE_CAPAS.md`
3. `core ADR 0033` (la web es la cara del ente) y `core docs/FRONTERAS.md`
   (su costura)
4. `meta ADR 0011` y `0013` (el borde va delante; Open WebUI mientras tanto)
5. `README.md` de este repo

## Reglas propias de este repo

- **La web presenta; no piensa por las capas.** Muestra lo que exponen sus
  contratos publicos; no reimplementa logica de core, extended, conscience ni
  pulse.
- **Cliente del contrato, no de las capas** (meta ADR 0007, regla 4): apunta al
  borde y no tiene ramas por capa.
- **No autentica por su cuenta.** La identidad la afirma el borde.
- **Charter de nacimiento:** no se escribe codigo hasta que haga falta algo que
  Open WebUI no sepa mostrar (`core ADR 0035`).
- Mientras el repo sea semilla, todo documento nuevo nace `Estado: propuesta`.
