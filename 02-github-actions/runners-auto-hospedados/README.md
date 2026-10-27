# runners-auto-hospedados

> Orquestração de executores elásticos e seguros dentro de clusters Kubernetes.

## 🛠️ Tecnologias & Componentes
- `Actions Runner Controller (ARC), Kubernetes runners autoscaling`

## 📋 Boas Práticas e Padrões de Produção
- Mantenha etapas de pipeline idempotentes, rápidas e determinísticas.
- Isole dependências via containers ou cache gerenciado.
- Nunca versione senhas, tokens de acesso ou chaves privadas em arquivos de configuração de pipeline.
- Siga as diretrizes de padronização corporativa do módulo [`02-github-actions`](../).
