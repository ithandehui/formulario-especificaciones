<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <title>Iniciar sesión</title>
  <style>
    body {
      font-family: sans-serif;
      background-color: #f5f5f5;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
    }
    .login-box {
      background: white;
      padding: 30px;
      border-radius: 8px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      width: 300px;
    }
    input, button {
      width: 100%;
      margin: 10px 0;
      padding: 10px;
      font-size: 16px;
    }
    button {
      background-color: #9F2241;
      color: white;
      border: none;
      cursor: pointer;
    }
    button:hover {
      background-color: #801b35;
    }
    .error {
      color: red;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <div class="login-box">
    <h2>Iniciar sesión</h2>
    <input type="email" id="correo" placeholder="Correo electrónico" required />
    <input type="password" id="password" placeholder="Contraseña" required />
    <button onclick="login()">Ingresar</button>
    <div id="error" class="error"></div>
  </div>

  <script>
    async function login() {
      const correo = document.getElementById('correo').value;
      const password = document.getElementById('password').value;
      const errorDiv = document.getElementById('error');

      const response = await fetch('http://35.226.84.73:5000/login', {
  method: 'POST',
  headers: { 'Content-Type': 'application/json' },
  body: JSON.stringify({ correo, password })
});

      const result = await response.json();

      if (result.status === 'ok') {
        window.location.href = 'formulario.html';
      } else {
        errorDiv.textContent = 'Correo o contraseña incorrectos';
      }
    }
  </script>
</body>
</html>
