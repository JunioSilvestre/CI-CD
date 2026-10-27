# pacotes-e-bibliotecas

> Publicação e versionamento imutável de bibliotecas internas e artefatos binários.

## 🛠️ Tecnologias & Componentes
- `GitHub Packages (GHCR), PyPI, Nexus, Artifactory`

## 📋 Boas Práticas e Padrões de Produção
- Mantenha etapas de pipeline idempotentes, rápidas e determinísticas.
- Isole dependências via containers ou cache gerenciado.
- Nunca versione senhas, tokens de acesso ou chaves privadas em arquivos de configuração de pipeline.
- Siga as diretrizes de padronização corporativa do módulo [`06-build-e-gerenciamento-de-artefatos`](../).
