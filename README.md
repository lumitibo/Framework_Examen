# Framework
avance 1.2
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1.0"/>
    <!--Importar la fuente de los íconos de Google-->
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
    <!--Importar la hojas de estilos de materialize css-->

    <link href="css/materialize.css" type="text/css" rel="stylesheet" media="screen,projection"/>
    <link rel="stylesheet" href="css/estilos.css" media="screen,projection">

    <title>Blog de Turismo</title>
  </head>
  <body>
    <div class="col contenedor-principal">

      <div class="row barra-superior">
        <div class="col l11 offset l1 right">

          <div class="col s6 m3 l3 left">
            <img class="responsive-img logo" src="img/logo_turismo.jpeg" alt="ShareUrcode">

          </div>
          <div class="col s6 m6 l7 right contenedor-botones">
              <a class="btn btn-medium waves-effect waves-light blue-grey"><i class="material-icons left">home</i>Inicio</a>
              <a class="btn btn-medium waves-effect waves-light blue-grey"><i class="material-icons left">insert_emoticon</i>Estuve en</a>
              <a class="btn btn-medium waves-effect waves-light blue-grey"><i class="material-icons left">local_airport</i>Mejores Viajes..</a>
              <a class="btn btn-medium waves-effect waves-light blue-grey"><i class="material-icons left">thumb_up</i>Recomend</a>
          </div>
          <div class="col left">
              <p ><br><br><h3 class="texto_titulo">Creando mi propio Eslogan</h3></p>
          </div>




        </div>

      </div>


          <div class="row l12 offset s1  contenedor-imagenes">
            <div class="col l1 hide-on-small-only ">
              <div class="float-btn" style="bottom: 45px; right: 90vw;">

              <div class="card-img">
                  <img class="responsive-img imagen_float" src="img/facebook.png" alt="FaceBook">
              </div>
              <div class="card-img">
                <img class="responsive-img imagen_float" src="img/twitter.png" alt="Twiter">
              </div>
              <div class="card-img">
                <img class="responsive-img imagen_float" src="img/instagram.png" alt="Instagram">
              </div>
              <div class="card-img">
                <img class="responsive-img imagen_float" src="img/youtube.png" alt="Youtube">
              </div>
              <div class="card-img">
                <img class="responsive-img imagen_float" src="img/pint.jpg" alt="Pinteres">
              </div>

            </div>
          </div>
          <div class="col l3 ">
            <div class="card-image img1"><img class="materialboxed responsive-img" src="img/cusco.jpg" alt="Cusco"></div>
            <div class="card-image img1"><img class="materialboxed responsive-img" src="img/mexico.jpg" alt="MExico"></div>
            <div class="card-image img1 "><img class="materialboxed responsive-img " src="img/brasil.jpg" alt="Brasil"></div>
          </div>

          <div class="col l4 card-image  img1" >
            <img class="materialboxed responsive-img " src="img/torre-eiffel.jpg" alt="Torre Eiffel">
          </div>
          <div class="col l4 ">
            <div class="card-image img1  "><img class="materialboxed responsive-img " src="img/cancun.jpg" alt="Cancun"></div>
            <div class="card-image img1 "><img class="materialboxed responsive-img " src="img/brasil.jpg" alt="Brasil"></div>

          </div>
        </div>


      <div class="row contenedor-texto">
          <div class="col l7 contenedor-texto1">
            <div class="card row justify-align">

              <div class="col s12 l5 card-image">
                <img class="materialboxed responsive-img" src="img/san_francisco.jpg" alt="">
              </div>
              <div class="col l7 ">
                <p ><h4>Viajes</h4></p><p id="d1"></p>
                <p >Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure
                </p>
              </div>
            </div>
            <div class="col l12">
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            </div>

        </div>



       <div id="contenedor-texto2" class="col l4 center">
          <div class="col l12 "><img class="circle responsive-img img_autor"src="img/autor.jpg" alt="">
          </div>
          <div class="col l12 ">
            <h3>Luis Tirado</h3>
            <hr>
            <p class="center-align">Caracterizado por ser una persona responsable, fiable, con iniciativa y  pro actividad.  Capaz  de  realizar trabajo bajo presión tanto a nivel individual  como  grupal,  logrando  metas  y  objetivos  trazados. Mi formación académica  y personal  me han llevado a desenvolverme en áreas Administrativas tales  Informática, Redes, Programación, Administración de Personal y así tener conocimientos en el Manejo de los Programas tales como  Visual Basic 6.0, Power Builder 7, Visual.Net, Java y lenguajes de Programación como PHP, Javascrip, HtML. También conocimientos en Administración de Bases de Datos con SQL 2005-2008,  SQL Anywhere, MySQL.</p>
          </div>
        </div>
        <div class="col l7 contenedor-texto1">
          <div class="col l12 ">
            <form>
              <div class="input-field col s6">
                <i class="material-icons prefix">perm_identity</i>
                <input id="nombre" type="text" class="validate" required="">
                <label for="nombre">Nombre </label>
              </div>
              <div class="input-field col s6">
                <i class="material-icons prefix">email</i>
                <input id="email" type="email" class="validate">
                <label for="email" data-succes="Correcto" data-error="Debes completar este campo">Correo</label>
              </div>
              <div class="row">
                <div class="input-field col s6">
                  <i class="material-icons prefix">comment</i>
                  <textarea id="texto" class="materialize-textarea"></textarea>
                  <label for="texto">Comentario</label>
                </div>
              </div>
              <div class="col s4 right">
                <a class="btn btn-large teal blue-grey waves-effect"href="#">Enviar</a>
              </div>
            </form>
          </div>
        </div>



    </div>


    </div>
    <script src="js/vendor/jquery.js"></script>
    <script src="js/vendor/what-input.js"></script>
    <script src="js/vendor/foundation.js"></script>
    <script src="js/app.js"></script>
    <script type="text/javascript" src="https://code.jquery.com/jquery-2.1.1.min.js"></script>
    <script type="text/javascript" src="js/materialize.min.js"></script>
  </body>

  <script type="text/javascript">
  var date= new Date();
  document.getElementById("d1").innerHTML=date;
  </script>
</html>
 al 25/0/2017
