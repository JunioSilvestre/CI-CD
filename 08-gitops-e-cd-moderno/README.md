# 08-gitops-e-cd-moderno — Integração GitOps & Entrega Contínua

A ponte entre o pipeline de CI (integração) e o operador GitOps (entrega contínua em cluster).

## 📂 Subáreas
- [`argocd-integration/`](./argocd-integration) — **Stack:** `Git commit no repositório de manifests, webhook trigger, sync wait` — O pipeline atualiza a tag da imagem no repositório de infraestrutura e notifica o ArgoCD.
- [`flux-cd-automation/`](./flux-cd-automation) — **Stack:** `ImageUpdateAutomation, commit assinado de volta ao Git` — Detecção automática de novas imagens de containers e reconciliação contínua.
- [`notificacoes-e-auditoria/`](./notificacoes-e-auditoria) — **Stack:** `Slack, Discord, Microsoft Teams, Datadog deployment markers` — Envio automatizado de status de deploy com links de auditoria e runbooks.

## 📌 Guia de Execução & Padrões
- Todas as etapas devem incluir verificações de saída (exit codes) estritas.
- Utilize autenticação OIDC passwordless sempre que integrar com provedores de nuvem (AWS, Azure, GCP).
