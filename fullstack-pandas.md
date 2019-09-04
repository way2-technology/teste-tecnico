# WAY2 - Processo Seletivo (Dev Full Stack)

## O PROBLEMA
 
Escreva um programa do tipo console application em que possamos pesquisar a posição em que uma determinada palavra se encontra em um dado dicionário. 
 
Para deixar as coisas mais divertidas, a única mandeira de se interagir com este dicionário é através de um webservice no seguinte endereço: https://way2dictionary.azurewebsites.net/api/values/{posição}
 
Sendo assim, uma chamada para: 
 
- http://teste.way2.com.br/dic/api/words/0 retorna “Abel”
- http://teste.way2.com.br/dic/api/words/1 retorna “Abelardo” 
- http://teste.way2.com.br/dic/api/words/3929 retorna “cabelo” 
- http://teste.way2.com.br/dic/api/words/40000000000000 retorna 400 Bad Request 
 
É importante saber também que cada vez que você chama este webservice, **morre um panda** ʕ •ᴥ•ʔ
 
Seu algoritmo não deve considerar o tamanho do dicionário mesmo se você o descubra por tentativa e erro. Isto se deve ao fato que você não sabe quando este dicionário vai mudar (aumentar ou diminuir) e seu algoritmo não pode quebrar por isso. 
 
Seu programa deve receber uma palavra como parâmetro de entrada e retornar a posição da palavra informada, alguma mensagem caso a palavra não exista e o número de pandas mortos no processo.
 
## PREMISSAS DO PROJETO 
- Deve ser escrito em c#, console application;
- Deve utilizar .Net Core;
- Deve estar pronto para rodar apenas apertando F5 no Visual Studio ou `dotnet run` no console, e nada mais;
 
## VAMOS AVALIAR 
- Número de pandas mortos
  - nos informe quantos pandas foram sacrificados no processo de pesquisa via mensagem no console (quanto menos, melhor);
- Clareza e qualidade do código;
- Cobertura e qualidade dos testes;

# Let's code!
