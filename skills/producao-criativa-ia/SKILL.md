---
name: sao-bento-producao-criativa-ia
description: Planejamento de campanhas multiformato, execução assistida por IA, roteamento de ferramentas, revisão técnica e organização de arquivos criativos.
---

# Produção criativa com IA — São Bento

**Ative quando:** o briefing pede múltiplas peças, variações, escala de produção, campanhas de fotos e vídeos, automação criativa ou fluxo de aprovação/qualidade.

## Orquestração responsável

1. **Ler as regras internas e do cliente**; separar especificações verificadas de hipóteses e ideias.
2. Construir um **brand pack**: logos aprovados, fontes licenciadas, paleta, tom verbal, modelos de produto corretos, legal e restrições. Dados sigilosos não entram no GitHub público.
3. Criar um mapa de entregas e dependências: conceito → fotografia/composição → KV → adaptação feed/stories/impresso → legendas → QA → exportação.
4. Escolher ferramenta por necessidade, não por moda: edição de imagem, desenho vetorial, código, motion, vídeo, revisão ou geração de variações.
5. Preservar **arquivos-fonte e camadas** quando viável. Em automotivo, usar foto real autorizada como âncora, verificar características de carro e sombra após alterações.
6. Fazer QA por peça: alinhamento visual, fidelidade da marca/produto, português, dados de venda, legal, formato/dimensões, margens e contraste.
7. Entregar com nomes claros e informar objetivamente o que foi produzido, o que faltou e o que depende de revisão humana.

## Roteamento por tipo

| Tarefa | Método recomendado |
| --- | --- |
| Lote de formatos | reutilização de KV com **recomposição** e QA por formato |
| Geração de variações | conceito aprovado + parâmetros fixos do brand pack |
| Motion | `../motion-storyboard/SKILL.md` + especificação de movimento |
| Identidade | `../branding-sistema-visual/SKILL.md` + fonte autorizada |
| Campanha varejo | `../direcao-arte-campanhas/SKILL.md` + validação comercial |
| Carro/Toyota | `../../FOTOGRAFIA-AUTOMOTIVA-IA.md` + guias Toyota primeiro |

## Referências técnicas

- [LangChain Design Agent / Content Studio](https://github.com/langchain-ai/design-agent): ideia de roteador por skills, wiki, brand pack, arquivos editáveis, revisão após render.
- [Open AI Design Agent](https://github.com/Anil-matcha/Open-AI-Design-Agent): planejamento de campanhas por ativos e uso modular de modelos e edição.
- [DesignHub](https://github.com/yakew7/DesignHub): fonte central de identidade e exportações.
- [Design Buddy](https://github.com/SpaceZephyr/design-buddy): seleção de estrutura de conteúdo e visuais por tipo de demanda.

## Limitações explícitas

Este arquivo não instala o Content Studio, Muapi, modelos de vídeo, servidores MCP, Slack, Remotion ou qualquer API. Não presumir credenciais, licenças de imagem, ferramentas ou renderizadores disponíveis. Nunca armazenar API keys, fontes comerciais, brandbooks integrais, propostas confidenciais ou material não autorizado no GitHub público. Execução e custos externos exigem configuração separada. Ferramenta com código aberto não equivale a geração gratuita.
