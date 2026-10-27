# canary-deployments

> Roteamento de 5% a 10% do tráfego real para a nova versão antes da promoção total.

## 🛠️ Tecnologias & Componentes
- `Argo Rollouts, Flagger, análise estatística de métricas`

## 📋 Boas Práticas e Padrões de Produção
- Mantenha etapas de pipeline idempotentes, rápidas e determinísticas.
- Isole dependências via containers ou cache gerenciado.
- Nunca versione senhas, tokens de acesso ou chaves privadas em arquivos de configuração de pipeline.
- Siga as diretrizes de padronização corporativa do módulo [`07-estrategias-de-deploy`](../).
