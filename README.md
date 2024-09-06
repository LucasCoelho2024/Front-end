# Front-end
// pagina.html

<!DOCTYPE html>
<html lang="pt-BR">
    <head>
        <meta charset="UTF-8">
        <title>Formulario Central do Atleta</title>
        <link rel="stylesheet" href="formulario.css">
     </head>
<body>
    <div class="principal">
    <h1>Formulario Exemplo</h1>
    <form>
        <div class="layoutCA">
        <label form="nome">Nome Completo</label>
        <input type="text" name="nome"
        placeholder="Digite seu nome aqui">
        </div>
        <div Class="layoutCA">
        <label form="email">E-mail</label>
        <input type="email" name="email" placeholder="Digite o seu e-mail">
        </div>
        <div class="layoutCA">
        <label form="senha">Senha</label>
        <input type="password" name="senha" placeholder="Digite sua senha">
        </div>
        <div Class="layoutCA">
        <label form="telefone">Telefone</label>
        <input type="tel" name="telefone" placeholder="Digite o seu telefone">
        </div>
        <div class="layoutCA">
        <label form="site">Site</label>
        <input type="url" name="site" placeholder="Digite o seu site">
        </div>
        <div class="layoutCA">  
        <label form="nascimento">Data Nascimento</label>
        <input type="date" name="nascimento" placeholder="Digite sua data de nascimento">
        </div>
        <div class="layoutCA">
        <label form="cor">Cor Favorita</label>
        <input type="color" name="cor" value="blue">
        </div>
        <div class="layoutCA">
        <label form="quantidade">quantidade</label>
        <input type="number" name="quantidade" min="1" max="20" value="1">  
        </div>
        <div class="layoutCA">
        <label form="cor">Nivel de Satisfação</label>
        <input type="range" name="nivel" min="0" max="10">
        </div>
        <div class="layoutCA">
        <label form="arquivo">Anexo Curriculo</label>
        <input type="file" name="arquvio">
        </div>
        <div class="layoutCA">
        <label form="SMS">Receber SMS</label>
        <input type="checkbox" name="SMS">
        </div>
        <div class="layoutCA">
        <input type="radio" name="genero" value="masculino">
        <label form="masculino">masculino</label>
        <input type="radio" name="genero" value="feminino">
        <label forme="feminino">feminino</label>
        </div>
        <div class="layoutCA">
        <button type="submit">Enviar</button>
        <button type="reset">Limpar</button>
        </div>
    </div>
    </form>
</body>
</html>
