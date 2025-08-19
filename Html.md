# Nureke-co3
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Nureke&Co — IT Solutions</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg-light: #f0f4f8;
      --bg-dark: #1a1a1a;
      --text-light: #1a1a1a;
      --text-dark: #f0f4f8;
      --card-light: #ffffff;
      --card-dark: #2a2a2a;
    }

    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background-color: var(--bg-light);
      color: var(--text-light);
      transition: background 0.3s ease, color 0.3s ease;
    }

    .dark-mode {
      background-color: var(--bg-dark);
      color: var(--text-dark);
    }

    header {
      text-align: center;
      padding: 40px 20px 20px;
    }

    header h1 {
      font-size: 28px;
      margin: 0 0 10px;
    }

    header p {
      font-size: 16px;
      color: inherit;
    }

    section {
      max-width: 600px;
      margin: auto;
      background-color: var(--card-light);
      border-radius: 12px;
      padding: 30px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.05);
      transition: background 0.3s ease;
    }

    .dark-mode section {
      background-color: var(--card-dark);
    }

    h2 {
      font-size: 20px;
      margin-bottom: 10px;
    }

    ul {
      list-style: none;
      padding: 0;
    }

    li {
      margin: 10px 0;
      padding-left: 20px;
      position: relative;
    }

    li::before {
      content: "✅";
      position: absolute;
      left: 0;
    }

    .why {
      margin-top: 20px;
      font-style: italic;
    }

    .contact {
      margin-top: 30px;
      text-align: center;
    }

    .contact a {
      display: inline-block;
      margin: 10px;
      padding: 12px 24px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: 600;
      color: white;
      transition: background 0.3s ease;
    }

    .whatsapp {
      background: #25D366;
    }

    .whatsapp:hover {
      background: #1da851;
    }

    .telegram {
      background: #0088cc;
    }

    .telegram:hover {
      background: #0070b8;
    }

    .form-section {
      margin-top: 40px;
    }

    form {
      display: flex;
      flex-direction: column;
    }

    input, textarea {
      margin-bottom: 15px;
      padding: 10px;
      border-radius: 6px;
      border: 1px solid #ccc;
      font-size: 14px;
    }

    button {
      padding: 12px;
      background-color: #333;
      color: white;
      border: none;
      border-radius: 6px;
      font-weight: 600;
      cursor: pointer;
    }

    button:hover {
      background-color: #555;
    }

    .toggle-theme {
      margin-top: 20px;
      text-align: center;
    }

    .toggle-theme button {
      background-color: #0088cc;
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 8px;
      cursor: pointer;
      font-weight: 600;
    }

    .toggle-theme button:hover {
      background-color: #006fa1;
    }
  </style>
</head>
<body>

  <header>
    <h1>Привет! Я Нурхан 👋</h1>
    <p>Ваш надёжный помощник в мире IT</p>
  </header>

  <section>
    <h2>📋 Услуги:</h2>
    <ul>
      <li>Создание адаптивных сайтов</li>
      <li>Настройка Windows, Android, Wi-Fi</li>
      <li>Установка и обновление программ</li>
      <li>Консультации по технике и безопасности</li>
    </ul>

    <p class="why">Работаю с душой, быстро и по-человечески. Каждый клиент — как друг.</p>

    <div class="contact">
      <h2>📞 Связь:</h2>
      <a href="https://wa.me/77750576263" class="whatsapp">WhatsApp</a>
      <a href="https://t.me/nurekelachowski" class="telegram">Telegram</a>
    </div>

    <div class="form-section">
      <h2>📨 Обратная связь</h2>
      <form>
        <input type="text" placeholder="Ваше имя" required>
        <input type="email" placeholder="Email" required>
        <textarea rows="4" placeholder="Ваше сообщение..." required></textarea>
        <button type="submit">Отправить</button>
      </form>
    </div>

    <div class="toggle-theme">
      <button onclick="document.body.classList.toggle('dark-mode')">🌙 Переключить тему</button>
    </div>
  </section>

</body>
</html>
