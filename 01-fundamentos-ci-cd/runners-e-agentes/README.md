# runners-e-agentes

> Arquiteturas de execução de pipelines efêmeros e seguros em infraestrutura própria.

## 🛠️ Tecnologias & Componentes
- `Hosted runners vs Self-hosted runners, Kaniko, Rootless containers`

## 📋 Boas Práticas e Padrões de Produção
- Mantenha etapas de pipeline idempotentes, rápidas e determinísticas.
- Isole dependências via containers ou cache gerenciado.
- Nunca versione senhas, tokens de acesso ou chaves privadas em arquivos de configuração de pipeline.
- Siga as diretrizes de padronização corporativa do módulo [`01-fundamentos-ci-cd`](../).
