# FrontEndS2
Misiones de la Segunda semana de Front End
# Pagina del Cliente
---------------------------------------------------------------------------------------------------------------------------------------------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial=scale=1.0">
    <title>Bienvenido Cliente</title>
</head>
<body>
    <center><img src="SWEETS.png" alt="Logo" longdesc="sweetsstars.html" height="150px" width="150px"></center>
    <center><h1>Bienvenido a Sweets Stars!</h1></center>
    <form action="pedido.js" method="post" target="_blank">
        <p>
        <h2>Escoga el Sabor de pastel que guste:</h2>
        <ol>
            <label><input type="checkbox" name="chocolate" value="200"> Chocolate - $200 <br><input type="number" id="cuantos" name="cuantos" value="cuantos"></label><br><br>
            <label><input type="checkbox" name="fresa" value="240"> Fresa - $240 <br><input type="number" id="cuantos" name="cuantos" value="cuantos"></label><br><br>
            <label><input type="checkbox" name="maracuya" value="300"> Maracuya - $300 <br><input type="number" id="cuantos" name="cuantos" value="cuantos"></label><br><br>
            <label><input type="checkbox" name="estrellas" value="270"> Estrellas - $270 <br><input type="number" id="cuantos" name="cuantos" value="cuantos"></label><br><br>
            <label><input type="checkbox" name="vainilla" value="180"> Vainilla - $180 <br><input type="number" id="cuantos" name="cuantos" value="cuantos"></label><br><br>
        </ol>
        <h3>Puede agregar mas sabores:</h3>
        <ol>
            <label><input type="radio" name="maschocolate">Chocolate + $90</label><br>
            <label><input type="radio" name="masmaracuya">Maracuya + $100</label><br>
            <label><input type="radio" name="masfresa">Fresa + $70</label><br>
            <label><input type="radio" name="masvainilla">Vainilla + $50</label><br>
        </ol>
        <h3>Ahora Seleccione el decorado:</h3>
        <label><input type="checkbox" name="canasta" value="canasta">Decoración en forma de canasta. - $90</label><br>
        <p>Especial para reuniones familiares<br>
            porque guardan un toque de elegancia <br>
            y un diseño tranquilo</p>
        <label><input type="checkbox" name="naked" value="naked">Naked cake.</label><br>
        <p>Pastel Sin decoracion.<br>
        </p>
         <label><input type="checkbox" name="3d" value="3d">Texturizados. - $190</label><br>
        <p>Con formas en 3D.<br>
        </p>   
        <h3>Puede combinar los decorados por un costo adicional:</h3>
        <ol>
            <label><input type="radio" name="mascanasta">Canasta + $90</label><br>
            <label><input type="radio" name="mastexturizado">Tecturizado + $190</label><br>
        </ol>
        <h2>Ingrese sus Datos</h2>
        <!--Entradas-->
        <label for="nombre">Nombre Completo:</label> <br>
        <input type="text" id="nombre" name="nombre" placeholder="Nombre"> <br><br>
        <label for="correo">Correo Electronico:</label> <br>
        <input type="email" id="correo" name="correo"> <br><br>
        <label for="celular">Numero de Celular:</label> <br>
        <input type="number" id="numero" name="celular" > <br><br>
        <label for="direccion">Direccion:</label> <br>
        <input type="text" id="direccion" name="direccion" > <br><br>
        <label for="direccion">Descripcion que tendra el pastel:</label> <br>
        <input type="text" id="descripcion" name="descripcion" > <br><br>
        <input type="button" name="siguiente" value="Aceptar">
        </p>
    </form>
    <footer  style="width:100%; margin-left: 0px;"  >
        <div class="copyright" style="background-color: #0d47a1;">
            <div class="container-fluid" style="background-color: #0d47a1; color: #bbdefb;">
                Direccion: Av. Galatica 889, Plaza Carl Sagan<br>
                Telefono: 553321477<br>
                Horario de Atencion: Lunes a Viernes de 08:00 a 20:00<br>
            </div>
        </div>
</body>
</html>


#Pagina de Pastelero
---------------------------------------------------------------------------------------------------------------------------------------------------------------------

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial=scale=1.0">
    <title>Bienvenido Administrador</title>
</head>
<body>
    <center><img src="SWEETS.png" alt="Logo" longdesc="sweetsstars.html" height="150px" width="150px"></center>
    <center><h1>Bienvenido a Sweets Stars!</h1></center>
    <form action="pastelero.js" method="post" target="_blank">
        <p>
        <h2>Este es el stock que queda para los sabores:</h2>
        <ol>
            <label for="schocolate">Chocolate - 25kg</label> <br>
            <label for="smaracuya">Maracuya - 5kg</label> <br>
            <label for="sfresa">Fresa - 4kg</label> <br>
            <label for="svainilla">Vainilla - 1.2Lt</label> <br>
        </ol>
        <p>
        <h2>Este es el stock para realizar la decoracion:</h2>
        <ol>
            <label for="schantilly">Crema Chantilly - 10 Lt</label> <br>
            <label for="sdulces">Dulces - 7kg</label> <br>
            <label for="sgalleta">Galletas - 2kg</label> <br>
            <label for="spastaballina">Pasta Ballina - 10kg</label> <br>
        </ol>
        <h2>Tabla de Pedidos:</h2>
        <table border="1" class="default">
            <tr>
              <th scope="row">Día</th>
              <th>Lunes</th>
              <th>Marte</th>
              <th>Miércoles</th>
              <th>Jueves</th>
              <th>Viernes</th>
            </tr>
            <tr>
              <th>Sabor</th>
              <td>Chocolate</td>
              <td>Maracuya</td>
              <td>Fresa</td>
              <td>Vainilla</td>
              <td>Chocolate</td>
            </tr>
            <tr>
              <th>Decorado</th>
              <td>Naked cake</td>
              <td>Texturizados</td>
              <td>Canasta</td>
              <td>Texturizados</td>
              <td>Texturizados</td>
            </tr>
            <tr>
              <th>Delivery</th>
              <td>Si</td>
              <td>Si</td>
              <td>Si</td>
              <td>No</td>
              <td>Si</td>
            </tr>
          </table>
        </p>
    </form>
    <footer  style="width:100%; margin-left: 0px;"  >
        <div class="copyright" style="background-color: #0d47a1;">
            <div class="container-fluid" style="background-color: #0d47a1; color: #bbdefb;">
                Direccion: Av. Galatica 889, Plaza Carl Sagan<br>
                Telefono: 553321477<br>
                Horario de Atencion: Lunes a Viernes de 08:00 a 20:00<br>
            </div>
        </div>
</body>
</html>
