# 02-github-actions — GitHub Actions Corporativo

Automação avançada com workflows YAML, composite actions, matrix builds, OIDC e segurança de secrets.

## 📂 Subáreas
- [`workflows-e-sintaxe/`](./workflows-e-sintaxe) — **Stack:** `workflow_dispatch, push, pull_request, matrix, reusable workflows` — Declaração de rotinas de automação com paralelismo e reutilização de steps.
- [`custom-actions-e-composite/`](./custom-actions-e-composite) — **Stack:** `action.yml, composite actions, Docker actions, TypeScript actions` — Desenvolvimento e empacotamento de ações customizadas reutilizáveis.
- [`seguranca-e-secrets/`](./seguranca-e-secrets) — **Stack:** `OIDC authentication (AWS/Azure/GCP), GitHub Secrets, Dependabot` — Autenticação passwordless eliminando credenciais de longa duração gravadas no repositório.
- [`runners-auto-hospedados/`](./runners-auto-hospedados) — **Stack:** `Actions Runner Controller (ARC), Kubernetes runners autoscaling` — Orquestração de executores elásticos e seguros dentro de clusters Kubernetes.

## 📌 Guia de Execução & Padrões
- Todas as etapas devem incluir verificações de saída (exit codes) estritas.
- Utilize autenticação OIDC passwordless sempre que integrar com provedores de nuvem (AWS, Azure, GCP).
