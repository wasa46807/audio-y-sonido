<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Deja de molestar</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <main class="center">
    <h1 class="big">DEJA DE MOLESTAR</h1>
    <p class="sub">Este sitio existe solo para dejarlo claro. 😎</p>
    <button id="toggle">¿Otra vez?</button>
  </main>

  <script>
    // pequeño toque interactivo
    const btn = document.getElementById('toggle');
    const h1 = document.querySelector('.big');
    btn.addEventListener('click', () => {
      h1.textContent = h1.textContent === 'DEJA DE MOLESTAR' ? 'YA BASTA' : 'DEJA DE MOLESTAR';
    });
  </script>
</body>
</html>
