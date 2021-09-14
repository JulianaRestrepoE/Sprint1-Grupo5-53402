# Sprint1-Grupo5-53402
Grupo 5 - 53402
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="estilos.css">
    <title>Sprint1</title>

</head>
<body>
    <section class="form-logo">
        <h2>Logo</h2>
        <section class="form-registro">
            <h3>Registro</h3>
            <form id= "form-registro" action="index.html" method="post">
                <label for="documento">Tipo de documento</label><br>
                <select name="documento" id="documento">
                    <option value="cc">Cédula</option> 
                    <option value="ti">Tarjeta de Identidad</option>
                    <option value="pas">Pasaporte</option>
                    <option value="tresidencia">Tarjeta de Residencia</option>
                </select><br>
                <label for="numerodoc">Número de documento</label><br>
                <input type="text" name="numdocumento" id="numdocumento"><br>
                <label for="documento">Correo</label><br>
                <input type="email" name="correo" id="correo"><br>
                <label for="documento">Contraseña</label><br>
                <input type="password" name="contrasena" id="contrasena"><br>

                <button><input type="button" name="btn-registrar" id="btn-registrar" value ="Registrar"></button><br>
            </form>
        </section>   
    </section>
</body>
</html>
