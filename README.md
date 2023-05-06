<html >
<head>
  

<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"></script>

</head>

<body>
   <form id="cadastro">
        <div class="form-group">
          <label for="nome">Nome*</label>
          <input type="text" class="form-control" id="nome" name="nome">
          <div id="erro-nome" class="invalid-feedback">Campo obrigatório</div>
        </div>
        <div class="form-group">
          <label for="sobrenome">Sobrenome*</label>
          <input type="text" class="form-control" id="sobrenome" name="sobrenome">
          <div id="erro-sobrenome" class="invalid-feedback">Campo obrigatório</div>
        </div>
        <div class="form-group">
          <label for="email">E-mail*</label>
          <input type="email" class="form-control" id="email" name="email">
          <div id="erro-email" class="invalid-feedback">Campo obrigatório</div>
        </div>
        <div class="form-group">
          <label for="senha">Senha*</label>
          <input type="password" class="form-control" id="senha" name="senha">
          <div id="erro-senha" class="invalid-feedback">Campo obrigatório</div>
        </div>
        <div class="form-group">
          <label for="endereco">Endereço*</label>
          <input type="text" class="form-control" id="endereco" name="endereco">
          <div id="erro-endereco" class="invalid-feedback">Campo obrigatório</div>
        </div>
        <div class="form-row">
          <div class="form-group col-md-2">
            <label for="numero">Número*</label>
            <input type="text" class="form-control" id="numero" name="numero">
            <div id="erro-numero" class="invalid-feedback">Campo obrigatório</div>
          </div>
          <div class="form-group col-md-5">
            <label for="uf">UF*</label>
            <select id="uf" class="form-control" name="uf">
              <option selected disabled value="">Selecione...</option>
            </select>
            <div id="erro-uf" class="invalid-feedback">Campo obrigatório</div>
          </div>
          <div class="form-group col-md-5">
            <label for="cidade">Cidade*</label>
            <select id="cidade" class="form-control" name="cidade">
              <option selected disabled value="">Selecione...</option>
            </select>
            <div id="erro-cidade" class="invalid-feedback">Campo obrigatório</div>
          </div>
        </div>
        <div class="form-group">
          <label for="bairro">Bairro*</label>
          <select id="bairro" class="form-control" name="bairro">
            <option selected disabled value="">Selecione...</option>
          </select>
          <div id="erro-bairro" class="invalid-feedback">Campo obrigatório</div>
        </div>
        <button type="submit" class="btn btn-primary">Cadastrar</button>
      </form>
      <script src="app.js" type="module"></script>
</body>
</html>
