# Testes de Font End - SENAI (UC11)
<h2 align="esquerda">:dart:OBJETIVO</h2>
Testar o site desenvolvido na Unidade de Codificação Front-End (E-Players), aplicando correções de acordo com os resultados.
<h2 align="esquerda">:white_check_mark:ELEMENTOS QUE SERÃO TESTADOS</h2>
Os testes que serão realizados na plataforma E-Players serão os testes de navegabilidade, verificando a interação do usuário com a plataforma, conforme descrito abaixo:
<p align="esquerda">:point_right: Na página de login da plataforma deve-se interagir com o campo usuário e senha; utilizando vários e-mails e diferentes senhas com apenas um deles correspondendo a um usuário cadastrado, verificando todos os retornos da tentativa de login;</p>
<p align="esquerda">:point_right:Verificar se todas as mensagens de falha de login estão sendo exibidas corretamente e se estão correspondentes com cada caso de falha;</p>
<p align="esquerda">:point_right:Verificar se o usuário está sendo encaminhado para a página Inicial quando ele estiver realizando o login de forma correta.</p>

<h2 align="esquerda">:wrench:FERRAMENTAS</h2>
Para realizar os testes trabalharemos com um conjunto de ferramentas chamado *SELENIUM*, será necessário baixar as ferramentas **Eclipse**, **JDK8**, **Apache Maven** e **WebDriver**.
<h2 align="esquerda">RESULTADO DOS TESTES</h2>
Inicialmente foi criado uma nova pasta chamada **testemania** dentro da pasta **eclipse-workspace**, ao abrir o Eclipse, foi realizado a inserção das dependências do *Selenium e Junit* dentro do arquivo **teste mania/pom.xml**. Dentro da pasta **testemania** foi criado uma *class* chamado **testesenhas.java**, dentro dessa *class* foram realizados os *testes* na funcionalidade do *Login*, observando se surgia mensagens de erro ao realizar o login.
Diante dos testes realizado foi possível atestar que todas as funcionalidade do Login e eventos da interface estão se comportando devidamente.

