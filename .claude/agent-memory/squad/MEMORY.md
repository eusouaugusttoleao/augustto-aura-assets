# Squad Architect — Memory

## Active project
- **Repo**: augustto-aura-assets (branch `claude/activate-aiossquad-cfqcX`)
- **Workspace**: `mentoria-cirurgiao-capilar/` — separado do projeto Aura para evitar conflito.
- **Cliente**: aluno de mentoria, cirurgião capilar (landing/página em construção).

## Squad status
- Activated on 2026-05-04 from SynkraAI/aiox-core@main.
- Installed agents: `squad`, `squad-chief`, `oalanicolas`, `pedro-valerio`, `sop-extractor`.
- Workflows directory `squads/squad-creator/workflows/` is empty (template not pulled). Squad agent should fall back to internal heuristics or request creation before referencing wf-*.yaml files.

## Decisions log
- 2026-05-04: Página do cirurgião capilar ficará em `mentoria-cirurgiao-capilar/` para isolar do projeto Aura.

## Pending
- Definir squad de domínio (cirurgia capilar / saúde / marketing médico) com `*create-squad`.
- Coletar referências do aluno (público-alvo, posicionamento, voice).
