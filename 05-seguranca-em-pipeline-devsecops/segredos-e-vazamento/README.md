# segredos-e-vazamento

> Inspeção contra commits acidentais de chaves de API, senhas e certificados privados.

## 🛠️ Tecnologias & Componentes
- `Gitleaks, TruffleHog, pre-commit hooks`

## 📋 Boas Práticas e Padrões de Produção
- Mantenha etapas de pipeline idempotentes, rápidas e determinísticas.
- Isole dependências via containers ou cache gerenciado.
- Nunca versione senhas, tokens de acesso ou chaves privadas em arquivos de configuração de pipeline.
- Siga as diretrizes de padronização corporativa do módulo [`05-seguranca-em-pipeline-devsecops`](../).
