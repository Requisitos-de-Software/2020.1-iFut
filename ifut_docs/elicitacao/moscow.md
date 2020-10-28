<table class="table table-striped border">
   <thead>
       <th>Data</th>
       <th>Versão </th>
       <th>Descrição</th>
       <th>Autor(es)</th>
   </thead>
   <tbody>
       <tr>
           <td> 19.09.2020 </td>
           <td> 0.1 </td>
           <td> Criação do documento </td>
           <td> Lucas Lopes</td>
       </tr>
       <tr>
           <td> 27.09.2020 </td>
           <td> 0.2 </td>
           <td> Revisão </td>
           <td> Isabella Carneiro </td>
       </tr>
       <tr>
           <td> 05.10.2020 </td>
           <td> 0.3 </td>
           <td> Adição de itens </td>
           <td> Isabella Carneiro </td>
       </tr>
   </tbody>
</table>

# **MoSCoW**
<div class="line"></div>

## Metodologia

<div>
   <p align="justify">&emsp;
      As quatro letras maiúsculas no esquema de priorização MoSCoW representam quatro classificações prioritárias
      possíveis para os requisitos em um conjunto (IIBA 2009):</p>
   <p align="justify">
      <strong>Must</strong>: A exigência deve ser satisfeita para que a solução seja considerada um sucesso.</p>
   <p align="justify">
      <strong>Should</strong>: O requisito é importante para o produto final, mas não é vital. Se deixado de lado, a
      aplicação ainda
      funciona. Mas, quando incluído, acrescenta um valor significativo. </p>
   <p align="justify">
      <strong> Could</strong>: não é necessário para o funcionamento do projeto. Implementá-lo somente se o tempo e os
      recursos
      permitirem.</p>
   <p align="justify">
      <strong>Won’t</strong> Isto indica um requisito que não será implementado neste momento, mas que poderia ser
      incluído em um
      lançamento futuro.</p>
   <p align="justify"><em>(Wiegers e Beatty, 2013)</em> </p>
</div>

## Participantes
- Lucas
- Isabella

## Nota Importante
 <p>Este será o método em que o grupo baseará os outros artefatos.</p>

## Resultado

<table class="table table-striped border" style="color:black;">
   <thead style="background-color: #00ff2b;">
      <th>Número</th>
      <th>Requisito</th>
      <th>MoSCoW</th>
   </thead>
   <tbody>
      <tr>
         <td>1 </td>
         <td>O  <a href="../../modelagem/lexico/#usuario">usuário</a> poderá acessar o aplicativo sem ter login </td>
         <td>Must </td>
      </tr>
      <tr>
         <td>2 </td>
         <td>O  <a href="../../modelagem/lexico/#usuario">usuário</a> pode ser capaz de ver os <a href="../../modelagem/lexico/#campeonato">campeonato</a>s cadastrados </td>
         <td>Must</td>
      </tr>
      <tr>
         <td>3 </td>
         <td>O  <a href="../../modelagem/lexico/#usuario">usuário</a> terá uma função de  <a href="../../modelagem/lexico/#favoritar">favoritar</a> um <a href="../../modelagem/lexico/#campeonato">campeonato</a> </td>
         <td>Should </td>
      </tr>
      <tr>
         <td>4</td>
         <td>O  <a href="../../modelagem/lexico/#usuario">usuário</a> poderá visualizar tabela de  <a href="../../modelagem/lexico/#pontuacao">pontuação</a> e  <a href="../../modelagem/lexico/#rodadas">rodadas</a> ao clicar em <a href="../../modelagem/lexico/#campeonato">campeonato</a> </td>
         <td>Should </td>
      </tr>
      <tr>
         <td>5 </td>
         <td>O  <a href="../../modelagem/lexico/#usuario">usuário</a>, ao selecionar um <a href="../../modelagem/lexico/#campeonato">campeonato</a>, poderá escolher <a href="../../modelagem/lexico/#classificacao">classificação</a>,  <a href="../../modelagem/lexico/#ranking">ranking</a> e notícias dentro daquele
            <a href="../../modelagem/lexico/#campeonato">campeonato</a> </td>
         <td>Could</td>
      </tr>
      <tr>
         <td>6</td>
         <td>O  <a href="../../modelagem/lexico/#usuario">usuário</a>, ao selecionar um <a href="../../modelagem/lexico/#campeonato">campeonato</a>, poderá escolher <a href="../../modelagem/lexico/#classificacao">classificação</a>,  <a href="../../modelagem/lexico/#ranking">ranking</a> e notícias dentro daquele
            <a href="../../modelagem/lexico/#campeonato">campeonato</a> </td>
         <td>Must </td>
      </tr>
      <tr>
         <td>7 </td>
         <td>O  <a href="../../modelagem/lexico/#usuario">usuário</a> poderá selecionar a visualização de classificações e  <a href="../../modelagem/lexico/#eliminatorias">eliminatórias</a> dentro de um <a href="../../modelagem/lexico/#campeonato">campeonato</a> </td>
         <td>Could</td>
      </tr>
      <tr>
         <td>8</td>
         <td>Deverá ser disponilbilizado um link para acesso ao site </td>
         <td>Could </td>
      </tr>
      <tr>
         <td>9</td>
         <td>O  <a href="../../modelagem/lexico/#usuario">usuário</a> poderá buscar e  <a href="../../modelagem/lexico/#filtrar">filtrar</a> <a href="../../modelagem/lexico/#campeonato">campeonato</a>s </td>
         <td>Could </td>
      </tr>
      <tr>
         <td>10</td>
         <td>O login só será permitido àqueles  <a href="../../modelagem/lexico/#usuario">usuário</a>s que receberam o acesso/<a href="../../modelagem/lexico/#cadastrar">cadastro</a> via email </td>
         <td>Must </td>
      </tr>
      <tr>
         <td>11</td>
         <td>Só será disponibilizado login e recuperação de senha </td>
         <td> Should</td>
      </tr>
      <tr>
         <td>12 </td>
         <td>O envio de convites para cadastrados só será permitido a perfis de treinadores ou administradores </td>
         <td>Could </td>
      </tr>
      <tr>
         <td>13 </td>
         <td>O  <a href="../../modelagem/lexico/#usuario">usuário</a> poderá visualizar o  <a href="../../modelagem/lexico/#placar">placar</a> de um jogo em  <a href="../../modelagem/lexico/#tempo-real">tempo real</a> </td>
         <td>Won’t </td>
      </tr>
      <tr>
         <td>14 </td>
         <td>O  <a href="../../modelagem/lexico/#usuario">usuário</a> poderá pesquisar um jogador e ver suas informações </td>
         <td>Could </td>
      </tr>
      <tr>
         <td>15 </td>
         <td>O  <a href="../../modelagem/lexico/#usuario">usuário</a> cadastrado poderá criar <a href="../../modelagem/lexico/#campeonato">campeonato</a>s </td>
         <td>Should</td>
      </tr>
      <tr>
         <td>16 </td>
         <td>O  <a href="../../modelagem/lexico/#usuario">usuário</a> poderá fazer sugestões via comunicação </td>
         <td>Won’t </td>
      </tr>
      <tr>
         <td>17 </td>
         <td>O <a href="../../modelagem/lexico/#cadastrar">cadastro</a> terá informações básicas como nome, email, contato e senha </td>
         <td>Should </td>
      </tr>
      <tr>
         <td> 18</td>
         <td> O login será por email e senha </td>
         <td> Must</td>
      </tr>
      <tr>
         <td> 19</td>
         <td>A recuperação de senha poderá ser enviada por email ou  <a href="../../modelagem/lexico/#mensagem">mensagem</a> </td>
         <td> Could</td>
      </tr>
      <tr>
         <td> 20</td>
         <td> O  <a href="../../modelagem/lexico/#usuario">usuário</a> poderá <a href="../../modelagem/lexico/#compartilhar">compartilhar</a> por link informações de um  <a href="../../modelagem/lexico/#time">time</a>, <a href="../../modelagem/lexico/#campeonato">campeonato</a> ou jogador </td>
         <td> Won’t</td>
      </tr>
      <tr>
         <td> 21</td>
         <td>O  <a href="../../modelagem/lexico/#usuario">usuário administrador/treinador </a>  poderá alterar o status de seu link como  <a href="../../modelagem/lexico/#offline">offline</a>/ <a href="../../modelagem/lexico/#online">online</a> </td>
         <td>Won’t </td>
      </tr>
      <tr>
         <td> 22 </td>
         <td>O  <a href="../../modelagem/lexico/#usuario">usuário administrador/treinador </a>  poderá restringir o compartilhamento de suas informações </td>
         <td>Could </td>
      </tr>
      <tr>
         <td>23 </td>
         <td>o  <a href="../../modelagem/lexico/#usuario">usuário administrador/treinador </a>  poderá preencher informações de um <a href="../../modelagem/lexico/#campeonato">campeonato</a> quando responsável ou
            delegado </td>
         <td>Should </td>
      </tr>
      <tr>
         <td>24 </td>
         <td>O  <a href="../../modelagem/lexico/#usuario">usuário</a> administrador de um <a href="../../modelagem/lexico/#campeonato">campeonato</a> poderá criar  <a href="../../modelagem/lexico/#rodadas">rodadas</a> e alterar <a href="../../modelagem/lexico/#chaves">chaves</a> </td>
         <td>Must </td>
      </tr>
      <tr>
         <td>25 </td>
         <td>O  <a href="../../modelagem/lexico/#usuario">usuário</a> administrador de um <a href="../../modelagem/lexico/#campeonato">campeonato</a> poderá editar, excluir  <a href="../../modelagem/lexico/#time">time</a>s e  <a href="../../modelagem/lexico/#rodadas">rodadas</a> </td>
         <td>Must </td>
      </tr>
      <tr>
         <td>26 </td>
         <td>O  <a href="../../modelagem/lexico/#usuario">usuário</a> administrador de um <a href="../../modelagem/lexico/#campeonato">campeonato</a> poderá abrir inscrições para <a href="../../modelagem/lexico/#campeonato">campeonato</a> </td>
         <td>Must </td>
      </tr>
      <tr>
         <td>27 </td>
         <td> O  <a href="../../modelagem/lexico/#usuario">usuário</a> administrador de um <a href="../../modelagem/lexico/#campeonato">campeonato</a> poderá editar/visualizar pagantes em um <a href="../../modelagem/lexico/#campeonato">campeonato</a> </td>
         <td>Must </td>
      </tr>
      <tr>
         <td>28 </td>
         <td>O sistema poderá enviar  <a href="../../modelagem/lexico/#links">links</a> de mensagens por  <a href="../../modelagem/lexico/#media-social">media social</a> </td>
         <td>Won’t </td>
      </tr>
      <tr>
         <td>29</td>
         <td>O  <a href="../../modelagem/lexico/#usuario">usuário</a> administrador de um <a href="../../modelagem/lexico/#campeonato">campeonato</a> pode fazer  <a href="../../modelagem/lexico/#upload">upload</a> de arquivos </td>
         <td> Must</td>
      </tr>
      <tr>
         <td>30 </td>
         <td>Um  <a href="../../modelagem/lexico/#usuario">usuário</a> logado poderá fazer logout </td>
         <td> Should</td>
      </tr>
      <tr>
         <td>31 </td>
         <td>O  <a href="../../modelagem/lexico/#usuario-elite">usuário elite</a>  deve poder adicionar notícias a um <a href="../../modelagem/lexico/#campeonato">campeonato</a> </td>
         <td> Must</td>
      </tr>
      <tr>
         <td>32 </td>
         <td>O  <a href="../../modelagem/lexico/#usuario-elite">usuário elite</a>  deve poder adicionar  <a href="../../modelagem/lexico/#patrocinadores">patrocinadores</a> e produtos </td>
         <td>Must </td>
      </tr>
      <tr>
         <td> 33</td>
         <td>O sistema deve ser capaz de gerar  <a href="../../modelagem/lexico/#sumula-digital">súmula digital</a> </td>
         <td> Should</td>
      </tr>
      <tr>
         <td>34 </td>
         <td> O  <a href="../../modelagem/lexico/#usuario">usuário premium </a> /ELITE deve poder ter acesso a  <a href="../../modelagem/lexico/#sumula-digital">súmula digital</a> </td>
         <td>Should </td>
      </tr>
      <tr>
         <td>35 </td>
         <td> O  <a href="../../modelagem/lexico/#usuario">usuário</a> poderá  <a href="../../modelagem/lexico/#filtrar">filtrar</a> jogadores em um  <a href="../../modelagem/lexico/#ranking">ranking</a> </td>
         <td> Could</td>
      </tr>
      <tr>
         <td>36 </td>
         <td>O  <a href="../../modelagem/lexico/#perfil">perfil</a> de JOGADOR deverá armazenar os  <a href="../../modelagem/lexico/#time">time</a>s que ele participa </td>
         <td> Must</td>
      </tr>
      <tr>
         <td>37 </td>
         <td>O  <a href="../../modelagem/lexico/#perfil">perfil</a> de JOGADOR deverá armazenar e exibir  <a href="../../modelagem/lexico/#estatisticas">estatísticas</a> e não exibir  <a href="../../modelagem/lexico/#informacoes-pessoais">informações pessoais</a> </td>
         <td>Must </td>
      </tr>
      <tr>
         <td> 38</td>
         <td>O sistema de tabelas deve ser <a href="../../modelagem/lexico/#auto-gerenciavel">auto gerenciável</a> a cada rodada </td>
         <td>Should </td>
      </tr>
      <tr>
         <td>39 </td>
         <td>O atualização de tabelas,  <a href="../../modelagem/lexico/#ranking">ranking</a>, resultados e  <a href="../../modelagem/lexico/#estatisticas">estatísticas</a> deverá ser feito de forma automática da cada
            fim de rodada </td>
         <td>Should </td>
      </tr>
      <tr>
         <td>40 </td>
         <td>O  <a href="../../modelagem/lexico/#usuario">usuário</a> deve ser capaz de ver os anúncios dos  <a href="../../modelagem/lexico/#parceiros">parceiros</a> e interagir com os mesmos </td>
         <td>Must </td>
      </tr>
      <tr>
         <td>41 </td>
         <td>O  <a href="../../modelagem/lexico/#usuario">usuário</a> deve ser capaz de visualizar a sua <a href="../../modelagem/lexico/#agenda-de-jogos">agenda de jogos</a> </td>
         <td>Won’t </td>
      </tr>
      <tr>
         <td>42 </td>
         <td>O sistema pode ter otimização para ter  <a href="../../modelagem/lexico/#seo">SEO</a> e para identificação por mecanismo de busca dentro de lojas de <a href="../../modelagem/lexico/#App">App</a>
         </td>
         <td>Must </td>
      </tr>
      <tr>
         <td>43 </td>
         <td>O <a href="../../modelagem/lexico/#App">App</a> deverá estar disponível para  <a href="../../modelagem/lexico/#ios">IOS</a> e ANDROID </td>
         <td>Should </td>
      </tr>
      <tr>
         <td>44 </td>
         <td>O <a href="../../modelagem/lexico/#App">App</a> deverá ser compatível com normas de <a href="../../modelagem/lexico/#acessibilidade">acessibilidade</a> e compatilibidade, com solução assistência/ajuda
            para debilidades </td>
         <td>Could </td>
      </tr>
      <tr>
         <td>45 </td>
         <td>O <a href="../../modelagem/lexico/#App">App</a> CLIENT deverá requisitar dados ao final de cada partida ao  <a href="../../modelagem/lexico/#server">server</a> </td>
         <td>Could </td>
      </tr>
      <tr>
         <td>46 </td>
         <td>O <a href="../../modelagem/lexico/#App">App</a> CLIENT deverá requisitar dados ao final de cada partida ao  <a href="../../modelagem/lexico/#server">server</a> </td>
         <td>Should </td>
      </tr>
      <tr>
         <td>47 </td>
         <td>O <a href="../../modelagem/lexico/#App">App</a> deverá ser construído em um  <a href="../../modelagem/lexico/#framework">Framework</a>  <a href="../../modelagem/lexico/#multiplataforma">Multiplataforma</a> </td>
         <td>Could</td>
      </tr>
      <tr>
         <td>48 </td>
         <td>O  <a href="../../modelagem/lexico/#usuario">usuário</a> poderá navegar pelos menus </td>
         <td>Could</td>
      </tr>
        <tr>
         <td>49 </td>
         <td>O  <a href="../../modelagem/lexico/#usuario">usuário</a> pode verificar o  <a href="../../modelagem/lexico/#extrato-do-jogo">extrato do jogo</a>, assim como sua  <a href="../../modelagem/lexico/#escalacao">escalação</a>.	 </td>
         <td>Should</td>
      </tr>
      <tr>
         <td>50 </td>
         <td>O  <a href="../../modelagem/lexico/#usuario">usuário</a> pode checar quem são os jogadores de um  <a href="../../modelagem/lexico/#time">time</a>, assim como os jogos que ele jogou e suas  <a href="../../modelagem/lexico/#estatisticas">estatísticas</a>.	 </td>
         <td>Should</td>
      </tr>
   </tbody>
</table>
