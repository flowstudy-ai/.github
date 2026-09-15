# FlowStudy

Aqui fica o que a gente testou usando o [Hermes Agent](https://hermes-agent.nousresearch.com/docs/) e decidiu guardar porque funcionou.

Não é outro Hermes, não é curso e não é coleção de promessa bonita. São peças pequenas, com código aberto, limite explicado e um jeito claro de testar.

Se funciona, entra. Se é só ideia com maquiagem, fica de fora.

## O que tem aqui

Publicamos dois tipos de coisa: **kits** e **receitas**.

### Kits

Kit mexe na instalação do Hermes para resolver um problema específico. Por isso precisa ter diagnóstico, teste sem estragar nada e caminho para desfazer.

- [**Knowledge**](https://github.com/flowstudy-ai/hermes-knowledge-kit) organiza seus arquivos Markdown para o agente encontrar decisões, projetos e referências sem sair cavando pasta no escuro.
- [**Oracle**](https://github.com/flowstudy-ai/hermes-oracle-kit) mantém uma cópia pesquisável da documentação do Hermes. Quando o agente tiver dúvida sobre o próprio sistema, consulta a fonte antes de inventar moda.

### Receitas

Receita não instala serviço nem conecta conta. É uma skill com instruções para o agente executar bem uma tarefa repetível.

- [**Briefing de grupos WhatsApp**](https://github.com/flowstudy-ai/hermes-recipes/tree/main/whatsapp-briefing) transforma as mensagens já coletadas dos grupos em um único resumo diário, curto e legível. Não conecta o WhatsApp e não lê conta alheia.
- [**Escada de pesquisa web**](https://github.com/flowstudy-ai/hermes-recipes/tree/main/web-research-ladder) ensina o agente a pesquisar sem torrar crédito: busca gratuita primeiro, extração só na página escolhida e arquivo ou browser quando houver bloqueio.
- [**Ver todas as receitas**](https://github.com/flowstudy-ai/hermes-recipes) abre o catálogo completo.

## Como usar

1. Escolha o problema que você quer resolver.
2. Abra o repositório e leia primeiro o que ele **não faz**.
3. Se for kit, rode o diagnóstico e o dry-run antes de instalar.
4. Se for receita, copie a skill e ajuste somente a configuração local necessária.
5. Teste no seu ambiente antes de confiar trabalho importante à peça.

Sem botão mágico. Se alguma etapa depende de chave, QR, conta ou decisão humana, o README precisa dizer isso sem enrolação.

## O que precisa acontecer antes de entrar aqui

- Foi usado de verdade, não apenas imaginado.
- Tem instrução em português claro.
- Não leva senha, conversa ou dado privado para o Git.
- Explica os limites sem esconder a parte chata.
- Tem uma forma concreta de verificar se funcionou.
- Se altera a instalação, também explica como desfazer.

A régua é simples: **prova antes de propaganda**.

## Independência

A FlowStudy é um projeto independente. O Hermes Agent é desenvolvido pela [Nous Research](https://nousresearch.com/).
