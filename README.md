## <center>Arquitetura do Projeto</center>
<h3><center> Java + Karate Framework API </center></h3>

---------------------------------------------------
<h3> Características: </h3>

- Linguagem de desenvolvimento - Java

- Versão do Java - 8

- Ambiente de desenvolvimento - Intellij Community

- Orquestrador de testes - JUnit 5

- Gerenciamento de dependência - Maven

- Relatório de testes automatizados - Relatório nativo do Karate Framework

- Framework integração com API - Karate Framework


---------------------------------------------------
<h3> O que é Karate Framework: </h3>
Karate Framework é uma ferramenta open source para testes de API, mocks, performance e até mesmo interface.

Sua principal caracterísca está baseada na sua simplicidade de escrita. Onde pessoas sem grande conhecimento em linguagem 
ou lógica de programção conseguem desenvolver um script sem grandes dificuldades.

A sintaxe utilizada pelo Karate é semelhante ao Gherkin e os testes são implementados dentro de um arquivo .feature e 
executados por um Runner.

Apesar de ser baseado no Gherkin, os cenários descritos seguem uma abordagem mais imperativa, ou seja, descrevem como 
as requisições são feitas e não o que ela faz. Em outras palavras, a linguagem utilizada nas features acaba sendo muito 
mais técnica do que de negócio.

No projeto da Base2, estamos focando no Karate para testes de API.


---------------------------------------------------
<h3> Treinamento: </h3>

Acompanhe o treinamento do Karate Framework na nossa Base de Conhecimento:

  - [Treinamento Karate Framework](https://docs.google.com/presentation/d/1NNiceW5UJCchvQuzSgcq9Yl77mDAFWQmiApnIryyv7k/edit#slide=id.g109fb20fb61_1_126)

O que vamos aprender:

- Conceitos Básicos:

  - O que é Karate Framework.
  - Materiais complementares Karate Framework.
  - Setup do ambiente.
  - Estrtutura do projeto.
  - Entendendo as features.
  - Escrevendo uma feature básica.
  - Entendendo os Runners.
  
    - Runners do Karate.
    - Runners do JUnit.
  - Relatório.
  - Entendendo karate-config.js.


- Conceitos Avançados:

  - Lendo arquivos Jsons.
  - Construindo Scnarios Outline.
  - Chamando outros Scenarios (obtendo token).
  - Executando funções JavaScript.
  - Extraindo dados com JsonPath.
  - Validações com Matcher.
  - Execução por linha de comando maven.
  

- Particularidades do Template Base2:

  - Conexão com banco de dados.

    -Utilização nas features.

    -Execução de queries.
  
  - Utils
  
    - Chamada de métodos dentro das features.

---------------------------------------------------
<h3> API de teste: </h3>

No diretório raiz do projeto existe um arquivo 
"createEnviroment.bat" que irá construir uma API em Java 11
Essa API foi a base para a construção dos cenários do template. 
