# Teste Técnico para Back-End Developer

Muito obrigado por reservar um tempo para fazer nosso teste técnico. Ele consiste de 2 partes:

 - Um teste técnico (código)
 - Algumas perguntas técnicas
 
Complete ambos e crie um arquivo zip com todo o conteúdo. Pegue este arquivo e dê upload para um local compartilhado como Google Drive, One Drive e nos forneça um link privado de acesso. Caso não seja possível, compartilhe o local com a pessoa responsável da Way2 que lhe atribuiu o teste. Por favor, não divulgue seu teste em outros canais. **Não dê fork neste repositório para apresentar sua solução.**

O arquivo zip deve ser **único**, nomeado como **{seu nome}-{nome da vaga}.zip** e deve conter:

1. Um arquivo único de markdown com as respostas para as perguntas técnicas
2. Um único diretório contendo o teste técnico

## Teste Técnico

Para o teste técnico, deve-se criar uma api .net core (visando a arquitetura de microserviços) com as seguintes premissas: 
* Um agendamento interno deve acessar a API do OpenWeather (https://openweathermap.org/api) a cada 15 minutos;
* As informações a serem recuperadas da API do OpenWeather são os valores das temperaturas das seguintes capitais: Porto Alegre, Florianópolis e Curitiba;
* Uma vez que os dados forem lidos, estes devem ser armazenados (em memória ou no disco);
* Dentro do Web App, uma API em REST deve ser disponibilizada para a consulta dos dados de temperatura armazenados;
* A API deve permitir a consulta passando os seguintes parâmetros obrigatórios: Nome da(s) cidade(s), Data de Início e Data de Fim;

### Plataforma

A API deve estar pronta para rodar em qualquer plataforma e **em uma máquina com somente dotnet instalado**, com o comando `dotnet run` e nada mais. 

Ganha pontos quando: 
- Usa alguma tecnologia de containerização (docker, docker-compose, k8s)
- Entrega o teste publicado em alguma cloud utilizando pipelines de CI/CD (Podemos combinar um periodo em que a aplicação estará online, favor comunicar).

### Requisitos

- Por favor, complete a user story abaixo
- Seu código deve estar pronto para rodar
- O código deve usar C# em um projeto ASP NET Core 
- Você **deve** incluir testes de unidade (Pirâmide de Testes)
- Tome cuidado com segurança, resiliência e velocidade
- Tente não incluir artefatos de seu build local (se utilizar build), como por exemplo, as bin, debug ou similar.

### Critérios de avaliação 
A qualidade da solução é fundamental, assim será levado em consideração na hora de avaliar as provas:
- Legibilidade do codigo entregue: a way2 privilegia uma cultura de Clean code
- Qualidade dos testes, praticamos TDD, portanto consideramos esse item fundamental para a aprovação do candidato
- Performance da aplicação.
- Arquitetura da solução: isolamento das camadas, injeção de dependencias, POO, SOLID etc..

### User Story
 Como um usuário consumidor da API <br />
 Eu posso chamar a API, passando a(s) cidade(s) e um range de datas<br />
 Então receberei todas os registros de temperatura desse período e das cidades escolhidas<br />

#### Aceite
- Para as cidades de Curitiba, Florianópolis e Porto Alegre, as informações de temperatura, junto com a data/hora da coleta são mostradas
- O tempo entre cada coleta é de 15 minutos (aproximadamente)

## Perguntas Técnicas

Por favor, responda estas perguntas em um arquivo markdown chamado `PerguntasTecnicas.md` e coloque dentro do .zip entregue.

1. Quanto tempo você usou para completar a solução apresentada? O que você faria se tivesse mais tempo?
2. Se usou algum framework, qual foi o motivo de ter usado este? Caso contrário, por que não utilizou nenhum?
3. Quais as métricas que você observaria nessa aplicação caso estivesse em produção com o cenário de "missão crítica"? 
4. Descreva você mesmo utilizando json.

Muito obrigado!
