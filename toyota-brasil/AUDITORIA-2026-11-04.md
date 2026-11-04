# Auditoria Toyota Brasil — 04/11/2026

**Responsável:** São Bento Creative Brain — curadoria de referências públicas para campanhas da Mirai Toyota.

## Escopo e critério

Esta atualização consolida o portfólio encontrado na **tabela pública Toyota do Brasil de maio de 2026**, cruzando com páginas oficiais de modelos e registros já existentes neste repositório. O objetivo é **evitar versões inventadas e visuais de outros mercados**, não afirmar estoque ou linha vigente em toda concessionária na data de consulta.

A fonte primária histórica é [tabela oficial de maio de 2026](https://media.toyota.com.br/b78fafa9-80f6-4a16-90f6-99e31640f403.pdf). Em consulta à Toyota Brasil, determinadas páginas do site principal não puderam ser abertas integralmente por restrições de acesso; os endereços da montadora foram cruzados com resultados públicos e a base existente. Logo, **nenhum URL de página isolado prova que todas as versões estão à venda hoje**.

## Resultado consolidado

**9 famílias de veículos; 36 configurações/versões de referência**, incluindo carrocerias de Hilux, variações híbridas e esportivas:

| Família | Configurações de referência 2026 | Versões/características que não devem ser confundidas |
|---|---:|---|
| [Corolla](https://www.toyota.com.br/modelos/corolla) | 5 | Sedã Flex, Hybrid, GR-Sport; nenhum destes é GR Corolla hatch |
| [Corolla Cross](https://www.toyota.com.br/modelos/corolla-cross) | 6 | Flex, Hybrid e GR-Sport / Dualtone |
| [Yaris Cross](https://www.toyota.com.br/modelos/yaris-cross) | 5 | Flex e Hybrid; não usar Yaris global/antigo |
| [Hilux Cabine Dupla](https://www.toyota.com.br/modelos/hilux-cabine-dupla) / [Cabine Simples](https://www.toyota.com.br/modelos/hilux-cabine-simples) | 10 | Dupla, simples e chassi-cabine; transmissões MT/AT |
| [SW4](https://www.toyota.com.br/modelos/sw4) | 3 | Platinum 5/7 lugares, Diamond |
| [RAV4 Hybrid](https://www.toyota.com.br/modelos/rav4) | 2 | S e SX AWD HEV; ano/geração corretos do Brasil |
| [Hiace](https://www.toyota.com.br/modelos/hiace) | 2 | Minibus versus Furgão; fabricação 2025/modelo 2026 na tabela |
| [GR Yaris](https://www.toyota.com.br/modelos/gr-yaris) | 2 | MT e AT |
| [GR Corolla](https://www.toyota.com.br/modelos/gr-corolla) | 1 | Hatch Circuit MT; distinto de Corolla GR-Sport |

**Total: 36 registros de configuração**, não 36 modelos independentes. Os nomes foram normalizados para pesquisa criativa, e a tabela histórica é autoridade final em caso de divergência.

**bZ4X:** registro separado como **referência de rede autorizada**, sem comprovação na tabela nacional de maio de 2026. Não usar como modelo nacional confirmado em peças sem nova validação com Mirai/Toyota.

## Ano-modelo 2027

A base existente registra anúncios de Corolla, Corolla Cross e Yaris Cross **2026/2027** na rede autorizada brasileira. Estas referências são evidência de ofertas locais, não um catálogo nacional completo de ano-modelo 2027. É obrigatório confirmar versão, chassi/ano, fotografia e disponibilidade com a Mirai antes de anunciar.

## Política de imagens oficiais

**Não foram importadas ou republicadas fotografias de veículos neste repositório.** Uma página Toyota Brasil ou Toyota Comunica é fonte de referência de modelo/fotografia, mas não autoriza automaticamente redistribuir imagens ou logotipos em um GitHub público.

Para uso publicitário profissional:
1. Escolher modelo, **versão**, ano-modelo, cor e mercado brasileiro.
2. Localizar a foto no [Toyota Brasil](https://www.toyota.com.br/) ou no [Toyota Comunica — downloads](https://www.toyotacomunica.com.br/downloads/).
3. Solicitar à Mirai/Toyota o ativo original autorizado, registrar URL/fonte, direitos, orientação, cor e data em **acervo privado**.
4. Preservar 100% da geometria e peças em recortes: faróis, grade, emblemas, rodas, vinco, espelhos, antenas, interiores e acabamento. Não substituir por uma composição gerada que altere a carroceria.
5. Para line-ups, primeiro recortar cada foto oficial aprovada, depois normalizar ângulo, perspectiva, escala relativa e sombra de contato. Não pedir à IA que recrie seis carros pela imaginação.
6. Diagramar marca, textos e preços separadamente, conforme [Brandbook Toyota Brasil 2026 — guia](../TOYOTA-BRASIL-BRANDBOOK-2026-GUIA.md).

### Estrutura recomendada de registro de imagem (acervo privado)

```yaml
familia: corolla-cross
versao: XRX Hybrid
mercado: BR
ano_modelo: a_confirmar
cor_oficial: a_confirmar
url_pagina_origem: a_confirmar
url_arquivo_original: a_confirmar
licenca_e_autorizacao: a_confirmar
orientacao: frontal_3_4
data_validacao: a_confirmar
aprovacao_mirai: pendente
fidelidade_visual: pendente
```

## Onde estão os dados

- [Inventário estruturado, JSON](inventario-oficial-2026-11-04.json) — 9 famílias, 36 registros, fontes, cautelas e status.
- [Catálogo histórico 2026](CATALOGO-2026.md) — transcrição editorial da tabela original.
- [Ano-modelo 2027](CATALOGO-2027.md) — registros de rede com grau de evidência.
- [Fontes e imagens](FONTES-E-IMAGENS.md) — procedência e cuidados com direitos.
- [Procedimento de fotografia automotiva](../FOTOGRAFIA-AUTOMOTIVA-IA.md) — recorte fiel, luz, sombra e controle de qualidade.

## Pendências declaradas

- Verificar novamente a disponibilidade **atual** de cada versão junto à Toyota Brasil e Mirai.
- Revalidar os links específicos de configuração e o ano-modelo de cada veículo.
- Obter autorização para arquivar e publicar fotos oficiais por versão. **Ainda não existe biblioteca de imagens binárias homologadas no GitHub.**
- A listagem nacional pode evoluir após a tabela de maio/2026; acrescentar mudanças somente com fonte primária verificável e data.

**Regra operacional:** tudo que estiver sem confirmação explícita é referência de estudo, não fato promocional aprovado.
