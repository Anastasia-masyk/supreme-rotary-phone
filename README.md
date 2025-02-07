<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Косметолог</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Услуги косметолога</h1>
            <p>Преобразите свою кожу с профессиональными процедурами</p>
        </div>
    </header>

    <section id="services">
        <div class="container">
            <h2>Наши услуги</h2>
            <div class="service">
                <h3>Чистка лица</h3>
                <p>Глубокая чистка для идеальной кожи.</p>
            </div>
            <div class="service">
                <h3>Анти-возрастные процедуры</h3>
                <p>Массаж и уход для омоложения кожи.</p>
            </div>
            <div class="service">
                <h3>Массаж для лица</h3>
                <p>Расслабляющий и восстанавливающий массаж.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Связаться с нами</h2>
            <p>Для записи на процедуры напишите нам:</p>
            <form action="mailto:example@email.com" method="post" enctype="text/plain">
                <input type="text" name="name" placeholder="Ваше имя" required>
                <input type="email" name="email" placeholder="Ваш Email" required>
                <textarea name="message" placeholder="Ваше сообщение" required></textarea>
                <button type="submit">Отправить сообщение</button>
            </form>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Косметолог | Все права защищены</p>
    </footer>
</body>
</html>
