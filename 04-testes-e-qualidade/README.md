# 04-testes-e-qualidade — Testes Automatizados e Portões de Qualidade

Execução e exigência de aprovação em testes unitários, testes de integração, cobertura de código e linters.

## 📂 Subáreas
- [`testes-automatizados/`](./testes-automatizados) — **Stack:** `pytest, npm test, junit reports, testcontainers` — Execução paralela de suítes de testes com publicação de relatórios XML.
- [`cobertura-de-codigo/`](./cobertura-de-codigo) — **Stack:** `Codecov, coverage.py, Istanbul, thresholds mínimos` — Bloqueio automático de pull requests que reduzam a cobertura de código.
- [`linters-e-formatacao/`](./linters-e-formatacao) — **Stack:** `Ruff, ShellCheck, ESLint, TFLint, Prettier` — Inspeção estática contínua de código nos branches antes de autorizar o merge.

## 📌 Guia de Execução & Padrões
- Todas as etapas devem incluir verificações de saída (exit codes) estritas.
- Utilize autenticação OIDC passwordless sempre que integrar com provedores de nuvem (AWS, Azure, GCP).
