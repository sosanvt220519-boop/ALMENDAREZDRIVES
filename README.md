# ALMENDAREZDRIVES
Viajes privados y ejecutivo 
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>José Antonio Almendarez | Chofer Privado</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --primary-dark: #1a1a1a;
            --accent-gold: #c5a059;
            --whatsapp-green: #25d366;
            --white: #ffffff;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            background-color: #f4f4f4;
            color: var(--primary-dark);
            line-height: 1.6;
        }

        header {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1549317661-bd32c8ce0db2?auto=format&fit=crop&q=80&w=1000') no-repeat center center/cover;
            height: 60vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: var(--white);
            padding: 20px;
        }

        .profile-card {
            background: var(--white);
            max-width: 500px;
            margin: -50px auto 30px;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            text-align: center;
        }

        h1 { margin-bottom: 5px; color: var(--primary-dark); }
        .subtitle { color: var(--accent-gold); font-weight: bold; text-transform: uppercase; letter-spacing: 2px; }

        .info-section { padding: 20px; }
        .info-item { margin-bottom: 15px; font-size: 1.1em; }
        .info-item i { color: var(--accent-gold); margin-right: 10px; }

        .btn-whatsapp {
            display: inline-block;
            background-color: var(--whatsapp-green);
            color: white;
            padding: 15px 30px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.2em;
            transition: transform 0.3s ease;
            margin: 10px;
        }

        .btn-whatsapp:hover { transform: scale(1.05); }

        .payment-methods {
            background: #eee;
            padding: 15px;
            border-radius: 10px;
            margin-top: 20px;
            font-size: 0.9em;
        }

        .floating-wa {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: var(--whatsapp-green);
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            font-size: 30px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.3);
            z-index: 1000;
        }
    </style>
</head>
<body>

    <header>
        <div style="font-size: 4em; margin-bottom: 10px;"><i class="fas fa-car"></i></div>
        <p>Servicio Ejecutivo en Nissan Versa (Nueva Generación)</p>
    </header>

    <div class="profile-card">
        <h1>José Antonio Almendarez</h1>
        <p class="subtitle">Chofer Privado y Ejecutivo</p>
        
        <div class="info-section">
            <div class="info-item"><i class="fas fa-phone"></i> 81 2287 1916</div>
            <div class="info-item"><i class="fas fa-envelope"></i> joseantonioalmendarezsosa@gmail.com</div>
        </div>

        <p><strong>¿Necesitas una cotización?</strong></p>
        
        <a href="https://wa.me/528122871916?text=Hola%20José%20Antonio,%20me%20gustaría%20solicitar%20una%20cotización." class="btn-whatsapp">
            <i class="fab fa-whatsapp"></i> Contactar Línea 1
        </a>

        <div class="payment-methods">
            <i class="fas fa-money-bill-wave"></i> Pago en efectivo y transferencia
        </div>
    </div>

    <a href="https://wa.me/528122871916" class="floating-wa" target="_blank">
        <i class="fab fa-whatsapp"></i>
    </a>

</body>
</html>
