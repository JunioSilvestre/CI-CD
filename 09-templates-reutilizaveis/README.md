# 09-templates-reutilizaveis — Bibliotecas de Pipelines e Templates Corporativos

Modelos prontos e testados para stacks padrão de mercado.

## 📂 Subáreas
- [`templates-python/`](./templates-python) — **Stack:** `Lint com Ruff + Testes Pytest + Dockerfile + Scan Trivy` — Pipeline completo para aplicações e microsserviços Python/FastAPI.
- [`templates-nodejs/`](./templates-nodejs) — **Stack:** `Lint ESLint + Build Next.js/Node + Testes Jest + Container` — Pipeline padronizado para aplicações frontend e APIs em TypeScript/JavaScript.
- [`templates-terraform/`](./templates-terraform) — **Stack:** `terraform fmt + validate + tflint + plan em PR + apply em main` — Automação segura de infraestrutura com aprovação baseada em pull request.
- [`templates-shell-linux/`](./templates-shell-linux) — **Stack:** `shellcheck + shfmt + testes BATS` — Validação rigorosa de scripts de automação operacional para servidores Linux.

## 📌 Guia de Execução & Padrões
- Todas as etapas devem incluir verificações de saída (exit codes) estritas.
- Utilize autenticação OIDC passwordless sempre que integrar com provedores de nuvem (AWS, Azure, GCP).
