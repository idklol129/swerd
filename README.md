<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Фотозоны на мероприятия | [Название вашей компании]</title>
    <style>
        /* Общие стили */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        /* Шапка */
        header {
            background-color: #fff;
            padding: 1rem 0;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        header .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: #4682B4; /* Цвет логотипа */
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
        }

        nav ul li {
            margin-left: 20px;
        }

        nav ul li a {
            color: #333;
            text-decoration: none;
        }

        /* Геройский раздел */
        .hero {
            background: url('https://via.placeholder.com/1200x600/ADD8E6/FFFFFF?text=Фотозона+для+мероприятий') no-repeat center center/cover;
            color: #fff;
            text-align: center;
            padding: 5rem 0;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 0.5rem;
        }

        .hero p {
            font-size: 1.2rem;
        }

        .button {
            display: inline-block;
            background-color: #4682B4; /* Цвет кнопок */
            color: #fff;
            padding: 0.75rem 1.5rem;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 1rem;
        }

        /* Каталог фотозон */
        .catalog {
            padding: 2rem 0;
        }

        .photozones {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        .photozone {
            width: 30%;
            margin-bottom: 20px;
            background-color: #fff;
            padding: 1rem;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .photozone img {
            width: 100%;
            margin-bottom: 0.5rem;
        }

        .photozone h3 {
            margin-bottom: 0.25rem;
        }

        .photozone p {
            font-size: 0.9rem;
            color: #666;
        }

        .photozone .price {
            font-weight: bold;
            margin-top: 0.5rem;
        }

        /* О нас */
        .about {
            background-color: #ddd;
            padding: 2rem 0;
            text-align: center;
        }

        /* Контакты */
        .contacts {
            padding: 2rem 0;
            text-align: center;
        }

        .contacts form {
            max-width: 500px;
            margin: 0 auto;
        }

        .contacts form input,
        .contacts form textarea {
            width: 100%;
            padding: 0.75rem;
            margin-bottom: 1rem;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        /* Подвал */
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
        }

        /* Адаптивность */
        @media (max-width: 768px) {
            .photozones {
                flex-direction: column;
                align-items: center;
            }

            .photozone {
                width: 80%;
            }
        }
    </style>
</head>
<body>

    <header>
        <div class="container">
            <div class="logo">[Название вашей компании]</div>
            <nav>
                <ul>
                    <li><a href="#catalog">Каталог</a></li>
                    <li><a href="#about">О нас</a></li>
                    <li><a href="#contacts">Контакты</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section class="hero">
            <div class="container">
                <h1>Создадим незабываемую атмосферу на вашем мероприятии!</h1>
                <p>Аренда и изготовление фотозон любой сложности.</p>
                <a href="#catalog" class="button">Посмотреть фотозоны</a>
            </div>
        </section>

        <section class="catalog" id="catalog">
            <div class="container">
                <h2>Наши фотозоны</h2>
                <div class="photozones">
                    <div class="photozone">
                        <img src="" alt="Фотозона 1">
                        <h3>Тематическая фотозона</h3>
                        <p>Описание тематической фотозоны.</p>
                        <p class="price">от 5000 руб.</p>
                        <a href="#contacts" class="button">Заказать</a>
                    </div>
                    <div class="photozone">
                        <img src="" alt="Фотозона 2">
                        <h3>Фотозона с цветами</h3>
                        <p>Описание фотозоны с цветами.</p>
                        <p class="price">от 7000 руб.</p>
                        <a href="#contacts" class="button">Заказать</a>
                    </div>
                    <div class="photozone">
                        <img src="" alt="Фотозона 3">
                        <h3>Брендированная фотозона</h3>
                        <p>Описание брендированной фотозоны.</p>
                        <p class="price">от 10000 руб.</p>
                        <a href="#contacts" class="button">Заказать</a>
                    </div>
                </div>
            </div>
        </section>

        <section class="about" id="about">
            <div class="container">
                <h2>О нас</h2>
                <p>[Название вашей компании] - это команда профессионалов, которые помогут вам создать идеальную фотозону для вашего мероприятия. Мы предлагаем широкий выбор готовых решений, а также изготавливаем фотозоны на заказ любой сложности.  Наши преимущества: индивидуальный подход, креативный дизайн, высокое качество материалов и доступные цены.</p>
                 <p><b>Отзывы клиентов:</b></p>
                 <p>"Спасибо большое за прекрасную фотозону! Все гости были в восторге!" - [Имя клиента]</p>
            </div>
        </section>

        <section class="contacts" id="contacts">
            <div class="container">
                <h2>Контакты</h2>
                <p>Оставьте заявку и мы свяжемся с вами в ближайшее время!</p>
                <form>
                    <input type="text" placeholder="Ваше имя" required>
                    <input type="email" placeholder="Ваш email" required>
                    <textarea placeholder="Ваше сообщение" rows="5" required></textarea>
                    <button type="submit" class="button">Отправить</button>
                </form>
                <p>Телефон: +7 (XXX) XXX-XX-XX</p>
                <p>Email: info@[вашдомен].ru</p>
                <p>Мы в социальных сетях: [Ссылки на ваши социальные сети]</p>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2024 [Название вашей компании]</p>
        </div>
    </footer>

</body>
</html>
