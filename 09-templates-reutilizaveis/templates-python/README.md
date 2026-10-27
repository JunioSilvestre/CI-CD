# templates-python

> Pipeline completo para aplicações e microsserviços Python/FastAPI.

## 🛠️ Tecnologias & Componentes
- `Lint com Ruff + Testes Pytest + Dockerfile + Scan Trivy`

## 📋 Boas Práticas e Padrões de Produção
- Mantenha etapas de pipeline idempotentes, rápidas e determinísticas.
- Isole dependências via containers ou cache gerenciado.
- Nunca versione senhas, tokens de acesso ou chaves privadas em arquivos de configuração de pipeline.
- Siga as diretrizes de padronização corporativa do módulo [`09-templates-reutilizaveis`](../).
