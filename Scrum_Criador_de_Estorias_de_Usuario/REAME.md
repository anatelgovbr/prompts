# Criador de Estórias de Usuário para desenvolvimento de sistema a partir de reunião gravada pelo Teams

> Analisar a gravação de uma reunião e transformar decisões confirmadas em Estórias de Usuário preparadas para refinamento, seguindo boas práticas do Scrum.

Há duas versões do prompt, configuradas para sistemas diferentes:

Sugestão de "Descrição do Prompt" para cadastro na Galeria de Prompts:

```text
Copilot M365/Teams: Criar Estórias de Usuário a partir de reunião de levantamento - Sistema Ana
>>> Cole na última linha do prompt a URL da opção "Assistir no Navegador" da gravação da reunião pelo Teams.
>>> Use esta versão para o Sistema de Gestão de Conteúdo e Monitoramento da Ana (Ana).
>>> Para outro sistema, altere as seções "Informações sobre o 'Sistema'" e "Denominações dos Papéis de Usuário" antes de executar o prompt.
```

```text
Copilot M365/Teams: Criar Estórias de Usuário a partir de reunião de levantamento - Sistema SEI
>>> Cole na última linha do prompt a URL da opção "Assistir no Navegador" da gravação da reunião pelo Teams.
>>> Use esta versão para o Sistema Eletrônico de Informações (SEI) e os papéis de usuário configurados para ele.
```

Orientações comuns às duas versões:

- Analise toda a gravação antes de gerar as Estórias e crie Estórias somente para decisões finais que gerem trabalho.
- Separe dúvidas, conflitos, lacunas e decisões pendentes na seção **# Pendências para Esclarecimento**, quando houver.
- Use somente os papéis de usuário definidos na seção **Sistema e Papéis de Usuário** da versão escolhida.
- Elabore Estórias com título específico, benefício claro, critérios de aceitação objetivos e verificáveis, requisitos não funcionais, evidências para futura estimativa SPP e dependências quando aplicáveis.
- Aplique os princípios INVEST sempre que possível e crie pelo menos três Critérios de Aceitação quando houver conteúdo suficiente.
- Não invente funcionalidades, regras, papéis, permissões, critérios, riscos, dependências ou outros dados ausentes da gravação.
- Não calcule, sugira ou infira SPP ou Story Points.
- Não inclua na resposta a URL, timestamps, nomes de participantes, título da reunião, transcrição de falas ou referências à gravação.