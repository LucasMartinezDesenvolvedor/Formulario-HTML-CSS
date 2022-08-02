# Formulario-HTML-CSS
<!DOCTYPE html>
<html lang="en">
</head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Cadastro</title>
</head>
<body>

    <div>
        <h1 id="titulo">Cadastro De DEVs</h1>
        <p id="subtitulo">Complete as suas informações</p>
        <br>
    </div>
    <br>
<form>
<fieldset class="grupo">
    <div class="campo">
        <label for="nome"><strong>nome</strong></label>
        <input type="text" name="nome" id="nome">
    </div class="campo">
<p>
    <div class="campo">
        <label for="Sobrenome"><strong>Sobrenome</strong></label>
        <input type="text" name="Sobrenome" id="Sobrenome">
    </div>
<p>
    <div class="campo">
    <label for="Email"><strong>Email</strong></label>
    <input type="email" name="email" id="email">
    </div class="campo">
<form>
<p>

<div class="Campo">
    <label></label></strong>De qual Lado da aplicação você Desenvolve<strong></strong></label>
    <label>
        <br>
        <input type="radio" name="devweb" value="Front-End" checked>Front-End
        <br>
        <input type="radio" name="devweb" value="Back-End">Back-End
        <br>
        <input type="radio" name="devweb" value="Full-Stack">Full-Stack
    </label>
</div class="Campo">

<div>
    <label>Senioridade</label>
    <select id="Senioridade">
<br>
<option>Junior</option>
<option>Pleno</option>
<option>Sênior</option>
<option selected disabled value="">Escolha</option>
<br><br><br>  
</div>
<p></p>
<br>
<fieldset>
    <div>
      <label>Selecione as tecnologias que utiliza:</label>
      <input  type="checkbox" id="tecnologia1" name="tecnologia1" value="HTML">
      <label for="tecnologia1">HTML</label>
      <input type="checkbox" id="tecnologia2" name="tecnologia2" value="CSS">
      <label for="tecnologia2">CSS</label>
      <input type="checkbox" id="tecnologia3" name="tecnologia3" value="Javascript">
      <label for="tecnologia3">Javascript</label>
      <input type="checkbox" id="tecnologia4" name="tecnologia4" value="PHP">
      <label for="tecnologia4">PHP</label>
     <input type="checkbox" id="tecnologia5" name="tecnologia5" value="C#">
     <label for="tecnologia5">C#</label>
     <input type="checkbox" id="tecnologia6" name="tecnologia6" value="Python">
     <label for="tecnologia6">Python</label>
     <input type="checkbox" id="tecnologia7" name="tecnologia7" value="Java">
     <label for="tecnologia7">Python</label>
    </div>
</fieldset>

<div>
    <br>
    <label>Conte um pouco da sua experiencia</label>
    <textarea row="6" style="width:26 em" id="experiência" name="experiencia"></textarea>
</div>

<button type="submit">Formulario Concluido Com Sucesso!!</button>

<form>

</body>
</html>
