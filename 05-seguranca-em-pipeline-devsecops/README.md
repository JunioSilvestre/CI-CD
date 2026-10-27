# 05-seguranca-em-pipeline-devsecops — DevSecOps & Segurança na Cadeia de Suprimentos

Integração contínua de segurança: análise estática (SAST), análise dinâmica (DAST), varredura de segredos e SBOM.

## 📂 Subáreas
- [`sast/`](./sast) — **Stack:** `SonarQube, Semgrep, Bandit, CodeQL` — Detecção precoce de falhas de segurança e injeções no código-fonte.
- [`sca-e-dependencias/`](./sca-e-dependencias) — **Stack:** `Trivy, Snyk, pip-audit, npm audit, Dependabot` — Varredura automatizada de dependências e bibliotecas de terceiros contra CVEs conhecidas.
- [`segredos-e-vazamento/`](./segredos-e-vazamento) — **Stack:** `Gitleaks, TruffleHog, pre-commit hooks` — Inspeção contra commits acidentais de chaves de API, senhas e certificados privados.
- [`assinatura-e-sbom/`](./assinatura-e-sbom) — **Stack:** `Cosign, Sigstore, Syft, Grype, SLSA provenance` — Assinatura criptográfica de imagens e geração de lista de materiais de software (SBOM).

## 📌 Guia de Execução & Padrões
- Todas as etapas devem incluir verificações de saída (exit codes) estritas.
- Utilize autenticação OIDC passwordless sempre que integrar com provedores de nuvem (AWS, Azure, GCP).
