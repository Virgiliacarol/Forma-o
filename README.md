<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>GitHub App</title>
</head>
<body>
    <header>
        <h1>GitHub App</h1>
        <nav>
            <ul>
                <li><a href="#">Início</a></li>
                <li><a href="#">Sobre</a></li>
                <li><a href="#">Contato</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="repo-form">
            <h2>Criar Novo Repositório</h2>
            <form>
                <input type="text" placeholder="Nome do repositório" required>
                <textarea placeholder="Descrição do repositório"></textarea>
                <button type="submit">Criar Repositório</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 GitHub App</p>
    </footer>
</body>
</html>

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

header {
    background-color: #24292e;
    color: white;
    padding: 10px 20px;
}

nav ul {
    list-style-type: none;
    display: flex;
}

nav ul li {
    margin-right: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

.repo-form {
    padding: 20px;
}

input[type="text"],
textarea {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    border: 1px solid #ddd;
    border-radius: 4px;
}

button {
    background-color: #28a745;
    color: white;
    padding: 10px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

button:hover {
    background-color: #218838;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #f1f1f1;
}

/* Responsividade */
@media (min-width: 600px) {
    nav ul {
        justify-content: flex-end;
    }

    .repo-form {
        max-width: 600px;
        margin: auto;
    }
}
