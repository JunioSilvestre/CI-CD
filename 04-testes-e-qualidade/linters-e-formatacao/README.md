# linters-e-formatacao

> Inspeção estática contínua de código nos branches antes de autorizar o merge.

## 🛠️ Tecnologias & Componentes
- `Ruff, ShellCheck, ESLint, TFLint, Prettier`

## 📋 Boas Práticas e Padrões de Produção
- Mantenha etapas de pipeline idempotentes, rápidas e determinísticas.
- Isole dependências via containers ou cache gerenciado.
- Nunca versione senhas, tokens de acesso ou chaves privadas em arquivos de configuração de pipeline.
- Siga as diretrizes de padronização corporativa do módulo [`04-testes-e-qualidade`](../).
