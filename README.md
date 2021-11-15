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
  <h4 style="font-family:roboto;">Atribuições do desenvolvedor WEB</h4>
     <p align="justify" style="font-family:roboto;">As atribuições do desenvolvedor front-end estão relacionadas com a programação da interface, a integração da interface com as chamadas de API do back-end, e da interação do usuário com o programa. Ao desenvolver o responsável pelo front-end, tem contato com todas as outras áreas relacionadas a criação do projeto e por isso além de entender um pouco sobre o back-end para realização da integração, é importante também ter conhecimentos de ux/ui para opinar nas ideias de design, que apesar de não ser do escopo do desenvolvedor criar o estilo da interface, é importante que ele possua conhecimentos minímos para opinar de forma realista na criação do projeto. O #VEMPRACASA é um projeto web, e como tal existem inúmeras maneiras de se abordar seu desenvolvimento. Diante das diversas tecnologias existentes, a equipe optou pelo Angular.</p>
 <h4 style="font-family:roboto;">A escolha de tecnologia</h4>
  <p align="justify" style="font-family:roboto;">O #VEMPRACASA é um projeto web, e como tal existem inúmeras maneiras de se abordar seu desenvolvimento. Diante das diversas tecnologias existentes, a equipe optou pela framework Angular. Apesar de existirem outras tecnologias, como VueJS e ReactJS que são outras duas frameworks de frontend com facilitações na criação de projetos web. A escolha da equipe foi fundamentada no conhecimento prévio ao projeto dos integrantes.</p>
  <p align="justify" style="font-family:roboto;">Angular é uma framework de web voltada  para o frontend baseado em TypeScript. Sua primeira versão foi lançada em 2010 e era conhecida como Angular JS, porém em 2016 todo seu código fonte foi reescrito e reformulado passando a ser chamado de Angular 2. O Angular trabalha através de Single-Page Applications (SPA), que é uma aplicação web consumida em uma única página. Quando uma página SPA é acessada pela primeira vez, todas as requisições são processadas em seu carregamento, e a partir dai apenas buscas que possuam especificações serão requisitadas ao servidor. Diferente das aplicações comuns que em qualquer solicitação de atualização de dados ocorre uma nova requisição que processa a busca e retorna os dados solicitados.</p>
  <h4 style="font-family:roboto;">O poder do Angular</h4>
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
  <p align="justify" style="font-family:roboto;"></p>
  ---
   
  <h2 style="font-family:roboto;"> Aprendizados Efetivos :book:</h2>   
  
  ---

</body>
</html>
