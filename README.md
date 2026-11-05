# Geografias da Reciclagem

**Atlas interativo de dados, políticas públicas e território brasileiro**  
**Autoria e direção técnica:** Camila Guedes Vicente · geógrafa

🌎 **[Acessar o Atlas](https://camilaguedesvicente.github.io/geografias-da-reciclagem/)**

> Projeto autoral independente, desenvolvido a partir de bases públicas. Não é uma plataforma oficial, nem representa ou recebe endosso das instituições responsáveis pelas fontes.

## Sobre o projeto

O *Geografias da Reciclagem* nasceu de uma pergunta: como tornar consultáveis informações dispersas sobre coleta seletiva, gestão de resíduos, organizações de catadores e atividades econômicas relacionadas à reciclagem **sem apagar as diferenças entre fontes, anos e escalas territoriais**?

O Atlas reúne mapas, indicadores e explicações em linguagem acessível para apoiar a formulação de perguntas sobre os municípios brasileiros. Seu propósito é ampliar o acesso à informação pública e favorecer uma leitura crítica do território — não oferecer um diagnóstico definitivo ou certificar a execução de políticas públicas.

## O que é possível explorar

- **Mapa interativo:** escolha perguntas sobre organizações de catadores, atividades relacionadas à reciclagem, fluxos declarados, coleta seletiva, gestão municipal e destinação final.
- **Gráficos e números:** examine indicadores e distribuições em diferentes recortes territoriais.
- **Consulta municipal:** pesquise municípios e acesse fichas e tabelas em texto.
- **Projeto e método:** conheça as decisões cartográficas, os procedimentos, as limitações e os próximos passos.
- **Entenda os dados:** consulte definições, fontes, períodos de referência e ressalvas.

A interface oferece uma leitura simplificada para começar, controles avançados para combinar camadas e alternativas textuais ao mapa. Testes com públicos diversos, dispositivos móveis e tecnologias assistivas integram a agenda de aprimoramento.

## Fontes e recortes

| Fonte | Informações utilizadas | Referência |
| --- | --- | --- |
| [SINISA — Ministério das Cidades](https://www.gov.br/cidades/pt-br/acesso-a-informacao/acoes-e-programas/saneamento/sinisa/resultados-sinisa) | Indicadores municipais de resíduos sólidos, gestão e fluxos declarados | Dados de 2023 e 2024 |
| [SINIR — Módulo Catadores](https://sinir.gov.br/sistemas/catadores/) | Registros declarados de organizações de catadores | Exportação de 03/11/2026 |
| [IBGE — Malhas territoriais](https://www.ibge.gov.br/geociencias/organizacao-do-territorio/malhas-territoriais/15774-malhas.html) | Geometrias e códigos municipais | Malha Municipal 2025 |
| [IBGE — SIDRA](https://sidra.ibge.gov.br/tabela/4714) | Informações censitárias para contextualização territorial | Censo 2022 |
| [IBGE — Biomas](https://www.ibge.gov.br/geociencias/informacoes-ambientais/estudos-ambientais/15842-biomas.html) | Referência para estimativas geoespaciais de participação municipal dos biomas | Biomas 2025 |
| [Receita Federal — Dados abertos do CNPJ](https://www.gov.br/receitafederal/pt-br/acesso-a-informacao/dados-abertos/cadastros) | Estabelecimentos com CNAEs relacionados a atividades da cadeia da reciclagem | Competência outubro/2026 |

O conjunto de indicadores cobre os **5.570 municípios brasileiros**, mas isso **não significa que todos tenham respondido a todos os campos**. A base está incorporada ao Atlas e **não possui atualização automática**.

### Cuidados de interpretação

- **Sem dado não é zero.** Ausência de resposta não comprova ausência de serviço ou atividade.
- **Declaração não é verificação de campo.** Respostas oficiais e registros cadastrais não comprovam, isoladamente, implementação ou efetividade.
- **CNAE não comprova compra de recicláveis.** Uma atividade econômica cadastrada não equivale a comprador confirmado.
- **Organizações SINIR são representadas de forma agregada.** A versão pública não divulga suas coordenadas ou endereços individuais.
- **Linhas de fluxo não representam trajetos reais.** Indicam movimentações declaradas entre localidades.
- **Recortes e estimativas são identificados.** A participação municipal em biomas decorre de processamento geoespacial do Atlas; não é um percentual oficial publicado pelo IBGE.

Consulte a aba **Entenda os dados** para as definições e ressalvas detalhadas de cada indicador.

## Tecnologias e processo de desenvolvimento

A preparação e a integração dos dados utilizaram procedimentos com **Python e SQLite**. A experiência web utiliza **HTML5, CSS3, JavaScript, SVG, JSON e CSV**.

**Ferramentas de IA generativa prestaram suporte à programação, revisão de código, solução de problemas e organização da interface.** A concepção, as escolhas de recorte, a revisão metodológica, a interpretação territorial e a comunicação dos resultados são dirigidas por **Camila Guedes Vicente**.

## Percurso do projeto

**Marco concluído — novembro de 2026:** publicação da versão inaugural para consulta pública.

Perspectivas para as próximas etapas:

1. **Do dado à política pública:** contextualizar indicadores com a PNRS, sua regulamentação, o Planares e um levantamento-piloto de normas e planos estaduais.
2. **Ampliar e qualificar as bases públicas:** incorporar novas séries quando comparáveis, documentando lacunas e diferenças metodológicas.
3. **Aprofundar as análises socioterritoriais:** investigar contrastes municipais e regionais, sem presumir causalidade.
4. **Investigar planejamento e implementação:** desenvolver estudos de caso com documentos, indicadores e, quando viável, escuta dos sujeitos envolvidos.
5. **Aprimorar o acesso público:** testar usabilidade, acessibilidade, documentação e procedimentos de atualização.

Esse percurso é uma **agenda de pesquisa e aprimoramento**, não um cronograma fechado de entregas.

## Autoria e caráter independente

**Camila Guedes Vicente** — geógrafa, com atuação em geoprocessamento, planejamento territorial e políticas públicas de resíduos sólidos.

O *Geografias da Reciclagem* é um **projeto autoral independente**. A indicação das instituições de origem das bases não implica coautoria, vínculo institucional ou endosso ao Atlas.

O repositório está público para consulta. A disponibilização do código não deve ser confundida com uma licença expressa de reutilização; a definição de uma licença para os componentes autorais permanece pendente. As condições de uso das fontes originais devem ser verificadas junto aos respectivos provedores.

## Referência sugerida

VICENTE, Camila Guedes. **Geografias da Reciclagem: atlas interativo de dados, políticas públicas e território**. 2026. Disponível em: https://camilaguedesvicente.github.io/geografias-da-reciclagem/.
