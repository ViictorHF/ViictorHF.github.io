<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Victor Hugo Ferreira</title>
    <style>
        body {
            background-color: #001219;
            color: white;
            font-size: larger;
        }
        header {
            position:relative;
            text-align:center;
            width:30%;
            height:100px;
            margin-top:-8px;
            border-bottom: 3px solid green;
        }
        nav {
            position: relative;
            text-align: center;
            float: right;
            width: 70%;
            top: 0px;
            margin-top: -100px;
            height: 240px;
        }
        a {
            text-decoration: none;
            background-color: black;
            padding: 15px;
            color: white;
            border: 3px solid;
            border-radius: 10px;
            border-color: green;
        }
        a:hover {
            background-color: #4A4A4A;
        }
        .listaNavBar {
            list-style-type: none;
        }
        .container {
            height: auto;
            display: grid;
            grid-template-columns: 900px 450px;
            grid-template-rows: 350px;
            grid-template-areas: "principal lado";
        }
        section {
            grid-area: principal;
            text-align: center;
            align-items: center;
            justify-content: center;
            margin: 10px;
            border: 5px solid;
            border-radius: 10px;
            border-color: green;
            padding: 10px;
        }
        aside {
            grid-area: lado;
            width: auto;
            text-align: center;
            align-items: center;
            justify-content: center;
            margin: 10px;
            border: 5px solid;
            border-radius: 10px;
            border-color: green;
            padding: 20px;
        }
        .foot {
            position: fixed;
            left: 0;
            bottom: 0;
            width: 100%;
            background-color: green;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Portfolio - Victor Hugo Ferreira</h1>
    </header>
    <nav>
        <ul class="listaNavBar">
            <li>
                <a href="https://github.com/ViictorHF" target="_blank">Github</a>
            </li>
        </ul>
    </nav>
    <div class="container">
        <section>
            <h2>Experiencia Academica:</h2>
            <ul>
                <li>Técnico em desenvolvimento de sistemas pelo <strong>SENAI</strong> lauro de freitas</li>
                <li>Certificado em desenvolvimento de sistemas pela Infinity School</li>
                <li>Ensino Medio no Colégio Gregor Mendel</li>
            </ul>
            <h3>Experiencia basica em ferramentas de programação:</h3>
            <ul>
                <li>Python</li>
                <li>C++</li>
                <li>HTML / CSS / JavaScript</li>
            </ul>
        </section>
        <aside>
            <h2>Objetivos:</h2>
            <ul>
                <li>Aprender mais sobre programação</li>
                <li>Trabalhar em área relacionada à jogos</li>
            </ul>
            <h3>Tenho interesse em aprender mais sobre:</h3>
            <ul>
                <li>C++</li>
                <li>Lua Scripts</li>
                <li>Ferramenta Godot</li>
            </ul>
        </aside>
    </div>
    <footer class="foot">
        <p>Portfolio - Victor Hugo Ferreira</p>
    </footer>
</body>
</html>