<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Estúdio de ensaio</title>
    <style>
       
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Sans-serif;
            color: #c9bfbf;
            background: linear-gradient(to bottom, #fffdfd, #ffffff);
            background-image: url('https://mural.blogfolha.uol.com.br/files/2019/07/IMG_2873.jpg');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
        }

        .overlay {
            background: rgba(0, 0, 0, 0.7);
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 0 10px;
        }

        header {
            text-align: center;
            padding: 30px 20px;
        }

        header h1 {
            font-size: 3.5rem;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.5rem;
            color: #ddd6d6;
        }

        .section {
            max-width: 900px;
            width: 100%;
            background: rgba(255, 255, 255, 0.05);
            margin: 20px 0;
            padding: 20px;
            border-radius: 12px;
            text-align: center;
        }

        .section h2 {
            font-size: 1.8rem;
            margin-bottom: 10px;
        }

        .section p {
            font-size: 1rem;
            line-height: 1.5;
        }

            .form-section {
            max-width: 600px;
            width: 100%;
            background: rgba(230, 225, 225, 0.08);
            margin: 30px 0;
            padding: 30px;
            border-radius: 12px;
            text-align: center;
        }

            .form-section h2 {
            margin-bottom: 15px;
            font-size: 1.8rem;
        }

        form {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        input[type="email"] {
            padding: 12px;
            border-radius: 8px;
            border: none;
            outline: none;
            font-size: 1rem;
        }

        button {
            padding: 12px;
            background: #0ba163;
            color: #fff;
            border: none;
            border-radius: 8px;
            font-size: 1rem;
            cursor: pointer;
            transition: background 0.3s;
        }

        button:hover {
            background: #b10808;
        }

                     @media (max-width: 768px) {
                    header h1 {
                     font-size: 2rem;
            }
                .section h2, .form-section h2 {
                font-size: 1.5rem;
            }
        }

                    @media (max-width: 480px) {
                    header h1 {
                    font-size: 1.5rem;
            }
                    header p {
                    font-size: 1rem;
            }
        }
    </style>
</head>
<body>
    <div class="overlay">
        <header>
            <h1>ESTÚDIO DO LAU</h1>
            <p>Ensaios e Gravações</p>
        </header>

        <div class="section">
            <h2>Quem Somos</h2>
            <p>Estúdio de música localizado Rua Alvilandia, 277, Osasco/SP - Há mais de 20 anos levando Rock n' Roll e música underground para a periferia</p>
        </div>

        <div class="section">
            <h2>Ensaios, gravações e cervejas: agende seu horário AGORA</h2>
            <p>Temos bar com diversas marcas de cervejas, duas salas climatizadas com: bateria, amplificadores e microfones de primeira linha</p>
        </div>

        <div class="section">
            <h2>Eventos e Workshops</h2>
            <p>Agende seu evento conosco: shows, workshops e aniversários. Seu evento com conforto e segurança.</p>
        </div>

        <div class="form-section">
            <h2>Mande seu e-mail que entraremos em contato ou ligue em nosso telefone (11) 3686-2557</h2>
            <form>
                <input type="email" name="email" placeholder="Digite seu e-mail" required>
                <button type="submit">Quero agendar</button>
            </form>
        </div>
    </div>
</body>
</html>
