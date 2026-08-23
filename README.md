# Galeria de Prompts

Coleção de prompts para apoiar atividades de análise, redação, comunicação e conformidade na Administração Pública.

Este repositório é mantido pela **Anatel** e está relacionado principalmente ao **SEI IA**, especialmente à funcionalidade **Galeria de Prompts**. Os prompts, porém, não são exclusivos do SEI IA: com as adaptações naturais de sintaxe, contexto, referências documentais e recursos disponíveis, eles podem ser utilizados em outras ferramentas, assistentes ou agentes de IA.

## Por que uma galeria de prompts importa

Uma galeria organizada reduz a barreira de entrada, compartilha práticas que já podem ser testadas e ajuda a transformar experiências individuais em conhecimento reutilizável. No SEI IA, ela também oferece um ponto de partida para que os servidores encontrem, adaptem e aprimorem prompts para suas atividades.

O consumo real pode levar algum tempo para atingir valores altos. Ele tende a ser diretamente proporcional às campanhas de letramento, oficinas e capacitações em prompts promovidas pelo órgão. Por isso, é altamente recomendável:

- cadastrar no SEI IA os prompts da galeria apresentados no tópico 8 do *Manual do Usuário do SEI IA*, além de outros prompts desenvolvidos pelo órgão;
- testar e revisar os prompts antes do cadastro, com entradas representativas e critérios claros de qualidade;
- incentivar a criação de prompts avançados, bem formatados e eficazes, alinhados às práticas de Engenharia de Prompts.

Assim, a galeria deixa de ser apenas um catálogo e passa a apoiar a adoção responsável e contínua da IA no trabalho.

## Conteúdo

Atualmente, o repositório reúne **57 prompts em dez áreas**. A contagem considera os arquivos `.txt` presentes na árvore do projeto.

| Área | Finalidade | Prompts | Orientações e descrições |
| --- | --- | ---: | --- |
| [Gerador de Ementas](Gerador_de_Ementas/) | Gerar ementas de decisões conforme o modelo padronizado pelo CNJ. | 1 | [Orientações](Gerador_de_Ementas/REAME.md) |
| [Jornalismo](Jornalismo/) | Criar notícias, revisar textos jornalísticos e preparar divulgação para WhatsApp. | 3 | [Orientações](Jornalismo/REAME.md) |
| [Linguagem Simples](Linguagem_Simples/) | Reescrever conteúdos a partir de texto colado, protocolo SEI ou uma ou mais URLs Gov.br. | 4 | [Orientações](Linguagem_Simples/REAME.md) |
| [Localizar de Prazos](Localizar_de_Prazos/) | Localizar prazos em documentos ou normas e organizá-los em tabela resumida. | 2 | [Orientações](Localizar_de_Prazos/REAME.md) |
| [Processo Administrativo Fiscal (PAF)](Processo_Administrativo_Fiscal-PAF/) | Produzir relatório sobre impugnação de crédito tributário em PAF. | 1 | [Orientações](Processo_Administrativo_Fiscal-PAF/REAME.md) |
| [Otimizador de Prompts](Otimizador_de_Prompts/) | Criar ou revisar prompts e ideias conforme o Modelo de Prompt Perfeito. | 1 | [Orientações](Otimizador_de_Prompts/REAME.md) |
| [Recapitulação de Reuniões](Recapitulacao_de_Reunicoes/) | Criar recapitulação de reunião e lista de ações a partir de transcrição ou gravação. | 3 | [Orientações](Recapitulacao_de_Reunicoes/REAME.md) |
| [Scrum: Criador de Estórias de Usuário](Scrum_Criador_de_Estorias_de_Usuario/) | Transformar decisões confirmadas em Estórias de Usuário a partir de gravação de reunião, conforme boas práticas do Scrum. | 2 | [Orientações](Scrum_Criador_de_Estorias_de_Usuario/REAME.md) |
| [Planejamento de Contratação não-TIC](Validar_Planejamento_Contratacao_nao-TIC/) | Validar quesitos de DFD, ETP, Pesquisa de Preços e TR para contratações em geral. | 15 | [Orientações](Validar_Planejamento_Contratacao_nao-TIC/REAME.md) |
| [Planejamento de Contratação TIC](Validar_Planejamento_Contratacao_TIC/) | Validar quesitos de DFD, ETP, Pesquisa de Preços e TR para contratações de TIC. | 25 | [Orientações](Validar_Planejamento_Contratacao_TIC/REAME.md) |
| **Total** |  | **57** |  |

Nas áreas de planejamento de contratação, os prompts estão organizados por documento e quesito:

- **DFD**: Documento de Formalização da Demanda;
- **ETP**: Estudo Técnico Preliminar;
- **PP**: Pesquisa de Preços;
- **TR**: Termo de Referência;
- **TCO**: análise comparativa de custos ao longo do ciclo de vida;
- **SRP** e **ARP**: Sistema de Registro de Preços e Ata de Registro de Preços;
- **DDO**: Declaração de Disponibilidade Orçamentária.

## Como usar

1. Escolha a área e abra o arquivo `.txt` do caso de uso desejado.
2. Leia o prompt inteiro e também as orientações da pasta correspondente antes de executá-lo.
3. Substitua os marcadores e forneça as entradas solicitadas. Em particular:
	- troque `#xxxxxxxx` pelo protocolo correto do documento no SEI;
	- cite os documentos relacionados exigidos pelo prompt, como DFD, ETP, PP, TR ou DDO;
	- em Linguagem Simples, informe o público-alvo e cole o texto ou as URLs solicitadas;
	- em Localizar de Prazos, use somente o texto vigente da lei ou norma;
	- em Jornalismo, informe as fontes e, quando aplicável, os exemplos de notícia indicados;
	- em Otimizador de Prompts, cole o prompt ou a ideia original entre as tags `<texto_do_prompt_original>` e `</texto_do_prompt_original>`;
	- em Recapitulação de Reuniões, escolha a versão adequada à fonte: arquivo com transcrição, transcrição colada ou URL da opção "Assistir no Navegador";
	- em Scrum: Criador de Estórias de Usuário, escolha `sistemaAna` ou `sistemaSEI` conforme o sistema e cole a URL da opção "Assistir no Navegador" na posição indicada.
4. Execute o prompt com os documentos e permissões adequados na ferramenta escolhida.
5. Revise o resultado comparando-o com as fontes. A saída da IA é apoio ao trabalho e não substitui a análise, a validação normativa ou a responsabilidade do servidor.

Ao usar os prompts fora do SEI IA, adapte as referências a documentos, a forma de anexar ou citar arquivos, os campos de entrada e os recursos específicos da ferramenta. Preserve, tanto quanto possível, o objetivo, as restrições e o formato de saída do prompt original.

## Cautelas essenciais

### Validações de contratação

Para os prompts de validação de planejamento de contratação:

- execute cada prompt em um tópico separado para a contratação em análise;
- não execute em sequência todos os quesitos no mesmo tópico, pois respostas anteriores podem influenciar o formato ou o mérito das respostas seguintes;
- na versão mais recente do SEI IA, desative a **Memória do Tópico** para evitar ruídos das interações anteriores;
- confira sempre se os protocolos citados correspondem aos documentos corretos.

### Fidelidade às fontes

- Não invente informações e não trate uma inferência como se estivesse na fonte.
- Confira se leis, normas e documentos usados estão vigentes e são aplicáveis ao caso.
- Preserve integralmente os trechos entre aspas quando o prompt determinar sua transcrição.
- Quando uma informação não estiver no documento, registre essa ausência em vez de preenchê-la por suposição.
- Faça revisão humana antes de usar o resultado em decisão, comunicação oficial, peça processual ou documento de contratação.

Também devem ser observadas as regras institucionais de sigilo, segurança da informação e proteção de dados ao fornecer conteúdo a qualquer ferramenta de IA.

## Cadastro na Galeria do SEI IA

Os arquivos deste repositório podem servir como base para o cadastro na Galeria de Prompts do SEI IA. Para cada cadastro:

1. use um título que identifique a área, o documento e o quesito, quando houver;
2. copie a versão testada do prompt e substitua os marcadores pelo modo de preenchimento adequado;
3. aproveite a sugestão de **Descrição do Prompt** registrada no `REAME.md` de cada pasta;
4. registre instruções de entrada, documentos necessários e limitações relevantes;
5. revise e atualize o cadastro quando normas, procedimentos ou o próprio prompt mudarem.

Além de cadastrar os prompts deste acervo e os apresentados no tópico 8 do Manual do Usuário do SEI IA, o órgão é incentivado a criar novos prompts a partir das necessidades reais dos servidores. Prompts bem especificados, testados e compartilhados tornam as capacitações mais práticas e ajudam a formar uma cultura de uso responsável da IA.

## Estado do acervo

- A área de **Planejamento de Contratação TIC** possui prompts para DFD, ETP, PP e os 14 quesitos de TR.
- A área de **Planejamento de Contratação não-TIC** possui prompts para DFD, ETP, PP e os quesitos 1 a 4 de TR.
- Os quesitos 5 a 14 de TR não-TIC aparecem nas orientações da pasta como pendentes e ainda não possuem arquivos `.txt` neste repositório.
- A área de **Otimizador de Prompts** possui um meta-prompt para criar ou revisar outros prompts conforme um modelo estruturado.
- A área de **Recapitulação de Reuniões** possui três variantes, conforme a forma de fornecimento da transcrição ou da gravação.
- A área de **Scrum: Criador de Estórias de Usuário** possui duas versões, configuradas para os sistemas Ana e SEI.

## Referências e materiais

As instruções dos prompts fazem referência, entre outras fontes, a:

- Lei nº 14.133/2021;
- Decreto nº 10.947/2022;
- IN SGD/ME nº 94/2022, nos prompts de contratação de TIC;
- Lei nº 15.263, de 14 de novembro de 2025, nos prompts de Linguagem Simples;
- padrão do CNJ para ementas;
- materiais de padronização e linguagem simples disponíveis nas pastas do projeto.

Materiais de apoio versionados neste repositório:

- [Manual de Linguagem Simples da Câmara dos Deputados](Linguagem_Simples/ManualdeLinguagemSimples_Camara_dos_Depurados.pdf);
- [Instrumento de Padronização AGU TIC](Validar_Planejamento_Contratacao_TIC/Instrumento_de_Padronizacao_AGU_TIC.pdf);
- [Aplicação de LLM no Controle de Conformidade em Licitações de TI](Validar_Planejamento_Contratacao_TIC/Aplicacao_de_LLM_no_Controle_de_Conformidade_em_Licitacoes_de_TI_TCC_LeonardoAlamy.pdf).

## Projetos relacionados

- [mod-sei-ia](https://github.com/anatelgovbr/mod-sei-ia)
- [sei-ia](https://github.com/anatelgovbr/sei-ia)

## Manutenção

Ao adicionar um prompt, prefira um arquivo `.txt` com um objetivo único, entradas claramente identificadas, restrições explícitas e formato de saída verificável. Atualize também as orientações da pasta e esta página quando a nova área alterar o mapa da galeria.