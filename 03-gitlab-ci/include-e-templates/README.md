# include-e-templates

> Modularização corporativa para que múltiplos projetos herdem pipelines padronizados.

## 🛠️ Tecnologias & Componentes
- `include:local, include:remote, CI/CD component catalog`

## 📋 Boas Práticas e Padrões de Produção
- Mantenha etapas de pipeline idempotentes, rápidas e determinísticas.
- Isole dependências via containers ou cache gerenciado.
- Nunca versione senhas, tokens de acesso ou chaves privadas em arquivos de configuração de pipeline.
- Siga as diretrizes de padronização corporativa do módulo [`03-gitlab-ci`](../).
