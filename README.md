# my-websitte
<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Книжковий Рай</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Lora:wght@700&family=Roboto&display=swap" rel="stylesheet">
</head>
<body>
    <main class="section-main">
        <img class="section-main-logo" src="logo.png" alt="логотип">
        <h1 class="section-main-title">Книжковий Рай</h1>
        <h2 class="section-main-subtitle">Відкрий для себе наступну чудову книгу</h2>
        <button class="section-main-button">Дізнатися більше</button>
    </main>

    <section class="second-section">
        <img class="second-section-img" src="library.jpg" alt="Бібліотека">
        <div class="second-section-info">
            <h3 class="section-subtitle">ЛАСКАВО ПРОСИМО ДО КНИЖКОВОГО РАЮ</h3>
            <h3 class="section-title">Про нашу бібліотеку</h3>
            <p class="second-section-text">Ласкаво просимо до нашої бібліотеки, де ви знайдете широкий вибір книг для будь-якого віку та вподобань.</p>
            <p class="second-section-name"><span class="second-section-name2">ІВАН ІВАНЕНКО</span> - Засновник Книжкового Раю</p>
        </div>
    </section>

    <section class="third-section">
        <h3 class="section-subtitle">РЕКОМЕНДОВАНІ КНИГИ</h3>
        <h3 class="section-title">Наша колекція</h3>
        <div class="third-section-books">
            <div class="third-section-book">
                <img src="book1.png" alt="книга 1" class="book-img">
                <h4 class="book-title">Маленький принц</h4>
                <p class="book-author">Антуан де Сент-Екзюпері</p>
                <p class="book-price">150 грн</p>
            </div>
            <div class="third-section-book">
                <img src="book2.png" alt="книга 2" class="book-img">
                <h4 class="book-title">Гаррі Поттер</h4>
                <p class="book-author">Дж. К. Роулінг</p>
                <p class="book-price">300 грн</p>
            </div>
        </div>
    </section>

    <footer class="footer">
        <h3 class="section-title footer-title">Приєднуйтесь до нашої спільноти</h3>
        <p class="footer-text">
            <span class="footer-text-main">Підпишіться на нашу розсилку.</span><br> 
            Для запитів, будь ласка, зв'яжіться з нами за номером (+380) 123-456-789
        </p>
        <form action="" class="footer-form">
            <p class="form-title">Ім'я</p>
            <input type="text" class="form-input">
            <p class="form-title">Електронна пошта</p>
            <input type="email" class="form-input">
            <p class="form-title">Телефон</p>
            <input type="tel" class="form-input">
            <button class="footer-button">Підписатися</button>
        </form>
    </footer>
</body>
</html>
