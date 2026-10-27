# assinatura-e-sbom

> Assinatura criptográfica de imagens e geração de lista de materiais de software (SBOM).

## 🛠️ Tecnologias & Componentes
- `Cosign, Sigstore, Syft, Grype, SLSA provenance`

## 📋 Boas Práticas e Padrões de Produção
- Mantenha etapas de pipeline idempotentes, rápidas e determinísticas.
- Isole dependências via containers ou cache gerenciado.
- Nunca versione senhas, tokens de acesso ou chaves privadas em arquivos de configuração de pipeline.
- Siga as diretrizes de padronização corporativa do módulo [`05-seguranca-em-pipeline-devsecops`](../).
