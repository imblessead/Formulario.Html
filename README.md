# Formulario.Html
Formulario

<html>
<head></head>
    <body>
        <h2><center> formulario</center></h2>
        <form method ="post">
            <fieldset>
                <legend>Dados e login:</legend>
            <label for="txtnome">nome: </label>
            <input type="text"name="nome" id ="nome"><br><br>
            <label for="senha">senha: </label>
            <input type=""password" name ="senha" id ="senha"> <br><br>
            </fieldset>
            <br>

            <fieldset>
                <legend>Sexo :</legend>
                <p>
                    <input type="Radio" name="Sexo" id="Sexo">
                    <label for="Sexo">femenino</label>
                </p>
                <p>
                    <input type="radio" name="sexo" id="sexo">
                    <label for="sexo">masculino </label>
                </p>
            </fieldset>
            <br><br>
            <fieldset>
                <legend>Interesses:</legend>
                <p>
                    <input type="checkbox" name="interesse" id="chkinteresse1">
                    <label for="chkinteresse1"> Carros</label>
            </p>
                <p> 
                    <input type="checkbox" name="interesse" id="chkinteresse2">
                    <label for="chkinteresse2"> Viagens</label>
            </p>
                <p>
                    <input type="checkbox" name="interesse" id="chkinteresse3">
                    <label for="chkinteresse3"> Gastronomia</label>
            </p>

            </fieldset>
            <br><br>
            <fieldset>
                <label for="Meusinteresse"> Seleciona interesse</label>
                <select name="Interesse2" id="ssss">
                         <optgroup label="Carros">
                              <option>BWM</option>
                              <option>Audi</option>
                              <option>Chevrolet</option>
                              <option>ferrari</option>
                        </optgroup>
                        <optgroup label="Viagens">
                             <option>Nova York</option>
                             <option>Miami</option>
                        </optgroup>
                        <optgroup label="Gastronomia">
                             <option>Comida Japonesa </option>
                             <option> Carnes</option>
                        </optgroup>
                 </select> 
                 </fieldset>
            
            

            <br><br>
            <label for="areal">Descreva o seu comentario </label><br>
            <textarea id="areal" name="comentario" rows="3" cols ="30">asd</textarea><br><br>
            <button type=""button">Logar</button>
            <button type ="Reset" Disabled="true">Cancelar</button>


            
        </form>
    </body>


</html>
