---
name: sao-bento-branding-sistema-visual
description: Construção e revisão de identidades, brandbooks, sistemas de tipografia, cores, design tokens, interfaces e consistência de marca.
---

# Branding e sistema visual — São Bento

**Ative quando:** criar identidade, refinamento de logo, manual, linguagem de campanha, papelaria, embalagem, identidade digital, site/landing page ou comparativos de design.

## Procedimento

1. Confirmar objetivo, categoria, público, personalidade, identidade existente, direitos de uso e meios de aplicação.
2. Consultar manual do cliente ANTES de consultar estilos de terceiros. Tratar referências públicas não oficiais como repertório, não como licença para copiar.
3. Definir conceito estratégico e princípios visuais, não somente um moodboard.
4. Construir **sistema**, com paleta por função (primária, contraste, neutros, estados), tipografia com pesos autorizados, escala de tamanhos, entrelinhas, margens e proporções.
5. Formalizar regra de logo: versões existentes, redução mínima comprovada, área de proteção, aplicações positiva/negativa, proibições e legibilidade.
6. Padronizar layout (colunas, intervalos, alinhamento, respiro, ritmo editorial); não impor uma grade digital de 12 colunas a uma peça impressa sem motivo.
7. Produzir aplicações-testes: feed, Stories, assinatura, papelaria, landing page, rótulo, fachada e/ou mídia do briefing.
8. Revisar WCAG/contraste em telas quando aplicável, reprodução de cor na impressão e tipografia em português brasileiro.
9. Documentar versão, origem, licença, responsáveis e pendências de aprovação.

## Design tokens, quando fizer sentido

```json
{
  "color": {"brand": "[cor oficial]", "surface": "[cor oficial]", "text": "[cor oficial]"},
  "type": {"family": "[fonte licenciada]", "display": "[peso autorizado]", "body": "[peso autorizado]"},
  "space": {"unit": "[unidade aprovada]"},
  "logo": {"asset": "[arquivo fornecido]", "clearspace": "[manual oficial]"}
}
```

Os valores acima são campos a preencher, **não** normas ou dados de uma marca real. A fonte de verdade é o manual oficial do cliente.

## Referências externas

- [DesignHub](https://github.com/yakew7/DesignHub): brand kits, tokens, mockups, paletas, versões e exportação.
- [brands-design-md](https://github.com/ricocc/brands-design-md): formato `DESIGN.md` e descrições técnicas de linguagens digitais; coleção não oficial.
- [Porsche Design System](https://github.com/porsche-design-system/porsche-design-system): disciplina de componentes e consistência; não transferir estética Porsche para outras marcas.
- [Mozilla OpenDesign](https://github.com/mozilla/OpenDesign): formulação objetiva do pedido e colaboração; repositório arquivado.

**Entrega padrão:** conceito, guia de identidade, especificações, exemplos de uso, arquivos exportáveis quando viáveis, checklist comercial e pendências explícitas. Nunca afirmar que um logo é registrável sem verificação jurídica.
