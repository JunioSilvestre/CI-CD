# 01-fundamentos-ci-cd — Fundamentos de CI/CD e Ciclo de Vida

Conceitos fundamentais de pipelines, estágios de entrega contínua, estratégias de ramificação e agentes de execução.

## 📂 Subáreas
- [`conceitos-e-ciclo-de-vida/`](./conceitos-e-ciclo-de-vida) — **Stack:** `Lint, Build, Test, Scan, Package, Deploy, Smoke Tests` — O ciclo de vida completo de uma alteração desde o commit até a verificação pós-implantação.
- [`estrategias-de-branching/`](./estrategias-de-branching) — **Stack:** `Trunk-Based Development, GitHub Flow, GitFlow, Feature Flags` — Modelos de colaboração em equipe reduzindo conflitos e habilitando deploys frequentes.
- [`runners-e-agentes/`](./runners-e-agentes) — **Stack:** `Hosted runners vs Self-hosted runners, Kaniko, Rootless containers` — Arquiteturas de execução de pipelines efêmeros e seguros em infraestrutura própria.

## 📌 Guia de Execução & Padrões
- Todas as etapas devem incluir verificações de saída (exit codes) estritas.
- Utilize autenticação OIDC passwordless sempre que integrar com provedores de nuvem (AWS, Azure, GCP).
