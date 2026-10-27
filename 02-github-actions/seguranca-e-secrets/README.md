# seguranca-e-secrets

> Autenticação passwordless eliminando credenciais de longa duração gravadas no repositório.

## 🛠️ Tecnologias & Componentes
- `OIDC authentication (AWS/Azure/GCP), GitHub Secrets, Dependabot`

## 📋 Boas Práticas e Padrões de Produção
- Mantenha etapas de pipeline idempotentes, rápidas e determinísticas.
- Isole dependências via containers ou cache gerenciado.
- Nunca versione senhas, tokens de acesso ou chaves privadas em arquivos de configuração de pipeline.
- Siga as diretrizes de padronização corporativa do módulo [`02-github-actions`](../).
