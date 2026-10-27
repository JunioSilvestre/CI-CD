# self-hosted-runner-kubernetes

> Implantação de runners efêmeros que sobem e descem conforme a fila de jobs.

## 🛠️ Tecnologias & Componentes
- `Actions Runner Controller (ARC) em cluster local`

## 📋 Boas Práticas e Padrões de Produção
- Mantenha etapas de pipeline idempotentes, rápidas e determinísticas.
- Isole dependências via containers ou cache gerenciado.
- Nunca versione senhas, tokens de acesso ou chaves privadas em arquivos de configuração de pipeline.
- Siga as diretrizes de padronização corporativa do módulo [`10-laboratorios-e-projetos-integradores`](../).
