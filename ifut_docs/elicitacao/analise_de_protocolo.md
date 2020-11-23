# **Análise de Protocolo**

## Histórico de Versão

<table class="table table-striped border">
    <thead>
        <th>Data</th>
        <th>Versão </th>
        <th>Descrição</th>
        <th>Autor(es)</th>
    </thead>
    <tbody>
        <tr>
            <td> 21.09.2020 </td>
            <td> 0.1 </td>
            <td> Criação do documento </td>
            <td> Isabella Carneiro </td>
        </tr>
        <tr>
            <td> 21.09.2020 </td>
            <td> 0.2 </td>
            <td> Adição da metodologia </td>
            <td> Bruna Almeida</td>
        </tr>
        <tr>
            <td> 26.09.2020 </td>
            <td> 0.3 </td>
            <td> Adição da tabela de versionamento </td>
            <td> Isabella Carneiro </td>
        </tr>
        <tr>
            <td> 27.09.2020 </td>
            <td> 0.4 </td>
            <td> Novos itens e formatação </td>
            <td> Lucas </td>
        </tr>
        <tr>
            <td> 05.10.2020 </td>
            <td> 0.5 </td>
            <td> Novos itens </td>
            <td> Isabella Carneiro</td>
        </tr>
        <tr>
            <td> 23.11.2020 </td>
            <td> 0.6 </td>
            <td> Revisão do documento </td>
            <td> Isabella </td>
        </tr>
    </tbody>
</table>

<div class="line"></div>

## Metodologia

<div>
    <p align="justify">&emsp;
        A técnica Análise de Protocolo pede ao stakeholder envolvido em determinado processo específico para executar
        uma tarefa relacionada a uma funcionalidade da aplicação e ao mesmo tempo ir descrevendo e inserindo o que pensa
        sobre aquele processo.</p>

</div>
<div class="line"></div>

## Participantes

- Isabella Carneiro

<div class="line"></div>

## Escopo

<div>
    <p align="justify">&emsp;
        Para melhor aplicação dessa técnica de elicitação foi definido um escopo de quais áreas do aplicativo seriam
        analisadas.
        Por fim, decidiu-se que seria aplicado em toda a parte grátis do aplicativo, isto é, excluindo a parte do
        <a href="../../modelagem/lexico/#atleta">atleta</a>.</p>
</div>

## Resultado

<div>
    <p align="justify">&emsp;
        A integrante do grupo Isabella fez o papel de  <a href="../../modelagem/lexico/#usuario">usuário</a> e descreveu sua experiência utilizando o aplicativo. O
        registro dessa narração será evidenciado a seguir.
        “Quando eu abro o iFut a tela inicial mostra <a href="../../modelagem/lexico/#campeonato">campeonato</a>s que eu posso selecionar, além dos <a href="../../modelagem/lexico/#campeonato">campeonato</a>s que
        favoritei. Tenho a opção de buscar por <a href="../../modelagem/lexico/#campeonato">campeonato</a>s e  <a href="../../modelagem/lexico/#favoritar">favoritar</a> o mesmo.
        Quando clico para  <a href="../../modelagem/lexico/#favoritar">favoritar</a> um <a href="../../modelagem/lexico/#campeonato">campeonato</a> ele fica mais visível na tela, com destaque, de modo que seja mais
        fácil de encontrá-lo para ver as informações.
        Na parte superior da tela tenho a opção de criar <a href="../../modelagem/lexico/#campeonato">campeonato</a> que me leva ao site do iFut e a opção de login para
        entrar na área do <a href="../../modelagem/lexico/#atleta">atleta</a>, que é uma funcionalidade paga.
        Quando seleciono um <a href="../../modelagem/lexico/#campeonato">campeonato</a> consigo ver a tabela de <a href="../../modelagem/lexico/#classificacao">classificação</a> dos  <a href="../../modelagem/lexico/#time">time</a>s e as  <a href="../../modelagem/lexico/#rodadas">rodadas</a> (passadas e
        futuras), ao selecionar um jogo vejo quem fez os gols, assistências e quem levou os cartões naquele jogo, também há uma aba que mostra a  <a href="../../modelagem/lexico/#escalacao">escalação</a> daquele jogo. Ao clicar em um  <a href="../../modelagem/lexico/#time">time</a> na tabela é possível ver os jogadores que jogam nele, os jogos que ele jogou e as  <a href="../../modelagem/lexico/#estatisticas">estatísticas</a> do  <a href="../../modelagem/lexico/#time">time</a>. É possível ver o  <a href="../../modelagem/lexico/#ranking">ranking</a> de  <a href="../../modelagem/lexico/#pontuacao">pontuação</a> dos <a href="../../modelagem/lexico/#atleta">atleta</a>s, podendo  <a href="../../modelagem/lexico/#filtrar">filtrar</a> por posição ou por pontuações.
        Nessa tela posso ver as regras das pontuações e também as notícias do <a href="../../modelagem/lexico/#campeonato">campeonato</a>.
        Quando clico no nome do jogador vejo o extrato da  <a href="../../modelagem/lexico/#pontuacao">pontuação</a> dele na rodada e nessa nova tela ao clicar no nome
        sou redirecionada ao  <a href="../../modelagem/lexico/#perfil">perfil</a> do jogador onde consigo ver as  <a href="../../modelagem/lexico/#informacoes-pessoais">informações pessoais</a> e técnicas do mesmo. Nela são
        exibidas as  <a href="../../modelagem/lexico/#estatisticas">estatísticas</a> dele e os  <a href="../../modelagem/lexico/#time">time</a>s que ele participa.
        Essas são as opções de navegação da parte não paga.”</p>
</div>

## Requisitos Elicitados

A partir da análise da narração do uso do app iFut foram elicitados os seguintes requisitos:

<table class="table table-striped border" style="color:black;">
    <thead style="background-color: #00ff2b;">
        <th>Número</th>
        <th>Requisito</th>
    </thead>
    <tbody>
        <tr>
            <td>1 </td>
            <td>O  <a href="../../modelagem/lexico/#usuario">usuário</a> deve ser capaz de visualizar o  <a href="../../modelagem/lexico/#perfil">perfil</a> de outros jogadores. </td>
        </tr>
        <tr>
            <td>2 </td>
            <td>O  <a href="../../modelagem/lexico/#usuario">usuário</a> deve ser capaz de visualizar a  <a href="../../modelagem/lexico/#pontuacao">pontuação</a> na rodada de outros jogadores. </td>
        </tr>
        <tr>
            <td>3 </td>
            <td>O  <a href="../../modelagem/lexico/#usuario">usuário</a> deve ser capaz de  <a href="../../modelagem/lexico/#favoritar">favoritar</a> um <a href="../../modelagem/lexico/#campeonato">campeonato</a>. </td>
        </tr>
        <tr>
            <td>4 </td>
            <td>O  <a href="../../modelagem/lexico/#usuario">usuário</a> deve ser capaz de  <a href="../../modelagem/lexico/#filtrar">filtrar</a> os jogadores no  <a href="../../modelagem/lexico/#ranking">ranking</a>. </td>
        </tr>
        <tr>
            <td>5 </td>
            <td>O  <a href="../../modelagem/lexico/#perfil">perfil</a> do jogador deve armazenar os  <a href="../../modelagem/lexico/#time">time</a>s que ele joga. </td>
        </tr>
        <tr>
            <td>6 </td>
            <td>O  <a href="../../modelagem/lexico/#perfil">perfil</a> do jogador deve armazenar  <a href="../../modelagem/lexico/#informacoes-tecnicas">informações técnicas</a>, além das pessoais.</td>
        </tr>
        <tr>
            <td>7 </td>
            <td>O sistema deve atualizar a tabela do <a href="../../modelagem/lexico/#campeonato">campeonato</a> a cada rodada.</td>
        </tr>
        <tr>
            <td>8 </td>
            <td>O sistema deve atualizar os  <a href="../../modelagem/lexico/#resultados">resultados</a> dos jogos do <a href="../../modelagem/lexico/#campeonato">campeonato</a> a cada rodada.</td>
        </tr>
        <tr>
            <td>9 </td>
            <td>O sistema deve atualizar o  <a href="../../modelagem/lexico/#ranking">ranking</a> dos jogadores a cada rodada.</td>
        </tr>
        <tr>
            <td>10 </td>
            <td>O aplicativo cliente deverá ser um <a href="../../modelagem/lexico/#App">App</a> consumidor de dados um serviço.</td>
        </tr>
        <tr>
            <td>11 </td>
            <td>O sistema deverá ser compatível com <a href="../../modelagem/lexico/#acessibilidade">acessibilidade</a> e  <a href="../../modelagem/lexico/#praticas-ux">Práticas UX</a>.</td>
        </tr>
        <tr>
            <td>13 </td>
            <td>O sistema deve estar de acordo com a <a href="../../modelagem/lexico/#legislacao">legislação</a> pertinente e políticas de privacidade.</td>
        </tr>
        <tr>
            <td>14 </td>
            <td>O aplicativo cliente deve ser multiplatarforma e de fácil  <a href="../../modelagem/lexico/#integracao">integração</a> com <a href="../../modelagem/lexico/#API">API</a> de terceiros.</td>
        </tr>
        <tr>
            <td>15 </td>
            <td>O  <a href="../../modelagem/lexico/#usuario">usuário</a> pode verificar o  <a href="../../modelagem/lexico/#extrato-do-jogo">extrato do jogo</a>, assim como sua  <a href="../../modelagem/lexico/#escalacao">escalação</a>.</td>
        </tr>
        <tr>
            <td>16 </td>
            <td>O  <a href="../../modelagem/lexico/#usuario">usuário</a> pode checar quem são os jogadores de um  <a href="../../modelagem/lexico/#time">time</a>, assim como os jogos que ele jogou e suas  <a href="../../modelagem/lexico/#estatisticas">estatísticas</a>.</td>
        </tr>
    </tbody>
</table>

## Referências
- SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 07;
