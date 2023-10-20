# Funcionalidades do Sistema (Telas)

Nesta seção são apresentadas as telas desenvolvidas para cada uma das funcionalidades do sistema.
<br>
<br>
## Home-Page (RF-001)

A tela principal do sistema apresenta apresenta a logo, menu principal, conteúdo e rodapé. Um exemplo da tela é apresentada na figura abaixo. <a href="https://icei-puc-minas-pmv-ads.github.io/PMV-ADS-2023-1-E1-PROJ-WEB-T11-Time2-CONCRETIZE/index.html">Acesse a página online clicando aqui.</a>

<img src="https://i.imgur.com/JMVabAv.jpg" width="50%">

### Requisitos atendidos
RF-001 - O site deve permitir que o usuário visualize na página inicial, a logo e o menu principal. O menu deve conter categorias como: cadastro/login, como funciona, quem somos, suporte, solicite um orçamento e blog. O usuário também deve conseguir visualizar ao longo da página principal, a apresentação do propósito da empresa, provas sociais, chamada para ação (cadastro na plataforma), assinatura de newsletter e rodapé.
<br>
<br>
## Solicitação de Serviços (RF-002)

A tela de solicitação de serviços apresenta um formulário para solicitar orçamentos aos profissionais. Um exemplo da tela é apresentada na figura abaixo. <a href="https://icei-puc-minas-pmv-ads.github.io/PMV-ADS-2023-1-E1-PROJ-WEB-T11-Time2-CONCRETIZE/src/solicitacao-servico.html">Acesse a página online clicando aqui.</a>

<img src="https://i.imgur.com/RxSupsG.png" width="50%">

### Requisitos atendidos
RF-007	O site deve ter uma funcionalidade que permita o cliente entrar em contato com o profissional dentro do próprio site, para solicitar orçamentos e tirar dúvidas, sem a necessidade de uma ferramenta externa.
<br>
<br>
## Serviços Solicitados (RF-003)

A tela de Serviços Solicitados apresenta um histórico de solicitações em andamento, separando-as por áreas (Pintor, Pedreiro, Gesseiro). Um exemplo da tela é apresentada na figura abaixo. <a href="https://icei-puc-minas-pmv-ads.github.io/PMV-ADS-2023-1-E1-PROJ-WEB-T11-Time2-CONCRETIZE/src/servicos-solicitados.html">Acesse a página online clicando aqui.</a>

<img src="https://i.imgur.com/C9Xj4iI.png" width="50%">

### Requisitos atendidos
RF-003	O site deve oferecer cards que permitam ao cliente visualizar os orçamentos de profissionais que mostraram interesse no serviço, separando-os por suas respectivas categorias.
<br>
<br>
## Serviços Solicitados - Detalhes (RF-004)

A tela de Serviços Solicitados - Detalhes, deve apresentar cards adicionais que permitam ao cliente visualizar os orçamentos de profissionais que mostraram interesse no serviço, contendo os dados do profissional, descrição do serviço e valor. Um exemplo da tela é apresentada na figura abaixo. <a href="https://icei-puc-minas-pmv-ads.github.io/PMV-ADS-2023-1-E1-PROJ-WEB-T11-Time2-CONCRETIZE/src/orcamentos.html">Acesse a página online clicando aqui.</a>

<img src="https://i.imgur.com/snImUNz.png" width="50%">

### Requisitos atendidos
RF-004	O site deve oferecer cards adicionais que permitam ao cliente visualizar os orçamentos de profissionais que mostraram interesse no serviço, contendo os dados do profissional, descrição do serviço e valor.
<br>
<br>
## Exibição de Informações do Profissional e Contato no Card de Orçamento (RF-005)

A tela deve permitir que o cliente acesse informações detalhadas fornecidas pelos profissionais através de um modal que será exibido ao clicar em "Detalhes" que está presente em cada card dos profissionais que responderem as solicitações.

<img src="https://i.imgur.com/OayCM85.png" width="50%">

### Requisitos atendidos
RF-005	O site deve fornecer para o cliente, através do card que mostrará o orçamento enviado pelo profissional, as informações do profissional em questão. Dessa forma, o cliente poderá entrar em contato com o profissional escolhido e acertar os detalhes restantes por conta própria, seja por número de celular ou email.
<br>
<br>
## Página de perfil do profissional (RF-006)

A tela de perfil do profissional deve apresentar ao cliente informações como nome, avaliações, portfólio, bio e as categorias nas quais o profissional atua.

<img src="https://i.imgur.com/tJbEepI.png" width="50%">

### Requisitos atendidos
RF-006	O site deve permitir que o cliente visualize a página do profissional.
<br>
<br>
## Página de painel do profissional (RF-007)

A tela de painel do profissional deve apresentar orçamentos enviandos pelo profissional em respota à solicitação de orçamento dos clientes.

<img src="https://i.imgur.com/43fTfiY.png" width="50%">

### Requisitos atendidos
RF-007	O site deve permitir que o profissional acesse uma página, onde poderá visualizar os orçamentos que já enviou e as solicitações de serviços que correspondem com sua categoria de atuação e localização.
<br>
<br>
## Página de resposta de orçamento (RF-008)

A tela de resposta de orçamento deve apresentar ao profissional campos para inserir o valor, prazo e detalhes da solicitação dos clientes.

<img src="https://i.imgur.com/Sv9Cd1r.png" width="50%">

### Requisitos atendidos
RF-008	O site deve permitir que o profissional envie um orçamento, caso esteja interessado, para as solicitações de serviços que correspondam com sua categoria de atuação e localização.

<!--
<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Especificação do Projeto</a></span>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>, <a href="4-Metodologia.md"> Metodologia</a>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>, <a href="5-Arquitetura da Solução.md"> Arquitetura da Solução</a>

Implementação do sistema descritas por meio dos requisitos funcionais e/ou não funcionais. Deve relacionar os requisitos atendidos os artefatos criados (código fonte) além das estruturas de dados utilizadas e as instruções para acesso e verificação da implementação que deve estar funcional no ambiente de hospedagem.

Para cada requisito funcional, pode ser entregue um artefato desse tipo

> **Links Úteis**:
>
> - [Trabalhando com HTML5 Local Storage e JSON](https://www.devmedia.com.br/trabalhando-com-html5-local-storage-e-json/29045)
> - [JSON Tutorial](https://www.w3resource.com/JSON)
> - [JSON Data Set Sample](https://opensource.adobe.com/Spry/samples/data_region/JSONDataSetSample.html)
> - [JSON - Introduction (W3Schools)](https://www.w3schools.com/js/js_json_intro.asp)
> - [JSON Tutorial (TutorialsPoint)](https://www.tutorialspoint.com/json/index.htm)
-->
