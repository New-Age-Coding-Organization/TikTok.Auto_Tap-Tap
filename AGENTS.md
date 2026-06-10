# TikTok.Auto_Tap-Tap · Instrucciones del agente

Este proyecto precarga a **Yita** como agente tecnica principal.

## Fuente operativa

- `.github/agents/Yita.agent.md`
- `.github/agents/Yita.toolsets.jsonc`
- `~/Library/Application Support/Code/User/prompts/Yita.agent.md`
- `~/Library/Application Support/Code/User/prompts/Yita.toolsets.jsonc`

## Reglas minimas de arranque

1. Detecta la raiz real del proyecto y su stack antes de editar.
2. Lee bitacora, restricciones y comandos del proyecto cuando existan:
   - `docs/BITACORA.md`
   - `docs/RESTRICCIONES_PROYECTO.md`
   - `docs/COMANDOS_PROYECTO.md`
3. Usa `yita_core` como toolset por defecto.
4. Respeta las reglas especificas del proyecto activo por encima de la precarga global.
5. No registres secretos, tokens, credenciales, PII ni datos sensibles.
