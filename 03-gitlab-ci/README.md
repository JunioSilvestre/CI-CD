# 03-gitlab-ci — GitLab CI/CD

Configuração declarativa (.gitlab-ci.yml), templates reutilizáveis, gerenciamento de ambientes e runners.

## 📂 Subáreas
- [`gitlab-ci-yml/`](./gitlab-ci-yml) — **Stack:** `.gitlab-ci.yml, stages, jobs, artifacts, cache, rules` — Estruturação de pipelines com controle rigoroso de cache e artefatos compartilhados.
- [`include-e-templates/`](./include-e-templates) — **Stack:** `include:local, include:remote, CI/CD component catalog` — Modularização corporativa para que múltiplos projetos herdem pipelines padronizados.
- [`gitlab-runners/`](./gitlab-runners) — **Stack:** `gitlab-runner, Kubernetes executor, Docker socket binding` — Instalação e configuração de agentes de build com isolamento de tarefas.
- [`environments-e-deploy/`](./environments-e-deploy) — **Stack:** `environments, review apps, manual gates, protected environments` — Criação de ambientes dinâmicos por branch e travas manuais para aprovação em produção.

## 📌 Guia de Execução & Padrões
- Todas as etapas devem incluir verificações de saída (exit codes) estritas.
- Utilize autenticação OIDC passwordless sempre que integrar com provedores de nuvem (AWS, Azure, GCP).
