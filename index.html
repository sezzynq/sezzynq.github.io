<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Оптимизация Windows</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            background: linear-gradient(135deg, #f4f4f4, #d9d9d9);
            color: #333;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            text-align: center;
            overflow: hidden;
            transition: background 0.5s;
        }

        header {
            margin-bottom: 30px;
        }

        h1 {
            font-size: 48px;
            margin: 0;
            transition: transform 0.5s;
        }

        h1:hover {
            transform: scale(1.1);
        }

        p {
            font-size: 18px;
            margin: 20px 0;
            opacity: 0;
            animation: fadeIn 1s forwards;
            animation-delay: 0.5s;
        }

        .button {
            background-color: #333;
            color: #fff;
            border: none;
            padding: 15px 30px;
            border-radius: 5px;
            font-size: 18px;
            cursor: pointer;
            transition: background-color 0.3s, transform 0.3s;
            text-decoration: none;
            display: inline-block;
            margin-top: 20px;
            opacity: 0;
            animation: fadeIn 1s forwards;
            animation-delay: 1s;
        }

        .button:hover {
            background-color: #555;
            transform: translateY(-3px);
        }

        .content {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-wrap: wrap;
            gap: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .card {
            background-color: white;
            border-radius: 10px;
            padding: 20px;
            width: 300px;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.2);
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        footer {
            text-align: center;
            padding: 20px 0;
            position: absolute;
            bottom: 0;
            width: 100%;
            background-color: #fff;
            box-shadow: 0 -2px 10px rgba(0, 0, 0, 0.1);
        }

        footer p {
            margin: 0;
            color: #333;
        }

        /* Модальное окно */
        .modal {
            display: none;
            position: fixed;
            z-index: 1;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            overflow: auto;
            background-color: rgba(0, 0, 0, 0.8);
            justify-content: center;
            align-items: center;
        }

        .modal-content {
            background-color: #fefefe;
            margin: 15% auto;
            padding: 20px;
            border: 1px solid #888;
            width: 300px;
            text-align: center;
        }

        .modal-content input {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .modal-content button {
            padding: 10px 20px;
            background-color: #333;
            color: white;
            border: none;
            border-radius: 5px;
           
            cursor: pointer;
        }

        .modal-content button:hover {
            background-color: #555;
        }

        /* Кнопка смены темы */
        .theme-toggle {
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #333;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .theme-toggle:hover {
            background-color: #555;
        }

        .telegram-link {
            margin-top: 20px;
            display: flex;
            align-items: center;
            text-decoration: none;
            color: #333;
        }

        .telegram-link img {
            width: 24px;
            height: 24px;
            margin-right: 10px;
        }

    </style>
</head>
<body>

<header>
    <h1>Оптимизация Windows</h1>
    <p>Скачайте архив для улучшения производительности вашего ПК.</p>
    <button class="button" onclick="openModal()">Скачать архив</button>
    <button class="theme-toggle" onclick="toggleTheme()">Сменить тему</button>
</header>

<div class="content" id="content">
    <div class="card">
        <h2>Советы по оптимизации</h2>
        <p>Узнайте, как улучшить скорость работы вашей системы.</p>
    </div>
    <div class="card">
        <h2>Проблемы и решения</h2>
        <p>Решите распространенные проблемы с производительностью.</p>
    </div>
    <div class="card">
        <h2>Настройки системы</h2>
        <p>Оптимизируйте настройки для повышения эффективности.</p>
    </div>
</div>

<footer>
    <p>&copy; 2023 Оптимизация Windows. Все права защищены.</p>
    <a href="https://t.me/mzstacks" class="telegram-link" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/Telegram_logo.svg" alt="Telegram Logo">
        Подписаться на наш Telegram-канал
    </a>
</footer>

<!-- Модальное окно для ввода пароля -->
<div id="passwordModal" class="modal">
    <div class="modal-content">
        <h2>Введите пароль для скачивания</h2>
        <input type="password" id="password" placeholder="Пароль">
        <button onclick="checkPassword()">Подтвердить</button>
        <p id="message" style="color: red;"></p>
    </div>
</div>

<script>
    function openModal() {
        document.getElementById("passwordModal").style.display = "flex";
    }

    function closeModal() {
        document.getElementById("passwordModal").style.display = "none";
        document.getElementById("message").innerText = ""; // Сброс сообщения
    }

    function checkPassword() {
        const password = document.getElementById("password").value;
        const correctPassword = "2024OptSezzynq"; // Замените на ваш пароль
        if (password === correctPassword) {
            window.location.href = "https://drive.google.com/file/d/1q8ApJiKJAOGbczvEdlhTY2IDuJPnc8Q7/view?usp=sharing"; // Замените на путь к вашему архиву
            closeModal();
        } else {
            document.getElementById("message").innerText = "Неверный пароль. Попробуйте еще раз.";
        }
    }

    // Закрытие модального окна при клике вне его
    window.onclick = function(event) {
        const modal = document.getElementById("passwordModal");
        if (event.target === modal) {
            closeModal();
        }
    }

    // Смена темы
    let darkTheme = false;

    function toggleTheme() {
        darkTheme = !darkTheme;
        document.body.style.background = darkTheme ? 'linear-gradient(135deg, #333, #555)' : 'linear-gradient(135deg, #f4f4f4, #d9d9d9)';
        document.body.style.color = darkTheme ? '#f4f4f4' : '#333';
        const buttons = document.querySelectorAll('.button, .theme-toggle');
        buttons.forEach(button => {
            button.style.backgroundColor = darkTheme ? '#555' : '#333';
            button.style.color = darkTheme ? '#f4f4f4' : '#fff';
        });
    }
</script>

</body>
</html>
           
