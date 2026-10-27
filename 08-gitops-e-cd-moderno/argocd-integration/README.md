# argocd-integration

> O pipeline atualiza a tag da imagem no repositório de infraestrutura e notifica o ArgoCD.

## 🛠️ Tecnologias & Componentes
- `Git commit no repositório de manifests, webhook trigger, sync wait`

## 📋 Boas Práticas e Padrões de Produção
- Mantenha etapas de pipeline idempotentes, rápidas e determinísticas.
- Isole dependências via containers ou cache gerenciado.
- Nunca versione senhas, tokens de acesso ou chaves privadas em arquivos de configuração de pipeline.
- Siga as diretrizes de padronização corporativa do módulo [`08-gitops-e-cd-moderno`](../).
