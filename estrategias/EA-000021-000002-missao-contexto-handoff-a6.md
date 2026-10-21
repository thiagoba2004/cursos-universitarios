# EA-000021-000002 — Missão aprovada, contexto especializado e recebimento operacional A6

**Projeto:** PRJ-000021 — Cursos Universitários  
**Estratégia:** `EA-000021-000002`  
**Origem/autoridade:** missão aprovada pelo titular em `REQ-000021-20261010-002`; execução documental de handoff autorizada por `REQ-GLOBAL-20261021-003` e `REQ-20261021-GDA-CHAT-001`.  
**Situação:** `IN_PROGRESS`, fase `F-000021-000002-002`.  
**Fronteira:** este plano não refaz o bootstrap `EA-000021-000001`, não aprova nova missão, não ativa SCIV, não instala configurações nativas e não equivale a aceite A6.

## Missão aprovada
Pesquisar e sistematizar informações sobre cursos superiores e instituições de ensino, com desenvolvimento condicionado a mandatos e fontes verificadas de inventários documentais, modelos de catálogo e estudos comparativos. Não oferecer cursos, matricular, certificar, representar instituições ou presumir autorização/reconhecimento sem evidências oficiais. Sem site Pages, gastos novos ou dados privados de alunos no Git público por inferência.

## Plano de fases (4 fases)
1. **FASE 01/04 [F-000021-000002-001] — Reconciliação da missão humana já aprovada.** Estado: `DOCUMENTARY_VERIFIED`. Objetivo: preservar `REQ-000021-20261010-002` e alinhar `MISSAO_E_ESCOPO.md`, `AGENTS.md`, `PROJECT_STATE.json` e `ROADMAP.md`. Gate: `MISSION_RECONCILED`. Não representa aceite A6.
2. **FASE 02/04 [F-000021-000002-002] — Fontes, contexto especializado e pacote de handoff.** Estado: `IN_PROGRESS`. Objetivo: conferir adaptador ChatGPT existente, fontes permitidas e próximo trabalho de pesquisa com seleção fundamentada de módulos. Gate: `CONTEXT_PACKAGE_RECOVERABLE` e autorizações delimitadas; sem obrigar reconfiguração nativa genérica.
3. **FASE 03/04 [F-000021-000002-003] — Comprovação B1/C3 e recuperação na conversa destinatária.** Estado: `HANDOFF_PENDING`. Objetivo: obter do titular atestação específica de que **a conversa que emitiu o relatório de recebimento de 20/10 pertence ao Projeto ChatGPT PRJ-000021**; aproveitar a prova visual C3 já reunida pela G0 e confirmar a leitura efetiva existente, sem refazer piloto SCIV. Gate: `B1_CURRENT_ATTESTATION_CONFIRMED`.
4. **FASE 04/04 [F-000021-000002-004] — Recibo A6 e continuidade especializada.** Estado: `HANDOFF_PENDING`. Objetivo: IA destinatária atual, em seu próprio contexto, emitir decisão positiva motivada de recebimento operacional e registrar recibo em `governanca/recebimentos/` com autorização, prova e readback. Gate: `PROJECT_OPERATIONAL_HANDOFF_ACCEPTED` somente se evidenciado.

## Pacote mínimo e papéis
- **Identidade e fontes:** `PRJ-000021`, `AGENTS.md`, `MISSAO_E_ESCOPO.md`, `PROJECT_STATE.json`, `ROADMAP.md`, `REQUEST_LOG.jsonl`, `STRATEGY_LOG.jsonl`, planos EAs 001/002 e `adaptadores/chatgpt/INSTRUCOES.md`; branch `main`.
- **Gerador PRJ-000002:** coordena documentação, reconciliação e handoff; não se torna executor da pesquisa sobre cursos.
- **IA especializada PRJ-000021:** confirma competência, limite das permissões, fontes, estado, riscos e primeiro passo operacional no seu próprio Projeto; emite recibo positivo **se** satisfeitos os requisitos.
- **Titular:** única intervenção residual material identificada — atestar B1 especificamente da conversa PRJ-000021, se não houver prova atual recuperável.
- **Fontes primárias futuras:** e-MEC, instituições de ensino e atos regulatórios vigentes, consultados e citados pela IA destinatária no momento de realizar pesquisa; nenhuma pesquisa temática substantiva executada por esta reconciliação.

## Limites e condição de parada
`A6_HANDOFF_PENDING` enquanto faltar atestação B1 específica ou recibo positivo da IA. A observação C3 anterior é evidência humana/visual, não inspeção independente da plataforma. Não exigir novo consentimento para missão aprovada, não ativar SCIV, não operar caixas nem exigir CPD, symlink físico ou Pages para este handoff. Primeiro trabalho após aceite: delimitar um recorte piloto de inventário de cursos, identificar fontes primárias oficiais e propor o método de catalogação, mediante autorização local.
