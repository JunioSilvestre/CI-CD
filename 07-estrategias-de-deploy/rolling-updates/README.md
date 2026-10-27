# rolling-updates

> Substituição gradual de instâncias garantindo atendimento contínuo.

## 🛠️ Tecnologias & Componentes
- `Zero-downtime deployment, health probes, graceful shutdown`

## 📋 Boas Práticas e Padrões de Produção
- Mantenha etapas de pipeline idempotentes, rápidas e determinísticas.
- Isole dependências via containers ou cache gerenciado.
- Nunca versione senhas, tokens de acesso ou chaves privadas em arquivos de configuração de pipeline.
- Siga as diretrizes de padronização corporativa do módulo [`07-estrategias-de-deploy`](../).
