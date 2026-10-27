# feature-flags

> Ativação controlada de funcionalidades em tempo de execução sem novo deploy de código.

## 🛠️ Tecnologias & Componentes
- `LaunchDarkly, Unleash, desassociação de deploy e release`

## 📋 Boas Práticas e Padrões de Produção
- Mantenha etapas de pipeline idempotentes, rápidas e determinísticas.
- Isole dependências via containers ou cache gerenciado.
- Nunca versione senhas, tokens de acesso ou chaves privadas em arquivos de configuração de pipeline.
- Siga as diretrizes de padronização corporativa do módulo [`07-estrategias-de-deploy`](../).
