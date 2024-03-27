<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cadastro</title>
    <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>

    <div class="campo">
        <h1 id="titulo">Cadastro de DEVs</h1>
        <p id="subtitulo"><strong>Complete suas informações</strong></p>
        <br>
    </div>
   <form>
       
               <fieldset class="grupo">
                   <div class="campo">
                       <label for="Nome"><strong>Nome</strong></label>
                       <input type="text" name="nome" id="nome" required>
                   </div>

                   <div class="campo">
                       <label for="Sobrenome"><strong>Sobrenome</strong></label>
                       <input type="text" name="Sobrenome" id="Sobrenome" required>
                   </div>
               </fieldset>

               <div class="campo">
                <label for="email"><strong>Email</strong></label>
                <input type="email" name="Email" id="email" required>
               </div>

               <div class="campo">
                <label><strong>De qual lado da aplicação voce desenvolve?</strong></label>
                <label>
                    <input type="radio" name="devweb" value="frontend" checked>Front-end 
                </label>
                <label>
                    <input type="radio" name="devweb" value="backend">Back-end 
                </label>
                <label>
                    <input type="radio" name="devweb" value="fullstack">Fullstack
                </label>
               </div>

               <div class="campo">
                <label for="senioridade"><strong>Senioridade</strong></label>
                <select name="Senioridade" id="senioridade">
                    <option selected disabled value="">Selecione</option>
                    <option>Junior</option>
                    <option>Pleno</option>
                    <option>Senior</option>
                </select>
               </div>

               <fieldset class="grupo">
                <div id="checkbox">
                    <label><strong>Selecione as tecnologias que utiliza:</strong></label><br><br>
                    <input type="checkbox" id="tecnologia1" name="tecnologia1" value="HTML">
                    <label for="tecnologia1">HTML</label>
                    <input type="checkbox" id="tecnologia2" name="tecnologia2" value="CSS">
                    <label for="tecnologia2">CSS</label>
                    <input type="checkbox" id="tecnologia3" name="tecnologia3" value="JavaScript">
                    <label for="tecnologia3">JavaScript</label>
                    <input type="checkbox" id="tecnologia4" name="tecnologia4" value="PHP">
                    <label for="tecnologia4">PHP</label>
                    <input type="checkbox" id="tecnologia5" name="tecnologia5" value="C#">
                    <label for="tecnologia5">C#</label>
                    <input type="checkbox" id="tecnologia6" name="tecnologia6" value="Python">
                    <label for="tecnologia6">Python</label>
                    <input type="checkbox" id="tecnologia7" name="tecnologia7" value="Java">
                    <label for="tecnologia7">Java</label>
                </div>
               </fieldset>

               <div class="campo">
                <br>
                <label><strong>Conte um pouco da sua experiencia:</strong></label>
                <textarea rows="6" style="width: 26em" id="experiencia" name="experiencia"></textarea>
               </div>
               <button class="botao" type="submit"><strong>Concluido</strong></button>
   </form>

    
</body>
</html>
