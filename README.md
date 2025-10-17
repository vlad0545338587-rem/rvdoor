<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>RVDOOR — Двери для вашего дома</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header class="header">
    <div class="container">
      <h1 class="logo">RVDOOR</h1>
      <nav>
        <a href="#about">О нас</a>
        <a href="#catalog">Каталог</a>
        <a href="#contact">Контакты</a>
      </nav>
    </div>
  </header>

  <section class="hero">
    <div class="container">
      <h2>Качественные двери от RVDOOR</h2>
      <p>Надёжность, стиль и долговечность для вашего дома.</p>
      <a href="#catalog" class="btn">Посмотреть каталог</a>
    </div>
  </section>

  <section id="about" class="about">
    <div class="container">
      <h2>О компании</h2>
      <p>RVDOOR — это команда профессионалов, специализирующихся на производстве и установке межкомнатных и входных дверей. Мы используем только качественные материалы и современные технологии.</p>
    </div>
  </section>

  <section id="catalog" class="catalog">
    <div class="container">
      <h2>Наш каталог</h2>
      <div class="products">
        <div class="product">
          <img src="https://via.placeholder.com/300x200?text=Межкомнатная+дверь" alt="Межкомнатная дверь">
          <h3>Межкомнатная дверь</h3>
          <p>Современный дизайн и высокое качество.</p>
        </div>
        <div class="product">
          <img src="https://via.placeholder.com/300x200?text=Входная+дверь" alt="Входная дверь">
          <h3>Входная дверь</h3>
          <p>Надёжная защита и эстетичный внешний вид.</p>
        </div>
        <div class="product">
          <img src="https://via.placeholder.com/300x200?text=Раздвижная+дверь" alt="Раздвижная дверь">
          <h3>Раздвижная дверь</h3>
          <p>Идеально подходит для современных интерьеров.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="contact" class="contact">
    <div class="container">
      <h2>Свяжитесь с нами</h2>
      <form id="contact-form">
        <input type="text" placeholder="Ваше имя" required />
        <input type="email" placeholder="Email" required />
        <textarea placeholder="Ваше сообщение" required></textarea>
        <button type="submit">Отправить</button>
      </form>
    </div>
  </section>

  <footer>
    <p>© 2025 RVDOOR. Все права защищены.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
