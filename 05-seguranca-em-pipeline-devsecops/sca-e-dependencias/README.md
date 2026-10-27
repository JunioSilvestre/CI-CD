# sca-e-dependencias

> Varredura automatizada de dependências e bibliotecas de terceiros contra CVEs conhecidas.

## 🛠️ Tecnologias & Componentes
- `Trivy, Snyk, pip-audit, npm audit, Dependabot`

## 📋 Boas Práticas e Padrões de Produção
- Mantenha etapas de pipeline idempotentes, rápidas e determinísticas.
- Isole dependências via containers ou cache gerenciado.
- Nunca versione senhas, tokens de acesso ou chaves privadas em arquivos de configuração de pipeline.
- Siga as diretrizes de padronização corporativa do módulo [`05-seguranca-em-pipeline-devsecops`](../).
