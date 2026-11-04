# Fotografia automotiva com IA — padrão São Bento

**Uso:** direção de arte, recorte e tratamento de fotografias de veículos para Toyota/Mirai e outras marcas, preservando a fidelidade ao veículo real.

**Natureza deste documento:** curadoria e procedimento original da São Bento, inspirado em referências externas. **Não é um software, nem instala modelos ou habilita automaticamente edição de imagens no ChatGPT.** Para cada trabalho, consultar este arquivo e as imagens originais aprovadas pelo cliente.

## Fontes estudadas e atribuição

- [aeozturkmen/car-background-removal](https://github.com/aeozturkmen/car-background-removal) — guia de remoção e substituição de fundo para concessionárias, segmentação, sombras, placas e padronização; Ahmet Eren Öztürkmen / Car Studio AI.
- [aeozturkmen/ai-car-photo-editor](https://github.com/aeozturkmen/ai-car-photo-editor) — guia de avaliação de editores automotivos com IA, iluminação, processamento em lote, qualidade e integração; Ahmet Eren Öztürkmen / Car Studio AI.
- Conteúdos de origem publicados sob licença **CC BY 4.0**. Esta página sintetiza procedimentos em redação própria e preserva a atribuição; **não copia integralmente** os guias nem incorpora imagens de demonstração para uso comercial sem licença.

Os dois repositórios são **documentação/guia de escolha de ferramentas**, não aplicativos open source de remoção de fundo. A plataforma comercial vinculada aos autores é a [Car Studio AI](https://carstudio.ai/); verificar seus termos e preços atuais antes de contratar ou integrar.

## Critério principal

**Aprimorar a apresentação nunca significa alterar o produto.** A fotografia final deve corresponder ao veículo original do cliente. Nenhuma IA está autorizada a redesenhar grade, faróis, lanternas, rodas, retrovisores, emblemas, proporções, linhas de carroceria, acessórios, acabamento ou estado de conservação. Não inventar modelos/versões Toyota Brasil. Na ausência de fotografia oficial suficiente, **solicitar imagem de referência autorizada ou limitar a entrega a estudo conceitual claramente identificado**.

## Escolher o fluxo pelo objetivo

| Objetivo | Tratamento preferido | Restrições |
|---|---|---|
| Catálogo, estoque e marketplace | fundo de estúdio cinza suave ou branco com contraste, enquadramento padronizado, sombra de contato | não ocultar avarias; preservar ângulo e estado do veículo |
| Campanha publicitária / key visual | fotografia real autorizada como hero + cenário e luz coerentes + composição editorial | não reconstruir a identidade visual do carro pela IA |
| Lançamento e branding premium | fotografia oficial + espaço negativo + hierarquia tipográfica | evitar texturas falsas, reflexos incoerentes, excessos de glow/neon |
| Lote grande de fotos | padronização de captura, processamento em lote e revisão em grade | testar primeiro reflexos e veículos escuros; prever revisão humana |

## Pipeline de trabalho — briefing até entrega

1. **Obter originais:** solicitar fotos reais autorizadas em máxima resolução, modelo, versão, ano, cor, ângulo desejado e formato de entrega. Registrar se a peça é oferta de concessionária, catálogo ou campanha conceitual.
2. **Diagnosticar a captura:** avaliar foco, iluminação, horizonte, corte de rodas/espelhos, reflexos, carro escuro e elementos finos (grade, rodas, antena, aerofólio, rack).
3. **Segmentar sem redesenhar:** remover o fundo preservando contorno, vidros, reflexos legítimos, retrovisores, raios das rodas e detalhes cromados. Revisar halos, recortes serrilhados e partes transparentes.
4. **Definir cenário adequado:** escolher entre transparente, fundo branco, estúdio em gradiente, fundo original suavizado ou cenário editorial. O contexto deve respeitar o ângulo de câmera e a direção de luz da fotografia.
5. **Reintegrar ao chão:** sombra de contato mais escura e estreita sob os pneus; difusão e direção coerentes com a iluminação; sem aparência de veículo flutuante. Reflexo de piso somente se fisicamente plausível.
6. **Calibrar cor e luz:** manter cor real, textura da pintura e desenho das peças; corrigir exposição e equilíbrio de brancos de modo contido. Não alisar contornos, inventar highlights ou trocar componentes.
7. **Diagramar separadamente:** usar tipografia, grid, logos oficiais e condições comerciais como camadas de design editáveis. Evitar depender de texto, números e logotipos gerados dentro da fotografia por IA.
8. **Revisar e exportar:** inspecionar em 100% e em miniatura, comparar lado a lado com o original, validar aprovação de marca e exportar cada formato nativo (ex.: 1080×1350, 1080×1920) sem deformar/cortar o carro.

## Checklist de qualidade automotiva (aprovação obrigatória)

- [ ] Veículo, versão, ano, cor, rodas, grade, faróis, proporções e detalhes **iguais à referência original**.
- [ ] Todos os espelhos, antena, partes de roda e áreas de vidro preservados sem halos.
- [ ] Pneus assentados no piso; direção, dureza e tamanho das sombras coerentes com a cena.
- [ ] Reflexos compatíveis com a iluminação e **sem objetos refletidos impossíveis**.
- [ ] Nenhuma avaria, risco, amassado, desgaste ou divergência de condição foi ocultada em fotos de venda.
- [ ] Marcas e emblemas oficiais verificados; não confiar em marca gerada automaticamente.
- [ ] Nenhum elemento promocional, taxa ou benefício inventado; conferir condições com cliente.
- [ ] Legibilidade mobile, boa hierarquia de informação, áreas seguras e formatos corretos.
- [ ] Avaliação comparativa em grade quando houver múltiplos carros e múltiplos ângulos.

## Fotografia de campanha sem “cara de IA”

- **Conceito antes do efeito:** determinar mensagem e ponto focal antes de gerar ou editar imagem.
- **Realismo de estúdio:** priorizar materiais reais, iluminação plausível, contraste controlado e uma única narrativa visual.
- **Menos é mais:** evitar excesso de brilho, reflexos genéricos, fumaça, partículas, carros idealizados e textos em excesso.
- **Layout editorial:** usar espaço negativo, alinhamento consistente, escala tipográfica e estrutura de leitura PT-BR.
- **Fidelidade absoluta:** se for foto de produto, não alterar o carro; se for peça ilustrativa criada por IA, não apresentá-la como foto oficial de modelo e versão.
- **Retoque seletivo:** problemas pequenos de recorte/sombra pedem correção localizada, não regeneração completa da carroceria.

## Prompt-base para tratamento de fotografia real

> Trate a fotografia anexada como **fonte de verdade absoluta do veículo**. Remova apenas o fundo e preserve integralmente geometria, perspectiva, proporções, cor, pintura, rodas, pneus, grade, faróis, lanternas, emblemas, retrovisores, vidros, reflexos legítimos e acessórios originais. Não invente, reprojete ou substitua peças. Aplique [fundo transparente/estúdio cinza/cenário definido], recorte preciso sem halos e sombra de contato realista sob cada pneu, compatível com a direção e a suavidade da luz. Não altere o estado físico ou as avarias do veículo. Entregue composição em [dimensões], com espaço para diagramação externa. Se algum detalhe não puder ser preservado fielmente, sinalize a limitação ao invés de inventá-lo.

**Nota:** este prompt orienta o trabalho; não garante recorte perfeito ou reconstrução técnica. Fazer inspeção humana e, quando necessário, composição manual.

## Como o Creative Brain deve utilizar este arquivo

Quando o pedido envolver **fotografias de carros, recorte, fundo transparente, realismo de concessionária, montagem de vários modelos ou campanha automotiva**, consultar:
1. [AGENTS.md](AGENTS.md) — papel criativo e regras de revisão;
2. [AUTOMOTIVO-TOYOTA.md](AUTOMOTIVO-TOYOTA.md) e [TOYOTA-BRASIL-BRANDBOOK-2026-GUIA.md](TOYOTA-BRASIL-BRANDBOOK-2026-GUIA.md) — fidelidade Toyota, brandbook e aprovações;
3. **Este documento** — tratamento da fotografia, sombras e exportação;
4. [BIBLIOTECA-GITHUB.md](BIBLIOTECA-GITHUB.md) — origens técnicas e links;
5. Arquivos de referência fornecidos pelo cliente ou [toyota-brasil/](toyota-brasil/) quando pertinente.

A implementação efetiva exige ferramentas de imagem disponíveis no ambiente e os materiais autorizados. **O GitHub é a base de conhecimento consultável; apenas armazenar links não treina o modelo, não instala softwares e não ativa edições automáticas.**
