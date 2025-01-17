<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Farmácia Drogalaura</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff;
            color: #333;
        }
        header {
            background-color: #c40101;
            padding: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            color: white;
        }
        h1 {
            margin: 0;
        }
        .container {
            display: flex;
            padding: 20px;
            gap: 20px;
        }
        .left-column, .right-column {
            flex: 1;
        }
        .image-container {
            text-align: left;
        }
        .image-container img {
            max-width: 100%;
            height: auto;
			margin-bottom: 5px;
			margin-left: 10px;
        }
        .button {
            display: block;
            width: 300px;
            height: 50px;
            color: white;
            text-align: center;
            line-height: 50px;
            font-size: 18px;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 5px;
            background-color: #25d366;
			text-align: left;
			padding-left: 50px;
			margin-left: 10px
        }
        .button:hover {
            background-color: #128c7e;
        }
        .header-button {
            display: inline-block;
            padding: 10px 20px;
            font-size: 18px;
            font-weight: bold;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin-left: 10px;
        }
        .header-whatsapp-button {
            background-color: #25d366;
        }
        .header-whatsapp-button:hover {
            background-color: #128c7e;
        }
        .header-instagram-button {
            background-color: #6f42c1;
        }
        .header-instagram-button:hover {
            background-color: #5a3398;
        }
        .location {
            text-align: left;
            margin-top: 20px;
        }
        footer {
            background-color: #c40101;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <div>
            <h1>FARMÁCIA DROGA LAURA</h1>
            <p>SUA SAÚDE, NOSSA MISSÃO</p>
        </div>
        <div>
            <a href="https://wa.me/558288215583" class="header-button header-whatsapp-button" target="_blank">WhatsApp</a>
            <a href="https://www.instagram.com/droga_laurasd" class="header-button header-instagram-button" target="_blank">Instagram</a>
        </div>
    </header>

    <div class="container">
        <div class="left-column">
            <div class="image-container">
                <img src="https://uploaddeimagens.com.br/images/004/883/634/original/img3.jpeg?1737145367" width="3500" height="200" alt="Imagem da Farmácia">
                <!-- Botão adicionado após a imagem -->
                <a href="https://wa.me/558288215583" class="button" target="_blank">Fale conosco no WhatsApp</a>
            </div>
        </div>
        <div class="right-column">
            <div class="location">
                <p>VISITE NOSSA LOJA:</p>
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d31476.235280010384!2d-35.793302999999995!3d-9.549549500000001!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x70149ed9312dd4b%3A0x809092066d202eb1!2sDROGA%20LAURA!5e0!3m2!1sen!2sbr!4v1737116209223!5m2!1sen!2sbr" 
                    width="500" 
                    height="500" 
                    style="border:0;" 
                    allowfullscreen="" 
                    loading="lazy" 
                    referrerpolicy="no-referrer-when-downgrade">
                </iframe>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 Farmácia Drogalaura - Todos os direitos reservados</p>
    </footer>
</body>
</html>
