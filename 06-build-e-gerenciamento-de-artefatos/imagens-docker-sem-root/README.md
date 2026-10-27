# imagens-docker-sem-root

> Compilação de containers sem privilégios de root para execução segura em Kubernetes.

## 🛠️ Tecnologias & Componentes
- `Docker Buildx, Kaniko, cache multi-tier, multi-arch (amd64/arm64)`

## 📋 Boas Práticas e Padrões de Produção
- Mantenha etapas de pipeline idempotentes, rápidas e determinísticas.
- Isole dependências via containers ou cache gerenciado.
- Nunca versione senhas, tokens de acesso ou chaves privadas em arquivos de configuração de pipeline.
- Siga as diretrizes de padronização corporativa do módulo [`06-build-e-gerenciamento-de-artefatos`](../).
