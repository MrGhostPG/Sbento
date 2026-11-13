# Integração de design e agentes criativos — São Bento

**Data da curadoria:** 2026-11-13  
**Objetivo:** ampliar o Creative Brain com repertório, método e especificações de skills, sem confundir documentação com instalação de aplicativos.

## Oito fontes externas avaliadas

| Fonte | Natureza | Aplicação na São Bento | Decisão |
| --- | --- | --- | --- |
| [Mozilla OpenDesign](https://github.com/mozilla/OpenDesign) | comunidade de pedidos de design; repositório arquivado | briefing claro, objetivos, referências, prazo e colaboração | consultar como histórico; **não instalar** |
| [LangChain Design Agent / Content Studio](https://github.com/langchain-ai/design-agent) | aplicação/arquitetura de agente; licença Apache 2.0 | roteamento por skill, brand pack, produção por etapas e QA | **adaptar método**; implantação depende de infraestrutura específica |
| [DesignHub](https://github.com/yakew7/DesignHub) | aplicativo local-first; licença MIT | brand kits, cores, tipografia, tokens, mockups, exportação | **avaliar instalação separada**; método incorporado aqui |
| [brands-design-md](https://github.com/ricocc/brands-design-md) | coleção de DESIGN.md e referências visuais | leitura de identidade, grids, spacing e organização de tokens | **referência de estudo**, não manual oficial das marcas |
| [Porsche Design System](https://github.com/porsche-design-system/porsche-design-system) | toolkit para aplicativos Porsche | consistência, design tokens, acessibilidade e controle de qualidade | **estudar método**, sem copiar identidade Porsche |
| [Motion Design Skills](https://github.com/iart-ai/motion-design-skills) | skills de animação; licença MIT | direção de movimento, composição de cenas, logo, AE e Remotion | **adaptar princípios** em skill interna |
| [Open AI Design Agent](https://github.com/Anil-matcha/Open-AI-Design-Agent) | app com orquestração de modelos; licença MIT | cadeia de geração/edição e kits multiformato | **avaliar piloto isolado**; geração pode exigir serviços/API |
| [Design Buddy](https://github.com/SpaceZephyr/design-buddy) | coleção de skills de criação visual | filosofia visual, pôster, storyboard, apresentações e infográficos | **adaptar fluxos**; scripts dependem de runtime e credenciais |

**Importante:** nenhuma das oito aplicações acima foi clonada ou executada pelo simples cadastro nesta biblioteca. Referências e skills adaptadas são arquivos locais deste repositório; instalação no macOS, ativação no ChatGPT, chamadas a serviços pagos e sincronização contínua requerem procedimentos próprios. Não confundir código aberto com serviço de inferência gratuito.

## Skills internas para consulta por agentes

- [Direção de arte e campanhas](skills/direcao-arte-campanhas/SKILL.md): conceito, imagem hero, hierarquia, desdobramento e aprovação comercial.
- [Branding e sistema visual](skills/branding-sistema-visual/SKILL.md): identidade, grade, tokens e manual de aplicação.
- [Motion e storyboard](skills/motion-storyboard/SKILL.md): linguagem de movimento, cenas, timing e plano audiovisual.
- [Produção criativa com IA](skills/producao-criativa-ia/SKILL.md): orquestração de entregas, dependências, controle de fidelidade e revisão.

Estas quatro skills foram **escritas e adaptadas para a São Bento**, com referência explícita aos projetos externos; não são reproduções nem instalações oficiais de terceiros. Quando o briefing mencionar a área correspondente, consultar a skill e os manuais da marca.

## Ordem de precedência

1. Briefing e ativos oficiais autorizados do cliente.
2. Regras de marca e restrições legais documentadas neste repositório (sobretudo Toyota Brasil/Mirai).
3. `AGENTS.md`, `METODO-CRIATIVO.md` e o material específico do cliente.
4. Skills internas de design.
5. Repositórios externos apenas como referência técnica e repertório crítico.

Nunca substituir Toyota Type ou uma assinatura oficial por fontes, ícones, logos ou cores Porsche/Mozilla ou de qualquer outro sistema. Nunca inventar ficha técnica, preço, alegação publicitária ou autorização de uso.

## Acionamento por demanda

| Pedido | Ler primeiro | Complementos |
| --- | --- | --- |
| Peça publicitária, feed, outdoor, campanha | `skills/direcao-arte-campanhas/SKILL.md` | `METODO-CRIATIVO.md`, composição, manual da marca |
| Marca, identidade, brandbook, landing page | `skills/branding-sistema-visual/SKILL.md` | DesignHub, DESIGN.md, regras oficiais |
| Reels, vinheta, animação, motion graphics | `skills/motion-storyboard/SKILL.md` | motion-design-skills, assets autorizados |
| Muitas peças ou formatos, pipeline IA | `skills/producao-criativa-ia/SKILL.md` | LangChain Content Studio, Design Agent, regras de QA |
| Toyota, Mirai, veículos e peças originais | manuais Toyota + `FOTOGRAFIA-AUTOMOTIVA-IA.md` **obrigatórios** | skill específica do trabalho, subordinada ao Brandbook |

## Plano de evolução

**Fase 1 — concluída neste repositório:** cadastro das oito referências; quatro skills adaptadas; roteamento de consulta em `AGENTS.md`; vínculo na biblioteca e README.

**Fase 2 — opcional e independente:** testar DesignHub em ambiente próprio; avaliar implantação do Content Studio/Design Agent; instalar skills upstream somente em runtime compatível; configurar chaves em cofre privado e verificar licenças/dependências. Não executar scripts externos nem copiar conjuntos grandes de mídia sem auditoria prévia.

**Critério de aceitação:** briefing resolvido, marca correta, peça original, fotografia/produto fiel, texto em PT-BR revisado, versão mobile e impressa testada, entrega no formato exigido.

## Proveniência e manutenção

Consultar as fontes originais para atualizações; páginas e README de terceiros não são fontes normativas da marca cliente. Respeitar as licenças individuais antes de copiar código ou material. A curadoria é uma **fotografia de 2026-11-13**, não sincronização automática nem treinamento permanente do ChatGPT.
