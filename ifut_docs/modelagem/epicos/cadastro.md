# Épico: Cadastro


### US01 Realizar cadastro 

Eu,  como <a href="../../modelagem/lexico/#usuario">usuário</a> visitante desejo poder me cadastrar no site/aplicativo do Ifut.

#### Critérios de Aceitação:
- Cadastro de pelo aplicativo mobile permitido.
- Ser possível escolher o plano de assinatura no processo de cadastro.
- Cadastro de administrador permitido apenas pelo site.
  
### US02 Fazer <a href="../../modelagem/lexico/#login">Login</a>

Eu,  como <a href="../../modelagem/lexico/#usuario">usuário</a> cadastrado desejo poder me logar no site/aplicativo do Ifut.

#### Critérios de Aceitação:
- Ser possível realizar o <a href="../../modelagem/lexico/#login">login</a> de <a href="../../modelagem/lexico/#usuario">usuário</a> existente e devidamente cadastrado.
- Ser retornado as credenciais e disponibilizado acesso ao perfil especificado.
- Realizar a validação das credenciais de acesso.
  


### US03 Fazer <a href="../../modelagem/lexico/#logout">Logout</a>

Eu,  como <a href="../../modelagem/lexico/#usuario">usuário</a> logado desejo poder me deslogar do site/aplicativo do Ifut.

#### Critérios de Aceitação:
- Ser possível limpar as credenciais da sessão.
- Retornar a <a href="../../modelagem/lexico/#home">home</a> do aplicativo.
- Redicionar para <a href="../../modelagem/lexico/#home">home</a> caso tente o acesso a uma rota que requisite estar autentificado.

### US04 Editar <a href="../../modelagem/lexico/#perfil">perfil</a> 

Eu,  como <a href="../../modelagem/lexico/#usuario">usuário</a> logado desejo poder me atualizar meus dados.

#### Critérios de Aceitação:
- Ser possível realizar o edição de <a href="../../modelagem/lexico/#informacoes-pessoais">informações pessoais</a> e de comunicação.
- Validar de dados obrigatórios já estão sendo usados por outra conta antes de atualizar
  
  
### US05 Recuperar senha

Eu,  como <a href="../../modelagem/lexico/#usuario">usuário</a> visitante desejo poder requisitar o reset da senha.

#### Critérios de Aceitação:
- Verificar se existente <a href="../../modelagem/lexico/#login">login</a> vinculado com alguma conta no sistema.
- Enviar link temporário de recuperação via email.
- Validar trocar de senha usando o email como informação de checagem.
  

### US06 Enviar convite

Eu,  como <a href="../../modelagem/lexico/#usuario">usuário</a> administrador/ treinador desejo poder enviar convites de cadastro.

#### Critérios de Aceitação:
- Link de cadastro vinculado a um <a href="../../modelagem/lexico/#Time">time</a> pra cadastrado.
- Vincular <a href="../../modelagem/lexico/#perfil">perfil</a> de atleta ao realizar cadastro por link.
- Link com tempo de expiração maior.