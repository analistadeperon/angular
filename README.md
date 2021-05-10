# angular
<div id="app"></div>
<form action="aula6.html" method="get">
  Campo 1: <input type="text" size="100" tabindex="3" maxlength="4" name="campo1"><br>
  Campo 2: <input type="text" size="100" tabindex="2" name="campo2"><br>
  Campo 3: <input type="text" size="100" tabindex="1"><br>
  Campo 4: <input type="radio" name="pergunta4" value="1">Resposta 1 
           <input type="radio" name="pergunta4" value="2">Resposta 2
           <input type="radio" name="pergunta4" value="3">Resposta 3<br>
  Campo 5: <input type="checkbox" name="pergunta5" value="1" accesskey="1">Resposta 1
           <input type="checkbox" name="pergunta5" value="2" accesskey="2">Resposta 2
           <input type="checkbox" name="pergunta5" value="3" accesskey="3">Resposta 3<br>
  Campo 6: <select name="pergunta6">
             <option>Item 5</option>
             <option>Item 6</option>
             <option selected>Item 7</option>
           </select>
  Campo 7: <select name="pergunta7" multiple>
             <option>Item 5</option>
             <option>Item 6</option>
             <option>Item 7</option>
             <option>Item 8</option>
           </select>
	   <input type="submit"> <input type="reset">
</form>

<form action="aula6.html" method="post" enctype="multipart/form-data">
<!-- no lugar de aula6.html eu colocarei o endereço da página que o analista fornecerá -->

  <div align="right">
    Código da vaga: <input type="text" readonly size="14" value="2005-01-863473"><br>
	Código do candidato: <input type="text" disabled size="14" value="2005-01-000356"><br>
	<hr width="80%">	
  </div>

  <fieldset>
    <legend><font size="4">Dados pessoais:</font></legend>
    Nome: <input type="text" name="nome" size="20" maxlength="30"><br>
    E-mail: <input type="text" name="email" size="30" maxlength="20"><br>
    Sexo: <input type="radio" name="sexo" value="M">Masculino
          <input type="radio" name="sexo" value="F">Feminino
          <input type="radio" name="sexo" value="N" checked>Nenhum<br>
    Idade: <input type="text" name="idade" size="2"><br>
    Foto: <input type="file" name="foto" size="15">
  </fieldset><br>

  <fieldset>
    <legend>Dados profissionais:</legend>
    Formas de contratação: <br>
      <input type="checkbox" name="contratacao" value="clt" checked>CLT <br>
      <input type="checkbox" name="contratacao" value="autonomo">Profissional autônomo <br>
      <input type="checkbox" name="contratacao" value="estágio">Estágio <br>
    Cargo pretendido:
      <select name="cargo">
        <option value="anjr">Analista junior</option>
        <option value="anpl">Analista pleno</option>
        <option value="ansr">Analista senior</option>
      </select> <br>
  </fieldset><br>

  <fieldset>
    <legend><b>Dados para login:</b></legend>
	  Usuário: <input type="text" name="usuario" size="10" maxlength="10"> <br>
	  Senha  : <input type="password" name="senha" size="10" maxlength="10">   
  </fieldset><br>

  <fieldset style="color:darkgreen;border-color:blue">
    <legend><font color="blue">Demais informações:</font></legend>
    Porque você quer entrar nesta empresa? <br>
	<textarea name="info1" rows="4" cols="30" wrap="virtual">Digite seu texto aqui</textarea> <br>
	Fluência nos idiomas: <br>
	<select name="idioma" multiple size="4">
	  <option value="ingles">Inglês</option>
	  <option value="espanol">Espanhol</option>
	  <option value="frances">Francês</option>
	  <option value="japa">Japones</option>
	  <option value="china">Chinês</option>
	  <option value="russo">Russo</option>
	  <option value="indiano">Indiano</option>
	  <option value="corintiano">Curintiano</option>
  	</select> <br>
	Time: 
	<select name="futebol">
	  <optgroup label="SP">
	    <option value="tricolor" selected>São Paulo</option>
	    <option value="parmera" selected>Palmeiras</option>
	    <option value="corintia" selected>Corinthians</option>
	    <option value="peixe" selected>Santos</option>
	  </optgroup>
	  <optgroup label="RJ">
	    <option value="time1" selected>Flamengo</option>
	    <option value="time2" selected>Vasco</option>
	    <option value="time3" selected>Botafogo</option>
	  </optgroup>
	  <optgroup label="MG">
	    <option value="mg-t1" selected>Cruzeiro</option>
	    <option value="mg-t2" selected>Atlético Mineiro</option>
	    <option value="mg-t3" selected>Clube de Futebol de Camanducaia</option>
	  </optgroup>
	  <optgroup label="RS">
	    <option value="rs-t1" selected>Internacional</option>
	    <option value="rs-t2" selected>Grêmio</option>
	    <option value="rs-t3" selected>Gaúchos Unidos de Pelotas</option>
	  </optgroup>
	  <optgroup label="CE">
	    <option value="1" selected>A</option>
	    <option value="2" selected>B</option>
	    <option value="3" selected>C</option>
	  </optgroup>
	</select>
  </fieldset><br>

  <hr width="80%">	
  <div align="center">
    <input type="reset"  name="btn_limpar" value="Limpar">
    <input type="submit" name="btn_envio"  value="Enviar">
    <input type="button" name="btn_voltar" value="Voltar">
    <input type="image"  name="btn_home"   src="img/arvore2.jpg" width="15" height="15">
  </div>
</form>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>BonilhaTech - Cadastro de Usuários</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
    <style>
        .usuario-conteudo {
            background-color: #EEE;
            padding: 20px 20px 10px 20px;
            margin-top: 30px;
        }
    </style>
</head>
<body>
<div class="container">
    <div class="row">
        <div class="col-md-offset-2 col-md-8">
            <div class="usuario-conteudo" ng-controller="UsuarioController">
                <div class="boasvindas" >
                    <h1 style="text-align: center"> {{myHeader}} </h1>
                </div>                
                <h1>Cadastro de Usuários</h1>
                <form name="formulario" ng-if="update">
                    <div class="form-group">
                        <label for="nome">Nome*</label>
                        <input type="text" class="form-control" id="nome" placeholder="Nome do usuário" 
                               maxlength="20" required ng-model="usuario.nome">
                    </div>
                    <div class="form-group has-feedback {{statusSenha.classe}}">
                        <label for="senha">Senha*</label>
                        <input type="password" class="form-control" id="senha" placeholder="Informe a senha do Usuário" 
                               maxlength="10" required ng-model="usuario.senha" ng-change="validarSenha()">
                        <span class="glyphicon form-control-feedback {{statusSenha.icone}}" aria-hidden="true"></span>
                        <p class="help-block">{{statusSenha.mensagem}}</p>
                    </div>
                    <div class="form-group has-edit">
                        <label for="nome">Para editar os dados, utilizar os campos abaixo:</label>
                        <input type="text" class="form-control" placeholder="Altere o nome do usuário" maxlength="20" 
                               required ng-model="update.name">
                        <input type="password" class="form-control" required ng-model="update.senha"placeholder="Altere a senha do Usuário"
                               maxlength="10" ng-change="validarSenha()">
                        <span class="glyphicon form-control-feedback {{statusSenha.icone}}" aria-hidden="true"></span>
                        <p class="help-block">{{statusSenha.mensagem}}</p>
                    </div>
                    <button type="submit" class="btn btn-primary" ng-submit="cadastrar()">Cadastrar</button>
                    <button ng-click="salvar()" ng-submit="salvar()" class="btn btn-primary">Editar</button>
                </form>
                <hr>
                <h1>Lista de Usuários: </h1>
                <table class="table table-striped" ng-hide="UsuarioController.usuarios == 0">
                    <thead>
                    <tr>
                        <th>Nome</th>
                        <th>Senha</th>
                        <th>Ação</th>
                    </tr>
                    </thead>
                    <tbody>
                    <!-- Aqui serão exibidos os dados do usuários cadastrados -->
                        <tr ng-repeat="usuario in usuarios">
                            <td>{{usuario.nome}}</td>
                            <td>{{usuario.senha}}</td>
                            <td><button class="btn btn-danger btn-xs" ng-click="remover($index)">Remover</button></td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>
    </div>
</div>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.4/angular.min.js"></script>
<script src="app.js"></script>
<html lang="pt-br">
<head>
<meta charset="utf-8">
<meta http-equiv="X-UA-Compatible" content="IE-edge">
<meta name="viewport" content="width=devide-width, initial-scale=1">
<title> ********** </title>
<link ref="icon" href="">
<link href="css/recuperarbootstrap.css" rel="stylesheet">
<link href="css/recuperar.css" rel="stylesheet">
</head>
<body>
<div class="container">
<form class="form-signin" method="POST" action="" style="background:#DCDCDC;">
<h2 class="form-signin-heading text-center">Recuperação de Senha</h2>
<div style="padding-bottom: 20px;">
<label class="sr-only">Usuário:</label>
<input class="form-control" name="email" placeholder="Digite seu email" type="text">
</div>
<input class="btn btn-lg btn-verde btn-block" value="Recuperar" name="SendRecupSenha" type="submit">
<div class="text-center" style="margin-top:20px;">
Lembrou?
<a href="login.php">Clique aqui</a>
</div>
</form>
</div>
