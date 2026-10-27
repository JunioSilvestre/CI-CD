# helm-charts-packaging

> Publicação de versões de charts de infraestrutura validadas pelo pipeline.

## 🛠️ Tecnologias & Componentes
- `helm package, chart-releaser, OCI registries`

## 📋 Boas Práticas e Padrões de Produção
- Mantenha etapas de pipeline idempotentes, rápidas e determinísticas.
- Isole dependências via containers ou cache gerenciado.
- Nunca versione senhas, tokens de acesso ou chaves privadas em arquivos de configuração de pipeline.
- Siga as diretrizes de padronização corporativa do módulo [`06-build-e-gerenciamento-de-artefatos`](../).
