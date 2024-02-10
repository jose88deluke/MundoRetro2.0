
<!DOCTYPE html>
<html lang="es">

<head>
  <link rel="shortcut icon" href="img/logo web.png" type="image/x-icon">
  <meta charset="UTF-8">
  <style>
    body {
      justify-content: center;
      background: #100720;
    }

    #form-container {
      border-radius: 1rem;
      width: 300px;
      padding: 30px 40px;
      background-color: white;
      margin: 0 auto;
      margin-top: 100px;
      box-shadow: 0px 0px 10px 0px rgb(89, 8, 240);
    }

    input[type=text],
    input[type=password] {
      width: 100%;
      padding: 12px 20px;
      margin: 8px 0;
      display: inline-block;
      border: 1px solid #ccc;
      box-sizing: border-box;
    }

    .button {
      background-color: #4CAF50;
      color: white;
      padding: 14px 20px;
      margin: 8px 0;
      border: none;
      cursor: pointer;
      border-radius: 1rem;
      width: 100%;
      height: 60px;
      box-shadow: 0px 0px 10px 0px rgb(76, 175, 80);
    }

    button:hover {
      opacity: 0.8;
    }
  </style>
</head>

<body>
  <div id="form-container">

    <form action="inicio.html" method="post">
      <img src="img/usuario.png" alt="solid">
      <label for="uname"><b>Usuario</b></label>
      <input type="text" placeholder="Introduce su Usuario" name="uname" required>
      <img src="img/candado.png" alt="solid">
      <label for="psw"><b>Contraseña</b></label>
      <input type="password" placeholder="Introduce su Contraseña" name="psw" required>
      <div class="Contraseña">
        <label><input type="checkbox">Recordar Contraseña</label>
      </div>
      <div class="fcc-btn" href="inicio.html">
        <button type="submit" class="button"><B>Continuar</B></button>
      </div>
    </form>
  </div>
</body>

</html>
