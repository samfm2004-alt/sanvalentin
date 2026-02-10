<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Para Mi San Valentín 💙</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', sans-serif;
            background: radial-gradient(circle, #203a43, #0f2027);
            color: white;
            text-align: center;
            overflow: hidden;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .pantalla {
            position: absolute;
            width: 100%;
            height: 100%;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            transition: all 0.8s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .oculta { opacity: 0; pointer-events: none; transform: scale(0.8); }

        .carta {
            max-width: 450px;
            width: 85%;
            background: rgba(255, 255, 255, 0.1);
            padding: 30px;
            border-radius: 30px;
            backdrop-filter: blur(20px);
            box-shadow: 0 0 40px rgba(0, 198, 255, 0.2);
            border: 1px solid rgba(255, 255, 255, 0.3);
            max-height: 85vh;
            overflow-y: auto;
        }

        .foto-drive {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid #00c6ff;
            margin-bottom: 15px;
        }

        .recuerdo-item {
            background: rgba(0, 198, 255, 0.05);
            margin: 10px 0;
            padding: 12px;
            border-radius: 15px;
            border-left: 4px solid #00c6ff;
            text-align: left;
            font-size: 14px;
        }

        button {
            padding: 14px 30px;
            border: none;
            border-radius: 50px;
            background: linear-gradient(45deg, #00c6ff, #0072ff);
            color: white;
            font-weight: bold;
            cursor: pointer;
            transition: 0.3s;
            font-size: 16px;
            margin: 10px;
        }

        #btnSi { transition: all 0.2s ease; z-index: 1000; }
        #btnNo { background: #ff4b2b; position: relative; transition: 0.2s; }

        .corazon {
            position: absolute;
            pointer-events: none;
            animation: subir 6s linear infinite;
            z-index: -1;
        }

        @keyframes subir {
            0% { transform: translateY(110vh) scale(0); opacity: 0; }
            100% { transform: translateY(-10vh) scale(1.2); opacity: 0; }
        }
    </style>
</head>
<body>

    <audio id="musicaFondo" loop>
        <source src="https://docs.google.com/uc?export=download&id=1jdFpmeUf4Mx45bMiG1M5wdvCjkp8TP3g" type="audio/mpeg">
    </audio>

    <div id="p1" class="pantalla">
        <div class="carta">
            <img src="https://docs.google.com/uc?export=download&id=1F9mykC5-Clu2IhqSfEhwhnikP73LXuO5" class="foto-drive">
            <h2 style="color: #00c6ff;">Hola, mi amor 💙</h2>
            <p>He preparado algo especial para ti. ¿Me dejas mostrártelo?</p>
            <button onclick="iniciar()">Empezar 💙</button>
        </div>
    </div>

    <div id="p2" class="pantalla oculta">
        <div class="carta">
            <h2>Pregunta seria...</h2>
            <p>¿Quieres ser mi San Valentín este año? 💙</p>
            <div style="margin-top: 30px;">
                <button id="btnSi" onclick="aceptar()">¡SÍ! 😍</button>
                <button id="btnNo" onmouseover="huir()" onclick="huir()">No</button>
            </div>
        </div>
    </div>

    <div id="p3" class="pantalla oculta">
        <div class="carta">
            <h2 style="color: #00c6ff;">¡Lo sabía! 😍</h2>
            <p>Eres lo mejor que me ha pasado. Aquí tienes algunas cosas que me encantan de ti:</p>
            <div class="recuerdo-item">✨ <b>Tu sonrisa:</b> Es mi motor de cada día.</div>
            <div class="recuerdo-item">✨ <b>Tu inteligencia:</b> Admiro cómo ves el mundo.</div>
            <div class="recuerdo-item">✨ <b>Tu apoyo:</b> Estás conmigo en las buenas y malas.</div>
            <div class="recuerdo-item">✨ <b>Tu caballerosidad:</b> Me haces sentir única.</div>
            <button onclick="navegar('p3', 'p4')">Sigue leyendo... 💙</button>
        </div>
    </div>

    <div id="p4" class="pantalla oculta">
        <div class="carta">
            <h1 style="font-size: 30px; color: #00c6ff;">¡TE AMO!</h1>
            <p>Gracias por aceptar ser mi San Valentín.</p>
            <div style="font-size: 50px;">💙👩‍❤️‍👨💙</div>
            <p>Prometo hacerte muy feliz hoy y siempre.</p>
        </div>
    </div>

    <script>
        const audio = document.getElementById("musicaFondo");
        const btnSi = document.getElementById("btnSi");
        const btnNo = document.getElementById("btnNo");
        let escalaSi = 1;
        const frasesNo = ["¿Seguro? 🥺", "¡Piénsalo bien!", "¡Inténtalo de nuevo!", "¡Casi me das!", "Error 404 🚫", "¡Nop! 😜"];

        function iniciar() {
            audio.play();
            navegar('p1', 'p2');
        }

        function navegar(actual, siguiente) {
            document.getElementById(actual).classList.add("oculta");
            document.getElementById(siguiente).classList.remove("oculta");
        }

        function huir() {
            // Mover botón No
            const x = Math.random() * (window.innerWidth - 100) - (window.innerWidth / 2 - 50);
            const y = Math.random() * (window.innerHeight - 100) - (window.innerHeight / 2 - 50);
            btnNo.style.transform = `translate(${x}px, ${y}px)`;
            btnNo.innerText = frasesNo[Math.floor(Math.random() * frasesNo.length)];
            
            // Crecer botón Sí
            escalaSi += 0.4;
            btnSi.style.transform = `scale(${escalaSi})`;
        }

        function aceptar() {
            navegar('p2', 'p3');
        }

        function crearCorazon() {
            const c = document.createElement("div");
            c.className = "corazon";
            c.innerHTML = "💙";
            c.style.left = Math.random() * 100 + "vw";
            c.style.fontSize = (Math.random() * 20 + 10) + "px";
            document.body.appendChild(c);
            setTimeout(() => c.remove(), 6000);
        }
        setInterval(crearCorazon, 300);
    </script>
</body>
</html>
