# Teste Técnico para Full-Stack Developer Place

Muito obrigado por reservar um tempo para fazer nosso teste técnico. Ele consiste em duas partes:

- Um teste técnico, dividido em Back-End e Front-End (código)
- Algumas perguntas técnicas

Complete ambos e crie um arquivo zip com todo o conteúdo. Pegue este arquivo e dê upload para um local compartilhado como Google Drive, One Drive e nos forneça um link privado de acesso. Caso não seja possível, compartilhe o local com a pessoa responsável da Way2 que lhe atribuiu o teste. Por favor, não divulgue seu teste em outros canais.  **Não dê fork neste repositório para apresentar sua solução.**

O arquivo zip deve ser  **único** , nomeado como  **{seu nome}-{nome da vaga}.zip**  e deve conter:

1. Um arquivo único de markdown com as respostas para as perguntas técnicas
2. Um único diretório contendo o teste técnico

**Teste Técnico (Back-End)**

Para o teste técnico, deve-se criar uma API (Web App) com as seguintes premissas:

- Um agendamento interno deve acessar a API do OpenWeather ([https://openweathermap.org/api](https://openweathermap.org/api)) a cada 15 minutos;
- As informações a serem recuperadas da API do OpenWeather são os valores das temperaturas das capitais passadas por parâmetros (Ex: Porto Alegre, Florianópolis e Curitiba);
- Uma vez que os dados forem lidos, estes devem ser armazenados (em memória ou no disco);
- Dentro do Web App, uma API em REST deve ser disponibilizada para a consulta dos dados de temperatura armazenados;
- A API deve permitir a consulta passando os seguintes parâmetros obrigatórios: Nome da cidade, Data de Início e Data de Fim;

- **Teste Técnico (Front-End)**

Crie uma [single page application](https://en.wikipedia.org/wiki/Single-page_application) que consulte a (Web App) e aceite Nome da(s) cidade(s), Data de Início e Data de Fim e apresente uma lista em forma de tabela com os dados de temperatura das cidades em questão.

**Plataforma**

**Back-End**

A API deve estar pronta para rodar em qualquer plataforma e  **em uma máquina com somente dotnet instalado** , com o comando dotnet run e nada mais.

Pontos extras se entregar o projeto dentro de algum container!!

**Front-End**

O site deve estar pronto para rodar em qualquer plataforma e **em uma máquina com somente um web server instalado (iis, node, apache, etc).**

**Requisitos**

- Por favor, complete a user story abaixo
- Seu código deve estar pronto para rodar

**Back-End**

- O código deve usar C# em um projeto ASP NET Core
- Você  **deve**  incluir testes de unidade
- Tome cuidado com segurança, resiliência e velocidade
- Tente não incluir artefatos de seu build local (se utilizar build), como por exemplo, as bin, debug ou similar.

**Front-End**

- Deve ser utilizado o Angular na última versão como framework javascript
- Você  **deve**  incluir testes de unidade
- Tente não incluir artefatos de seu build local (se utilizar build), como por exemplo, a pasta node\_modules.

**Critérios de avaliação**

A qualidade da solução é fundamental, assim será levado em consideração na hora de avaliar as provas:

- Legibilidade do código entregue: a way2 privilegia uma cultura de **Clean Code**
- Adoção de boas práticas do padrão Restful
- Qualidade dos testes, praticamos TDD, portanto consideramos esse item fundamental para a aprovação do candidato
- Arquitetura da solução: isolamento das camadas, injeção de dependências, etc..

**User Story**

**Back-End**

Como um usuário consumidor da API
 Eu posso chamar a API, passando a(s) cidade(s) e um range de datas
 Então receberei todas os registros de temperatura desse período e das cidades escolhidas

**Front-End**

Como um usuário utilizando a aplicação
 Eu posso ver a temperatura das cidades escolhidas e um range de datas
 Então mostrarei na tela uma tabela com os registros de temperatura desse período e das cidades escolhidas

**Aceite**

**Back-End**

- Para as cidades passadas por parâmetros, as informações de temperatura, junto com a data/hora da coleta são mostradas
- O tempo entre cada coleta é de 15 minutos (aproximadamente)

**Front-End**

- Para as cidades passadas por parâmetros, as informações de temperatura, junto com a data/hora da coleta são mostradas na tela em forma de tabela
- Os campos de nome da cidade e temperatura são informados para cada cidade.

**Anotações finais**

Sinta-se a bondade de inovar, a gente aprecia muito inovação, pode sair da caixa sem problemas e mostrar mais o que você sabe fazer para a gente ;)

**Perguntas Técnicas**

Por favor, responda estas perguntas em um arquivo markdown chamado PerguntasTecnicas.md e coloque dentro do .zip entregue.

1. Quanto tempo você usou para completar a solução apresentada? O que você faria se tivesse mais tempo?
2. Quais librarias utilizou para complementar sua implementação e qual foi o motivo de ter usado estas? Caso contrário, por que não utilizou nenhum?
3. Liste alguns frameworks javascript e nos diga em quais situações seria melhor utilizar cada um deles.
4. Descreva você mesmo utilizando json.

Muito obrigado!
