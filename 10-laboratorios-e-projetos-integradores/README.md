# 10-laboratorios-e-projetos-integradores — Laboratórios Práticos e Projetos Integradores

Implementações completas prontas para portfólio corporativo.

## 📂 Subáreas
- [`pipeline-multi-cloud-completo/`](./pipeline-multi-cloud-completo) — **Stack:** `GitHub Actions completo: Build -> Scan -> Deploy AWS ECS/EKS` — Solução completa demonstrando todas as etapas de um pipeline de entrega contínua.
- [`self-hosted-runner-kubernetes/`](./self-hosted-runner-kubernetes) — **Stack:** `Actions Runner Controller (ARC) em cluster local` — Implantação de runners efêmeros que sobem e descem conforme a fila de jobs.
- [`devsecops-supply-chain-security/`](./devsecops-supply-chain-security) — **Stack:** `Gitleaks + SonarQube + Trivy + Cosign + SBOM` — Esteira blindada de segurança atendendo a requisitos de conformidade corporativa.

## 📌 Guia de Execução & Padrões
- Todas as etapas devem incluir verificações de saída (exit codes) estritas.
- Utilize autenticação OIDC passwordless sempre que integrar com provedores de nuvem (AWS, Azure, GCP).
