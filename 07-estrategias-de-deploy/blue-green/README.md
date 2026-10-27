# blue-green

> Garantia de rollback instantâneo através da manutenção de dois ambientes idênticos.

## 🛠️ Tecnologias & Componentes
- `Active/Passive pools, troca rápida de roteamento DNS/Load Balancer`

## 📋 Boas Práticas e Padrões de Produção
- Mantenha etapas de pipeline idempotentes, rápidas e determinísticas.
- Isole dependências via containers ou cache gerenciado.
- Nunca versione senhas, tokens de acesso ou chaves privadas em arquivos de configuração de pipeline.
- Siga as diretrizes de padronização corporativa do módulo [`07-estrategias-de-deploy`](../).
