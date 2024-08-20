<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8" />
    <title>Meu blog pessoal</title>
    <style>
        body {
            background-color: white;
            font-family: Arial, Helvetica, Sans-Serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        header {
            background-color: #f27f1b;
            color: white;
            text-align: center;
            padding: 1em 0;
        }

        h3 {
            border-bottom: 2px solid purple;
        }

        section {
            padding: 1em;
            margin: 0 auto;
            max-width: 800px;
            flex: 1;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
            width: 100%;
        }

        form {
            display: flex;
            flex-direction: column;
            gap: 1em;
        }

        label {
            font-weight: bold;
            margin-bottom: 0.5em;
        }

        input[type="email"],
        textarea {
            padding: 0.5em;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 1em;
            width: 100%;
            box-sizing: border-box; /* Inclui padding e border no tamanho total do elemento */
        }

        textarea {
            resize: vertical; /* Permite redimensionar verticalmente */
        }

        button {
            background-color: #f27f1b;
            color: white;
            border: none;
            padding: 0.75em 1.5em;
            border-radius: 4px;
            font-size: 1em;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        button:hover {
            background-color: #d05b1a; /* Cor um pouco mais escura para o hover */
        }

        button:focus {
            outline: 2px solid #333; /* Adiciona uma borda ao redor do botão quando ele está focado */
        }
    </style>
</head>
<body>
    <header>
        <h1>Título do blog</h1>
        <h2>Subtitle</h2>
    </header>
    <section>
        <h3>Sobre mim</h3>
        <p>
            Entusiasta em designer e programação
        </p>
        <h3>Hobbies</h3>
        <ul>
            <li>Música</li>
            <li>Filmes</li>
            <li>Desenvolvedor</li>
        </ul>
        <h3>Entre em contato:</h3>
        <form action="" method="get">
            <label for="email">Email</label>
            <input type="email" name="email" id="email" />
            
            <label for="message">Mensagem</label>
            <textarea name="message" id="message" rows="8" cols="40"></textarea>
            
            <button type="submit">Enviar</button>
        </form>
    </section>
    <footer>
        <p>
            &copy; 2024. Todos direitos reservados.
        </p>
    </footer>
</body>
</html>
