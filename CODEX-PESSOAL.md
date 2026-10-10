# Codex pessoal

Este fork pertence a emanuelle-lima/fluxo_criativo. A origem é ReadyToGo-Education/fluxo_criativo.

Use a branch codex-pessoal para personalizações. Nunca envie commits ou Pull Requests para a origem. A branch main recebe atualizações da origem via GitHub Actions, e a automação tenta incorporá-las a codex-pessoal. Em caso de conflito, a execução deve falhar sem descartar alterações.

O arquivo AGENTS.md e as fontes .claude/ continuam sendo as referências metodológicas. Após alterações nas fontes, execute python3 scripts/exportar-para-codex.py e depois python3 scripts/exportar-para-codex.py --verificar.

A presença de .codex/hooks.json não garante que os hooks sejam executados pelo ambiente Codex. Verifique as validações críticas antes de publicar entregas.
