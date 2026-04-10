<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contacto - Harmony Staffing Agency</title>
    <style>
        /* ESTILOS GLOBALES - Simulan el fondo y centrado del volante original */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f2f5; /* Color de fondo claro similar al volante */
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        /* CONTENEDOR PRINCIPAL - Simula el ancho y padding del pie del volante */
        .harmony-footer {
            background-color: white; /* El "papel" del volante */
            width: 100%;
            max-width: 600px; /* Ancho máximo para que se vea bien en web */
            padding: 40px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            border-radius: 8px;
            text-align: center;
        }

        /* ESTILO DEL LOGO RECREADO */
        .harmony-logo {
            font-size: 48px;
            font-weight: bold;
            color: #1a4da3; /* Azul Harmony */
            margin-bottom: 5px;
        }
        .harmony-logo .plus {
            color: #f39c12; /* Naranja Harmony */
            margin-left: 2px;
        }
        .agency-text {
            color: #f39c12; /* Naranja Harmony */
            font-size: 14px;
            text-transform: uppercase;
            letter-spacing: 2px;
            margin-bottom: 30px;
            margin-top: -10px;
        }

        /* CONTENEDOR DE INFORMACIÓN DE CONTACTO */
        .contact-grid {
            display: grid;
            grid-template-columns: 1fr 1fr; /* Dos columnas */
            gap: 20px;
            text-align: left;
            margin-bottom: 25px;
        }

        /* TÍTULOS DE SECCIÓN */
        .contact-title {
            color: #f39c12; /* Naranja Harmony */
            font-weight: bold;
            font-size: 18px;
            margin-bottom: 10px;
            grid-column: 1 / -1; /* Ocupa todo el ancho */
        }

        /* ESTILOS PARA LOS ENLACES DE CONTACTO */
        .contact-item {
            display: flex;
            align-items: center;
            margin-bottom: 8px;
            font-size: 15px;
            color: #333;
        }
        
        .contact-item a {
            text-decoration: none; /* Quita el subrayado */
            color: inherit; /* Mantiene el color del texto */
            transition: color 0.2s; /* Efecto suave al pasar el ratón */
        }

        .contact-item a:hover {
            color: #1a4da3; /* Cambia a azul al pasar el ratón */
            text-decoration: underline; /* Añade subrayado solo al hover */
        }

        /* ICONOS UNIFORMES (Simplificados) */
        .icon-placeholder {
            width: 25px;
            margin-right: 10px;
            text-align: center;
            font-size: 18px;
        }

        /* DIRECCIÓN AL FINAL */
        .address {
            color: #f39c12; /* Naranja Harmony */
            font-size: 13px;
            font-weight: bold;
            border-top: 2px solid #eee;
            padding-top: 15px;
            margin-top: 10px;
        }

        /* Adaptación para pantallas pequeñas */
        @media (max-width: 480px) {
            .contact-grid {
                grid-template-columns: 1fr; /* Una columna en móvil */
            }
            .right-col .contact-item {
                justify-content: flex-start; /* Alinea a la izquierda en móvil */
            }
        }
        
        /* Ajuste específico para la columna derecha para alinear a la derecha como en la imagen original */
        .right-col {
            text-align: right;
            display: flex;
            flex-direction: column;
            align-items: flex-end;
        }
    </style>
</head>
<body>

    <div class="harmony-footer">
        
        <div class="harmony-logo">
            harmony<span class="plus">+</span>
        </div>
        <div class="agency-text">STAFFING AGENCY</div>

        <div class="contact-title">Contact us:</div>

        <div class="contact-grid">
            
            <div class="left-col">
                <div class="contact-item">
                    <span class="icon-placeholder">📞</span>
                    <a href="tel:+17863372365">(+1) 786 337 2365</a>
                </div>
                <div class="contact-item">
                    <span class="icon-placeholder">📞</span>
                    <a href="tel:+17863797275">(+1) 786 379 7275</a>
                </div>
                <div class="contact-item">
                    <span class="icon-placeholder">👤</span>
                    KATIA MENDEZ
                </div>
            </div>

            <div class="right-col">
                <div class="contact-item">
                    <a href="https://www.instagram.com/jobharmonypls/" target="_blank">@jobharmonypls</a>
                    <span class="icon-placeholder" style="margin-right:0; margin-left:10px;">📸</span>
                </div>
                <div class="contact-item">
                    <a href="https://www.facebook.com/harmonyplus.staffing/" target="_blank">harmony plus</a>
                    <span class="icon-placeholder" style="margin-right:0; margin-left:10px;">📘</span>
                </div>
                <div class="contact-item">
                    <a href="mailto:Info@harmonypls.com">Info@harmonypls.com</a>
                    <span class="icon-placeholder" style="margin-right:0; margin-left:10px;">✉️</span>
                </div>
            </div>
            
        </div>

      <div class="visitor-counter">
    <span class="counter-label"></span>
    <span id="numero-visitas" class="counter-number">...</span>
</div>
</body>
</html>
