# 07-estrategias-de-deploy — Estratégias Avançadas de Implantação

Metodologias de implantação sem indisponibilidade para o usuário final e controle fino de tráfego.

## 📂 Subáreas
- [`rolling-updates/`](./rolling-updates) — **Stack:** `Zero-downtime deployment, health probes, graceful shutdown` — Substituição gradual de instâncias garantindo atendimento contínuo.
- [`blue-green/`](./blue-green) — **Stack:** `Active/Passive pools, troca rápida de roteamento DNS/Load Balancer` — Garantia de rollback instantâneo através da manutenção de dois ambientes idênticos.
- [`canary-deployments/`](./canary-deployments) — **Stack:** `Argo Rollouts, Flagger, análise estatística de métricas` — Roteamento de 5% a 10% do tráfego real para a nova versão antes da promoção total.
- [`feature-flags/`](./feature-flags) — **Stack:** `LaunchDarkly, Unleash, desassociação de deploy e release` — Ativação controlada de funcionalidades em tempo de execução sem novo deploy de código.

## 📌 Guia de Execução & Padrões
- Todas as etapas devem incluir verificações de saída (exit codes) estritas.
- Utilize autenticação OIDC passwordless sempre que integrar com provedores de nuvem (AWS, Azure, GCP).
