# Criador de Recapitulação de Reunião gravada pelo Teams

> Criar recapitulação estruturada das discussões e lista de ações com responsáveis a partir de uma transcrição ou gravação.

Escolha a descrição correspondente à forma de fornecimento da fonte:

Sugestão de "Descrição do Prompt" para cadastro na Galeria de Prompts:

```text
Recapitulação de Reunião gravada pelo Teams - Anexando arquivo de transcrição
>>> No SEI IA, anexe o arquivo que contém a transcrição completa da reunião.
>>> Use esta versão quando a fonte estiver disponível em um arquivo anexado.
```

```text
Recapitulação de Reunião gravada pelo Teams - Colando transcrição
>>> Cole a transcrição entre as tags <transcricao_reuniao> e </transcricao_reuniao>.
>>> Use esta versão quando a fonte estiver disponível como texto.
```

```text
Copilot M365/Teams: Recapitulação de Reunião gravada pelo Teams - Colando URL "Assistir no Navegador"
>>> Cole no campo indicado do prompt a URL da opção "Assistir no Navegador" da gravação da reunião pelo Teams.
>>> Use esta versão quando a gravação estiver disponível para a conta com as permissões necessárias.
```

Orientações comuns às três versões:

- A resposta deve começar com **Data da Reunião:** e a data de hoje no formato dd/mm/aaaa.
- A resposta deve conter somente as seções **# Recapitulação da Reunião** e **# Lista de Ações da Reunião**.
- Organize o conteúdo em blocos temáticos em negrito e subitens isolados em linhas iniciadas por `*   `, mantendo a ordem da fonte.
- Escreva cada subitem de forma curta, direta e independente, com no máximo um período.
- Destaque em **negrito** o responsável por cada ação identificada.
- Baseie-se exclusivamente no conteúdo fornecido e não inclua referência à transcrição, à gravação, ao arquivo ou à URL na resposta.
- Aplique linguagem clara, objetiva, acessível e impessoal, evitando parágrafos extensos, jargões desnecessários e transições entre subitens.