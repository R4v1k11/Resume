<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Резюме</title>
    <link rel="stylesheet" href="style.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
            color: #000;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: #fff;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            font-weight: bold;
        }
        .button {
            display: inline-block;
            background: black;
            color: white;
            padding: 10px 15px;
            text-decoration: none;
            margin-right: 10px;
        }
        .about {
            display: flex;
            gap: 20px;
            margin: 20px 0;
        }
        .about img {
            width: 150px;
            height: auto;
        }
        .contacts, .skills {
            background: #ddd;
            padding: 10px;
            margin: 10px 0;
        }
        .images img {
            width: 100%;
            max-width: 400px;
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Резюме</h1>
        <p>Я создаю сайты, чтобы мне хватило на работу :)</p>
        <a href="#" class="button">Обо мне</a>
        <a href="#" class="button">Контакты</a>
        
        <h2>Обо мне</h2>
        <div class="about">
            <img src="photo.jpg" alt="Фото">
            <p>Я умею делать резюме, а еще заниматься спортом, делать сайты и играть.</p>
        </div>
        
        <h2>Контакты</h2>
        <div class="contacts">
            <p><strong>Instagram:</strong> @yourinsta</p>
            <p><strong>Email:</strong> yourmail@gmail.com</p>
        </div>
        
        <h2>Навыки</h2>
        <div class="skills">
            <p>Баскетбол, HTML, Футбол, CSS, пляжный хоккей, Git и GitHub, основы тестирования, PostMan!</p>
        </div>
        
        <div class="images">
            <img src="basketball1.jpg" alt="Баскетбол 1">
            <img src="basketball2.jpg" alt="Баскетбол 2">
        </div>
    </div>
</body>
</html>
