# notificacoes-e-auditoria

> Envio automatizado de status de deploy com links de auditoria e runbooks.

## 🛠️ Tecnologias & Componentes
- `Slack, Discord, Microsoft Teams, Datadog deployment markers`

## 📋 Boas Práticas e Padrões de Produção
- Mantenha etapas de pipeline idempotentes, rápidas e determinísticas.
- Isole dependências via containers ou cache gerenciado.
- Nunca versione senhas, tokens de acesso ou chaves privadas em arquivos de configuração de pipeline.
- Siga as diretrizes de padronização corporativa do módulo [`08-gitops-e-cd-moderno`](../).
