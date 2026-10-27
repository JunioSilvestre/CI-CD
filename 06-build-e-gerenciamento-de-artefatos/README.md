# 06-build-e-gerenciamento-de-artefatos — Builds Otimizados e Gestão de Artefatos

Construção de imagens de containers de alta performance, pacotes de software e registries.

## 📂 Subáreas
- [`imagens-docker-sem-root/`](./imagens-docker-sem-root) — **Stack:** `Docker Buildx, Kaniko, cache multi-tier, multi-arch (amd64/arm64)` — Compilação de containers sem privilégios de root para execução segura em Kubernetes.
- [`pacotes-e-bibliotecas/`](./pacotes-e-bibliotecas) — **Stack:** `GitHub Packages (GHCR), PyPI, Nexus, Artifactory` — Publicação e versionamento imutável de bibliotecas internas e artefatos binários.
- [`helm-charts-packaging/`](./helm-charts-packaging) — **Stack:** `helm package, chart-releaser, OCI registries` — Publicação de versões de charts de infraestrutura validadas pelo pipeline.

## 📌 Guia de Execução & Padrões
- Todas as etapas devem incluir verificações de saída (exit codes) estritas.
- Utilize autenticação OIDC passwordless sempre que integrar com provedores de nuvem (AWS, Azure, GCP).
