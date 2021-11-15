<html>
<body>
  
 <h1 align="center"> API 4º Semestre Banco de Dados</h1>
  
  <p align="center">
 <a href="#-resumo-do-projeto-clipboard"> Resumo do Projeto</a> •
 <a href="#-tecnologias-adotadas-computer">Tecnologias Adotadas</a> •
 <a href="#-contribuições-individuais-dart">Contribuições Individuais</a> •
 <a href="#-aprendizados-efetivos-book">Aprendizados Efetivos</a>
</p>
  
  ---
  
  <h2> Autor :necktie: </h2>
  <table align="center">
   <tr>
    <td align="center"><a href="https://www.linkedin.com/in/mike-barcelos-b4648016a/"><img style="border-radius: 50%;" src="https://github.com/GabrielSG20/API4Sem2021/blob/documentation/images/MikeBarcelos.jfif" width="200px;" alt=""/><br/><b>Mike Barcelos</b></a>
      <br/>
      Web Front-End Developer
     </td>
   </tr>
  </table>

 ---
  
  <h2 style="font-family:roboto;"> Resumo do Projeto :clipboard:</h2>
  
  <p align="justify" style="font-family:roboto;"> :calendar: <b>#VEMPRACASA</b> é uma parceria entre a <a href="https://www.oracle.com/br/index.html">Oracle</a> e a FATEC São José dos Campos com a finalidade de desenvolvimento de um Sistema para realização de agendamentos de eventos nos espaços da Casa Oracle, seguindo as normas vigentes de ocupação por conta da Pandemia do Coronavírus, tendo a possibilidade de priorização de acordo com regras de negócio, facilitando a inscrição e cadastro de convidados e aumentando o controle por parte dos organizadores.</p>
  <p align="justify" style="font-family:roboto;">Nessa documentação será abordado o projeto da visão do desenvolvedor front-end, para mais informações gerais sobre o projeto <a href="https://github.com/GabrielSG20/API4Sem2021">clique aqui</a></p>
  
  ---
  
  <h2 style="font-family:roboto;"> Tecnologias Adotadas :computer:</h2>
  
  * [Java](https://www.java.com/pt_BR/)
  * [Spring Boot](https://spring.io/)
  * [JavaScript](https://www.javascript.com/)
  * [Angular](https://angular.io/)
  * [Oracle SQL Developer](https://www.oracle.com/tools/downloads/sqldev-downloads.html)
  * [Figma](https://www.figma.com/)
  * [Jira](https://vempracasa.atlassian.net/) 
  * [Oracle Cloud](https://www.oracle.com/br/cloud/) 
  * [Heroku](https://www.heroku.com/platform) 
  
  ---
  
  <h2 style="font-family:roboto;"> Contribuições Individuais :dart:</h2>
  <h4 style="font-family:roboto;">AS ATRIBUIÇÕES DO DESENVOLVEDOR WEB</h4>
     <p align="justify" style="font-family:roboto;">As atribuições do desenvolvedor front-end estão relacionadas com a programação da interface, a integração da interface com as chamadas de API do back-end, e da interação do usuário com o programa. Ao desenvolver o responsável pelo front-end, tem contato com todas as outras áreas relacionadas a criação do projeto e por isso além de entender um pouco sobre o back-end para realização da integração, é importante também ter conhecimentos de ux/ui para opinar nas ideias de design, que apesar de não ser do escopo do desenvolvedor criar o estilo da interface, é importante que ele possua conhecimentos minímos para opinar de forma realista na criação do projeto. O #VEMPRACASA é um projeto web, e como tal existem inúmeras maneiras de se abordar seu desenvolvimento. Diante das diversas tecnologias existentes, a equipe optou pelo Angular.</p>
 <h4 style="font-family:roboto;">A ESCOLHA DA TECNOLOGIA</h4>
  <p align="justify" style="font-family:roboto;">O #VEMPRACASA é um projeto web, e como tal existem inúmeras maneiras de se abordar seu desenvolvimento. Diante das diversas tecnologias existentes, a equipe optou pela framework Angular. Apesar de existirem outras tecnologias, como VueJS e ReactJS que são outras duas frameworks de frontend com facilitações na criação de projetos web. A escolha da equipe foi fundamentada no conhecimento prévio ao projeto dos integrantes.</p>
  <p align="justify" style="font-family:roboto;">Angular é uma framework de web voltada  para o frontend baseado em TypeScript. Sua primeira versão foi lançada em 2010 e era conhecida como Angular JS, porém em 2016 todo seu código fonte foi reescrito e reformulado passando a ser chamado de Angular 2. O Angular trabalha através de Single-Page Applications (SPA), que é uma aplicação web consumida em uma única página. Quando uma página SPA é acessada pela primeira vez, todas as requisições são processadas em seu carregamento, e a partir dai apenas buscas que possuam especificações serão requisitadas ao servidor. Diferente das aplicações comuns que em qualquer solicitação de atualização de dados ocorre uma nova requisição que processa a busca e retorna os dados solicitados.</p>
  <h4 style="font-family:roboto;">O PODER DO ANGULAR</h4>
 <p align="justify" style="font-family:roboto;">A arquitetura do Angular é baseada em componentes, que funcionam como blocos de construções são utilizados conforme a necessidade da aplicação. Tal arquitetura permite uma melhor flexibilização na hora de construir uma aplicação, pois facilita na reutilização de código sem a necessidade de reescreve-lo.</p>
 <details>
  <summary>Demonstração da Arquitetura do Angular</summary>
  <br>
   <img style="border-radius: 50%;" src="https://user-images.githubusercontent.com/46934773/141854587-c851f23d-9c30-425b-a06e-ea6f54ce99d1.png" width="200px;" alt=""/>
  </details>
  <p align="justify" style="font-family:roboto;">Como evidenciado pela imagem acima, todo componente dentro do angular possui os arquivos HTML, SCSS e TypeScripts próprios. Dentro do arquivo TypeScript do componente podemos setar configurações  de importação e template. Graças a isso é possível chama-los como uma tag criada dentro de suas configurações que assemelha-se aos elementos HTML dentro do projeto, provando a facilitação na reutilização de código. Assim como um elemento de HTML a tag deve ser aberta e fechada como pode-se ver nas imagens abaixo.</p>
   <details>
  <summary>Importação de componentes dentro do Angular</summary>
  <br>
   <img style="border-radius: 50%;" src="https://user-images.githubusercontent.com/46934773/141857884-9db909e2-c0c3-41bb-b243-c144765ece43.png" alt=""/>
   <img style="border-radius: 50%;" src="https://user-images.githubusercontent.com/46934773/141858109-6f449af6-137c-4c44-9652-5d2e4485fc37.png" alt=""/>
  </details>
  <h4 style="font-family:roboto;">A AUTONOMIA DO FRONT-END</h4>
  <p align="justify" style="font-family:roboto;">Para desenvolver a interface, existem etapas que demandam niveis de autonomia. Por exemplo, é impossível começar a desenvolver uma tela, sem que o design tenha construído ela primeiro. Por conta disso o desenvolvimento do front-end pode ficar travado e se atrasar quanto ao escopo das sprints. Outra entrava que o desenvolvedor front-end pode enfrentar é a falta dos EndPoints para comunicação do back-end com o front-end, dificultando no teste das funcionalidades da tela.</p>
  <p align="justify" style="font-family:roboto;">Após a criação do design, o front-end pode fazer toda parte gráfica, e até tentar construir a lógica para realizar o envio de dados quanto as ações do usuário para o back-end, porém, após esse desenvolvimento, caso os EndPoints ainda não estejam configurados para realizar as ações referentes ao back e ao banco, os testes acabam por ser limitados. Para esses casos o desenvolvedor pode utilizar uma fake API, que simula um banco de dados e suas operações. Nesse projeto fizemos uso do MirageJS para essa finalidade.</p>
  <p align="justify" style="font-family:roboto;">No início do projeto, por conta de todas as tenuâncias envolvendo o banco de dados e a lógica do back-end, a parte referente ao front-end estava parada. Todas as telas da sprint já haviam sido feitas, e agora só era necessário consumir a API e verificar se o envio de dados estava correto. Por isso para realizar os testes e deixar as telas prontas para o consumo da API o MirageJS foi aplicado.</p>
  <p align="justify" style="font-family:roboto;">Através do MirageJS é possível simular a existência de um banco de dados, que pode gerar uma fake API com a finalidade de simular as requisições necessárias para uma tela ou projeto.</p>
  <details>
  <summary>Utilização do MirageJS</summary>
  <br>
   <img style="border-radius: 50%;" src="https://user-images.githubusercontent.com/46934773/141865426-ca844748-9361-4991-a0d8-36a0cefa196c.png" alt=""/>
  </details>
  <p align="justify" style="font-family:roboto;">Como ilustrado na imagem acima, o MirageJS é criado através de um mock onde você pode setar uma lista com dados pré definidos, com permissões para serem manipulados de forma simples, utilizando da criação de métodos próprios da API do Mirage.</p>
  <details>
  <summary>Implementação do MirageJS</summary>
  <br>
   Arquivo de serviços do aplicativo:
   <img style="border-radius: 50%;" src="https://user-images.githubusercontent.com/46934773/141866862-f4027997-8207-4381-a55c-f22c40a4d8a0.png" alt=""/>
    <br>
   Inicialização do MirageJS através de um componente do Angular:
   <img style="border-radius: 50%;" src="https://user-images.githubusercontent.com/46934773/141867186-3496e3a7-a104-45a4-a5b6-1e6fca5e4729.png" alt=""/>
  </details>
  <p align="justify" style="font-family:roboto;">Pode-se observar, que no arquivo de serviços do aplicativo, a configuração é a mesma seja para uma API verdadeira ou para o MirageJS, a única diferença é a chamada da URL. E para que a fake API funcione, no componente que será feito as requisições é necessário realizar a chamada do MirageJS, como ocorre na segunda imagem. É importante lembrar que ao sair de uma tela para outra, é necessário fechar a requisição do Mirage para evitar conflitos de requisições em outros componentes como é feito com as requisições reais.</p>
  <h4 style="font-family:roboto;">OS COMPONENTES DO PROJETO</h4>
  <p align="justify" style="font-family:roboto;">A lista de componentes do projeto #VEMPRACASA é extensa, e vai desde os mais simples como por exemplo as telas de login e cadastro, os menus superior e lateral e as demais telas. O componente de menu superior, é o que melhor exemplifica a reutilização de código sem a necessidade de redigita-lo, já que é um componente que esta presente em quase todas as telas do projeto.</p>
  
  ---
   
  <h2 style="font-family:roboto;"> Aprendizados Efetivos :book:</h2>   
  
  ---

</body>
</html>
