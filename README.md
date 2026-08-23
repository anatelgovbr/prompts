# Galeria de Prompts

É muito importante que o órgão cadastre na **Galeria** prompts avançados e crie mais prompts adequados às atividades do órgão.

Este repositório é mantido pela **Anatel** e está relacionado principalmente ao **SEI IA**, especialmente à funcionalidade **Galeria de Prompts**. Os prompts, porém, não são exclusivos do SEI IA: com adaptações naturais de sintaxe, contexto e referências documentais, eles podem ser utilizados em outras ferramentas, assistentes ou agentes de IA.

## Por que uma galeria de prompts importa

Uma galeria organizada reduz barreira de entrada, compartilha práticas que já podem ser testadas e ajuda a transformar experiências individuais em conhecimento reutilizável. No SEI IA, ela também oferece um ponto de partida para que os servidores encontrem, adaptem e aprimorem prompts para suas atividades.

O consumo real pode levar algum tempo para atingir valores altos. Ele tende a ser diretamente proporcional às campanhas de letramento, oficinas e capacitações em prompts promovidas pelo órgão. Por isso, é altamente recomendável:
- cadastrar no SEI IA os prompts avançados deste repositório, além de outros desenvolvidos pelo órgão;
- incentivar a criação de prompts avançados, bem formatados e eficazes, alinhados às boas práticas de Engenharia de Prompts.

A Galeria de Prompts iniciando com o máximo de prompts avançados serve como referência e orienta os usuários na criação de prompts mais completos, organizados e eficazes.

## Conteúdo

Este repositório reúne **57 prompts em dez áreas de conhecimento**.

| Área | Finalidade | Qtd. de Prompts | Orientações e descrições |
| --- | --- | ---: | --- |
| [Gerador de Ementas](Gerador_de_Ementas/) | Gerar ementas de decisões conforme o modelo padronizado pelo CNJ. | 1 | [Orientações](Gerador_de_Ementas/README.md) |
| [Jornalismo](Jornalismo/) | Criar notícias, revisar textos jornalísticos e preparar divulgação para WhatsApp. | 3 | [Orientações](Jornalismo/README.md) |
| [Linguagem Simples](Linguagem_Simples/) | Reescrever conteúdos a partir de texto colado, protocolo SEI ou uma ou mais URLs Gov.br. | 4 | [Orientações](Linguagem_Simples/README.md) |
| [Localizar de Prazos](Localizar_de_Prazos/) | Localizar prazos em documentos ou normas e organizá-los em tabela resumida. | 2 | [Orientações](Localizar_de_Prazos/README.md) |
| [Processo Administrativo Fiscal (PAF)](Processo_Administrativo_Fiscal-PAF/) | Produzir relatório sobre impugnação de crédito tributário em PAF. | 1 | [Orientações](Processo_Administrativo_Fiscal-PAF/README.md) |
| [Otimizador de Prompts](Otimizador_de_Prompts/) | Criar ou revisar prompts e ideias conforme o Modelo de Prompt Perfeito. | 1 | [Orientações](Otimizador_de_Prompts/README.md) |
| [Recapitulação de Reuniões](Recapitulacao_de_Reunicoes/) | Criar recapitulação de reunião e lista de ações a partir de transcrição ou gravação. | 3 | [Orientações](Recapitulacao_de_Reunicoes/README.md) |
| [Scrum: Criador de Estórias de Usuário](Scrum_Criador_de_Estorias_de_Usuario/) | Transformar decisões confirmadas em Estórias de Usuário a partir de gravação de reunião, conforme boas práticas do Scrum. | 2 | [Orientações](Scrum_Criador_de_Estorias_de_Usuario/README.md) |
| [Planejamento de Contratação não-TIC](Validar_Planejamento_Contratacao_nao-TIC/) | Validar quesitos de DFD, ETP, Pesquisa de Preços e TR para contratações em geral. | 15 | [Orientações](Validar_Planejamento_Contratacao_nao-TIC/README.md) |
| [Planejamento de Contratação TIC](Validar_Planejamento_Contratacao_TIC/) | Validar quesitos de DFD, ETP, Pesquisa de Preços e TR para contratações de TIC. | 25 | [Orientações](Validar_Planejamento_Contratacao_TIC/README.md) |
| **Total** |  | **57** |  |

## Como usar

1. Escolha a área de conhecimento, leia as orientações do README.md da pasta correspondente e abra o arquivo `.txt` do caso de uso desejado.
2. Leia o prompt antes de executá-lo.
3. Substitua os marcadores e forneça as entradas solicitadas. Em particular:
	- troque `#xxxxxxxx` pelo protocolo correto do documento ou do processo pertinente, conforme o caso;
	- parceba que alguns prompts se aplicam diretamente ao uso do "Copilot M365" da Microsoft (p. ex. Recapitulação de Reuniões e Scrum Criador de Estórias de Usuário) e demandam colar a URL da opção "Assistir no Navegador" da gravação gerada pelo Teams.
		- Esses prompts podem ser adaptados para uso direto no SEI IA subindo como arquivo avulso a gravação ou a transcrição da reunião.
4. Execute o prompt.
5. Revise o resultado comparando-o com as fontes. A saída da IA é apoio ao trabalho e não substitui análise, validação normativa ou responsabilidade do servidor.

Ao usar os prompts fora do SEI IA, adapte as referências, a forma de anexar ou citar arquivos e os campos de entrada da ferramenta. Preserve, tanto quanto possível, Persona, Contexto, Tarefa/Objetivo, Restrições, Instruções e Formato.

## Cadastro na Galeria do SEI IA

Os arquivos deste repositório podem servir como base para o cadastro na Galeria de Prompts do SEI IA. Para cada cadastro:

1. use a descrição sugerida no `README.md` da pasta correspondente como **Descrição do Prompt**;
2. copie o prompt do arquivo `.txt` do caso de uso correspondente para o campo **Prompt**;

Além de cadastrar os prompts deste acervo, deve ser incentivada a criação de novos prompts a partir das necessidades reais dos servidores do órgão. Prompts bem especificados, testados e compartilhados tornam as capacitações mais práticas e ajudam a formar uma cultura de uso responsável da IA.

## Projetos relacionados

- [mod-sei-ia](https://github.com/anatelgovbr/mod-sei-ia)
- [sei-ia](https://github.com/anatelgovbr/sei-ia)

## Manutenção desse Acervo de Prompts

Novos prompts devem ser apresentados por Pull Request (PR) para este repositório, seguindo as orientações abaixo:

1. Estar na **pasta da área de conhecimento** pertinente;
2. Conter um **arquivo `.txt` do prompt integral**, com um objetivo único.
3. Seguir o modelo de prompt perfeito sempre que possível, incluindo Persona, Contexto, Tarefa/Objetivo, Restrições, Instruções e Formato.
4. Ter um **README.md** na pasta da área de conhecimento, com título da área de conhecimento, finalidade de uso e, para cada prompt disponibilizado, sugestão da "**Descrição do Prompt**" para cadastro na Galeria de Prompts.