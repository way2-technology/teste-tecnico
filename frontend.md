# Teste Técnico para Front-End Developer

Muito obrigado por reservar um tempo para fazer nosso teste técnico. Ele consiste de 2 partes:

 - Um teste técnico (código)
 - Algumas perguntas técnicas
 
Complete ambos e crie um arquivo zip com todo o conteúdo. Pegue este arquivo e dê upload para um local compartilhado como Google Drive, One Drive e nos forneça um link privado de acesso. Caso não seja possível, compartilhe o local com a pessoa responsável da Way2 que lhe atribuiu o teste. Por favor, não divulgue seu teste em outros canais. Não dê fork neste repositório para apresentar sua solução.

O arquivo zip deve ser **único**, nomeado como **{seu nome}-{nome da vaga}.zip** e deve conter:

1. Um arquivo único de markdown com as respostas para as perguntas técnicas
2. Um único diretório contendo o teste técnico

## Teste Técnico

Para o teste técnico, vamos utilizar a V2 da API pública chamada <a href="https://www.football-data.org" target="_blank">football-data.org</a>.

Crie uma [single page application](https://en.wikipedia.org/wiki/Single-page_application) que aceite um código de competição (Ex: 2013 = Campeonato Brasileiro série A) e apresente uma lista com o ranking da mesma. A lista deve conter:

- posição no ranking (atual ou final, caso o campeonato já tenha acabado)
- nome do time
- vitórias
- empates
- derrotas
- pontos

### Plataforma

O site deve estar pronto para rodar em qualquer plataforma e **em uma máquina com somente um web server instalado (iis, node, apache, etc).**

### Requisitos

- Por favor, complete a user story abaixo
- Seu código deve estar pronto para rodar
- Sinta-se a vontade para usar qualquer framework se achar necessário
- Você **deve** incluir testes de unidade
- Tente não incluir artefatos de seu build local (se utilizar build), como por exemplo, a pasta node_modules.

### User Story

 Como um **usuário utilizando a aplicação** <br />
 Eu posso ver **o ranking de um campeonato enviando seu código (Ex: 2013)**<br />
 Então eu sei quais **times estão ou finalizaram na frente**<br />

#### Aceite
- Para o código 2013, o ranking do campeonato Brasileiro é mostrado
- Os campos de posição, nome do time, vitórias, empates, derrotas e pontos são informados para cada time.

## Perguntas Técnicas

Por favor, responda estas perguntas em um arquivo markdown chamado `PerguntasTecnicas.md` e coloque dentro do .zip entregue.

1. Quanto tempo você usou para completar a solução apresentada? O que você faria se tivesse mais tempo?
2. Se usou algum framework javascript, qual foi o motivo de ter usado este? Caso contrário, por que não utilizou nenhum?
3. Liste alguns frameworks javascript e nos diga em quais situações seria melhor utilizar cada um deles.
4. Descreva você mesmo utilizando json.

Muito obrigado!
