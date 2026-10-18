# crileiton-mods

Marketplace personal de plugins para Claude Code.

## Instalar

```bash
claude plugin marketplace add crileiton/crileiton-mods
claude plugin install cache-keeper@crileiton-mods
claude plugin install recording-mode@crileiton-mods
claude plugin install goal-meter@crileiton-mods
claude plugin install collision-guard@crileiton-mods
```

## Plugins

- **cache-keeper** — mantiene caliente el caché de chats grandes, `/board`, `/keepwarm`, `/handoff`.
- **recording-mode** — `/rec`: oculta claves, datos personales y cifras en pantalla al grabar.
- **goal-meter** — barra de progreso para `/goal`, y `/goals`.
- **collision-guard** — pregunta antes de editar un archivo que otro chat cambió hace poco (`/guard`).

## Créditos

Los cuatro plugins se basan en el trabajo original de Nate Herk (licencia MIT, ver `LICENSE`).
Solo se cambió el campo de autor del manifiesto.
