# Para-Crespita-
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Para mi Crespita 🦁</title>
    <style>
        body { background-color: #fce4ec; font-family: sans-serif; display: flex; align-items: center; justify-content: center; height: 100vh; margin: 0; text-align: center; }
        .card { background: white; padding: 2rem; border-radius: 15px; box-shadow: 0 10px 20px rgba(0,0,0,0.1); width: 80%; max-width: 400px; }
        h1 { color: #d81b60; font-size: 1.5rem; }
        .btn-group { display: flex; justify-content: center; gap: 10px; margin-top: 20px; position: relative; }
        button { padding: 10px 20px; border: none; border-radius: 5px; cursor: pointer; font-weight: bold; }
        #si { background: #4caf50; color: white; }
        #no { background: #f44336; color: white; position: relative; }
    </style>
</head>
<body>
    <div class="card">
        <h1>¿Quieres ser mi San Valentín, Crespita? 🌹</h1>
        <p>Atte: El ganador de los Karts</p>
        <div class="btn-group">
            <button id="si">¡SÍ! 😍</button>
            <button id="no">No ☹️</button>
        </div>
    </div>
    <script>
        const btnNo = document.getElementById('no');
        const btnSi = document.getElementById('si');
        btnNo.addEventListener('mouseover', () => {
            const x = Math.random() * (window.innerWidth - btnNo.offsetWidth);
            const y = Math.random() * (window.innerHeight - btnNo.offsetHeight);
            btnNo.style.position = 'absolute';
            btnNo.style.left = x + 'px';
            btnNo.style.top = y + 'px';
        });
        btnSi.addEventListener('click', () => {
            alert('¡El hipotálamo nunca falla! Nos vemos el 14. ❤️');
            window.location.href = "https://wa.me/960193287 "; 
        });
    </script>
</body>
</html>
