# Plano de Testes de Software

Nesta seção são apresentados os planos de teste de software.
<br>
<br>
<table style="border-collapse: collapse;">
  <tr>
    <th style="border: 1px solid white; padding: 10px;">Caso de teste</th>
    <td style="border: 1px solid black; padding: 10px;">CT-01: Visualização da home</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Requisitos</th>
   <td style="border: 1px solid black; padding: 10px;">RF-01: o site deve permitir que o usuário visualize na página inicial, a logo e o menu principal. Inicialmente, o menu principal deve permitir que o usuário acesse as seguintes páginas: home, solicitação de serviços, serviços solicitados, painel do profissional e meu perfil (as duas últimas opções estão disponíveis apenas para profissionais). O usuário também deve conseguir visualizar ao longo da página principal, a apresentação do propósito da empresa, chamada para ação, provas sociais e rodapé.</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Objetivo de teste</th>
   <td style="border: 1px solid black; padding: 10px;">Verificar se os botões presentes na home estão redirecionando para página correta</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Passos</th>
   <td style="border: 1px solid black; padding: 10px;">1- Acessar o navegador<br>2- Acessar a home do site (https://icei-puc-minas-pmv-ads.github.io/PMV-ADS-2023-1-E1-PROJ-WEB-T11-Time2-CONCRETIZE/index.html)<br>3- Clicar em todos os botões da página e verificar se está direcionando para a página correta</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Critérios de êxito</th>
   <td style="border: 1px solid black; padding: 10px;">- Ao selecionar qualquer categoria presente na barra de busca e clicar no botão de lupa, o usuário deve ser redirecionado para a página de "Solicite um serviço"<br>- Ao clicar nos botões presentes na seção de "Principais categorias", o usuário deve ser redirecionado para a página de "Solicite um serviço" (https://icei-puc-minas-pmv-ads.github.io/PMV-ADS-2023-1-E1-PROJ-WEB-T11-Time2-CONCRETIZE/src/solicitacao-servico.html)</td>
  </tr>
</table>
<br>
<br>
<table style="border-collapse: collapse;">
  <tr>
    <th style="border: 1px solid white; padding: 10px;">Caso de teste</th>
    <td style="border: 1px solid black; padding: 10px;">CT-02 - Solicitação de serviço</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Requisitos</th>
   <td style="border: 1px solid black; padding: 10px;">RF-02 - O site deve permitir que o cliente solicite um serviço através de um formulário.</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Objetivo de teste</th>
   <td style="border: 1px solid black; padding: 10px;">Verificar se o preenchimento da solicitação está acontecendo corretamente.</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Passos</th>
   <td style="border: 1px solid black; padding: 10px;">1) Preencher o título da solicitação;<br>2) Selecionar a categoria do profissional;<br>3) Preencher o endereço corretamente;<br>4) Inserir detalhes mais relevantes sobre o serviço a ser solicitado. </td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Critérios de êxito</th>
   <td style="border: 1px solid black; padding: 10px;">* Ser obrigatório o preenchimento de todos os campos;<br>* Dropdown exibir todas as categorias disponíveis;</td>
  </tr>
</table>
<br>
<br>
<table style="border-collapse: collapse;">
  <tr>
    <th style="border: 1px solid white; padding: 10px;">Caso de teste</th>
    <td style="border: 1px solid black; padding: 10px;">CT-03 - Serviços Solicitados</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Requisitos</th>
   <td style="border: 1px solid black; padding: 10px;">RF-03 - O site deve permitir que o cliente acesse uma lista com os serviços que solicitou.</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Objetivo de teste</th>
   <td style="border: 1px solid black; padding: 10px;">Redirecionar para o orçamento.</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Passos</th>
   <td style="border: 1px solid black; padding: 10px;">1) Ver orçamentos enviados;<br>2) Clicar no orçamento para visualizar.</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Critérios de êxito</th>
   <td style="border: 1px solid black; padding: 10px;">*Redirecionar para o orçamento.</td>
  </tr>
</table>
<br>
<br>
<table style="border-collapse: collapse;">
  <tr>
    <th style="border: 1px solid white; padding: 10px;">Caso de teste</th>
    <td style="border: 1px solid black; padding: 10px;">CT-004: Serviços solicitados - detalhes</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Requisitos</th>
   <td style="border: 1px solid black; padding: 10px;">RF-004: A tela deverá exibir os orçamentos enviados pelos profissionais ao cliente com base na categoria de serviços solicitados.</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Objetivo de teste</th>
   <td style="border: 1px solid black; padding: 10px;">Apresentar cards individuais contendo as informações de orçamento de cada profissional, apresentando nome, preço, prazo e um botão de detalhes.</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Passos</th>
   <td style="border: 1px solid black; padding: 10px;">1)Acessar “Meu Painel” a partir da home;<br> 2) Clicar em “Serviços Solicitados";<br> 3) Escolher uma das categorias na qual foi solicitado um orçamento.</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Critérios de êxito</th>
   <td style="border: 1px solid black; padding: 10px;">* Os cards devem exibir informações individuais de cada profissional, como nome, preço e prazo.</td>
  </tr>
</table>
<br>
<br>
<table style="border-collapse: collapse;">
  <tr>
    <th style="border: 1px solid white; padding: 10px;">Caso de teste</th>
    <td style="border: 1px solid black; padding: 10px;">CT-005 - Exibição de Informações do Profissional e Contato no Card de Orçamento</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Requisitos</th>
   <td style="border: 1px solid black; padding: 10px;">RF-005 - O site deve fornecer para o cliente, através do card que mostrará o orçamento enviado pelo profissional, as informações do profissional em questão. Dessa forma, o cliente poderá entrar em contato com o profissional escolhido e acertar os detalhes restantes por conta própria, seja por número de celular ou email.</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Objetivo de teste</th>
   <td style="border: 1px solid black; padding: 10px;">Exibir o orçamento detalhado de cada profissional individualmente, contendo o prazo, preço, observações, informações de contato e um botão que leva ao perfil do profissional.</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Passos</th>
   <td style="border: 1px solid black; padding: 10px;">1)Acessar “Meu Painel” a partir da home;<br>2) Clicar em “Serviços Solicitados";<br>3) Escolher uma das categorias na qual foi solicitado um orçamento;<br>4) Escolher qual profissional deseja ver o orçamento e clicar em “Detalhes”.</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Critérios de êxito</th>
   <td style="border: 1px solid black; padding: 10px;">* O modal deve apresentar as informações de contato do profissional correspondente com o card e o botão deve levar ao perfil correto do profissional.</td>
  </tr>
</table>
<br>
<br>
<table style="border-collapse: collapse;">
  <tr>
    <th style="border: 1px solid white; padding: 10px;">Caso de teste</th>
    <td style="border: 1px solid black; padding: 10px;">CT-06: Visualização da página de perfil do profissional</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Requisitos</th>
   <td style="border: 1px solid black; padding: 10px;">RF-06: O site deve permitir que o cliente visualize a página do profissional.</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Objetivo de teste</th>
   <td style="border: 1px solid black; padding: 10px;">Verificar se a página de orçamentos está direcionando corretamente para o perfil de cada profissional.</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Passos</th>
   <td style="border: 1px solid black; padding: 10px;">1- Acessar o navegador<br>2- Acessar a página de orçamentos (https://icei-puc-minas-pmv-ads.github.io/PMV-ADS-2023-1-E1-PROJ-WEB-T11-Time2-CONCRETIZE/src/orcamentos.html)<br>3 - Seguir algum dos caminhos abaixo:<br>(a) Clicar na foto de um profissional<br>(b) Clicar no botão “Detalhes” e em seguida “Perfil do Profissional”
</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Critérios de êxito</th>
   <td style="border: 1px solid black; padding: 10px;">* Ao clicar em um profissional na página de orçamentos, a página de perfil do profissional deve ser apresentada corretamente.</td>
  </tr>
</table>
<br>
<br>
<table style="border-collapse: collapse;">
  <tr>
    <th style="border: 1px solid white; padding: 10px;">Caso de teste</th>
    <td style="border: 1px solid black; padding: 10px;">CT-07 - Página de painel profissional</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Requisitos</th>
   <td style="border: 1px solid black; padding: 10px;">RF-07 - O site deve permitir que o profissional acesse uma página, onde poderá visualizar os orçamentos que já enviou e as solicitações de serviços que correspondem com sua categoria de atuação e localização.</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Objetivo de teste</th>
   <td style="border: 1px solid black; padding: 10px;">Verificar se os pop-ups estão aparecendo e o redirecionamento está sendo feito.</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Passos</th>
   <td style="border: 1px solid black; padding: 10px;">1) Ver orçamentos enviados;<br>2) Enviar novos orçamento se houver interesse;</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Critérios de êxito</th>
   <td style="border: 1px solid black; padding: 10px;">*Ao lado esquerdo deve mostrar os Orçamentos enviados ao cliente<br>*Ao lado direito deve mostrar Solicitações para enviar orçamento se houver interesse.<br>*Orçamentos enviados devem abrir um pop-up.<br>*Enviar orçamento deve redirecionar para a página de Enviar orçamento.
</td>
  </tr>
</table>
<br>
<br>
<table style="border-collapse: collapse;">
  <tr>
    <th style="border: 1px solid white; padding: 10px;">Caso de teste</th>
    <td style="border: 1px solid black; padding: 10px;">CT-08 - Enviar orçamento ao cliente</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Requisitos</th>
   <td style="border: 1px solid black; padding: 10px;">RF-08 - O site deve permitir que o profissional envie um orçamento, caso esteja interessado, para as solicitações de serviços que correspondam com sua categoria de atuação e localização.</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Objetivo de teste</th>
   <td style="border: 1px solid black; padding: 10px;">Verificar se o preenchimento do orçamento está acontecendo corretamente.</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Passos</th>
   <td style="border: 1px solid black; padding: 10px;">1) Preencher o preço estimado do serviço;<br>2) Preencher o prazo estimado do serviço;<br>3) Preencher os detalhes relevantes;</td>
  </tr>
  <tr>
   <th style="border: 1px solid white; padding: 10px;">Critérios de êxito</th>
   <td style="border: 1px solid black; padding: 10px;">* Não ser possível digitar palavras nos campos de preço;<br>* Ser obrigatório o preenchimento de todos os campos;</td>
  </tr>
</table>

<!-- <span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Especificação do Projeto</a></span>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>

Apresente os cenários de testes utilizados na realização dos testes da sua aplicação. Escolha cenários de testes que demonstrem os requisitos sendo satisfeitos.

Enumere quais cenários de testes foram selecionados para teste. Neste tópico o grupo deve detalhar quais funcionalidades avaliadas, o grupo de usuários que foi escolhido para participar do teste e as ferramentas utilizadas.
 
## Ferramentas de Testes (Opcional)

Comente sobre as ferramentas de testes utilizadas.
 
> **Links Úteis**:
> - [IBM - Criação e Geração de Planos de Teste](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Práticas e Técnicas de Testes Ágeis](http://assiste.serpro.gov.br/serproagil/Apresenta/slides.pdf)
> -  [Teste de Software: Conceitos e tipos de testes](https://blog.onedaytesting.com.br/teste-de-software/)
> - [Criação e Geração de Planos de Teste de Software](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Ferramentas de Test para Java Script](https://geekflare.com/javascript-unit-testing/)
> - [UX Tools](https://uxdesign.cc/ux-user-research-and-user-testing-tools-2d339d379dc7) -->
