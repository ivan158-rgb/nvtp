<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>НВТП | Электронный Учебный Центр</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <div class="container">
            <h1>Начальная Военно-Техническая Подготовка (НВТП)</h1>
            <p>Интерактивный тренажер и ИИ-помощник</p>
        </div>
    </header>

    <main class="container">
        
        <section class="info-section">
            <h2>Основные разделы обучения</h2>
            <div class="cards">
                <div class="card">
                    <h3>Уставы ВС</h3>
                    <p>Изучение внутренней службы, дисциплинарного и строевого уставов.</p>
                </div>
                <div class="card">
                    <h3>Огневая подготовка</h3>
                    <p>Устройство ТТХ автомата АК-74, пистолета ПМ, правила стрельбы и безопасность.</p>
                </div>
                <div class="card">
                    <h3>Военная техника</h3>
                    <p>Основы бронетанковой техники, автомобильной подготовки и средств связи.</p>
                </div>
            </div>
        </section>

        <section class="chat-section">
            <h2>Консультация с преподавателем</h2>
            <p class="chat-sub">Задай вопрос товарищу капитану по уставам, оружию или технике.</p>
            
            <div class="chat-container">
                <div class="chat-box" id="chatBox">
                    <div class="message bot-message">
                        <strong>Капитан Иванов:</strong> Здравия желаю, курсант! Я твой виртуальный преподаватель по НВТП. Готов проверить твои знания или ответить на вопросы по уставам, ТТХ оружия или технике. Задавай вопрос четко!
                    </div>
                </div>
                <div class="chat-input-area">
                    <input type="text" id="userInput" placeholder="Например: расскажи про АК-74 или Строевой устав..." onkeydown="if(event.key === 'Enter') sendMessage()">
                    <button onclick="sendMessage()">Спросить</button>
                </div>
            </div>
        </section>

    </main>

    <footer>
        <div class="container">
            <p>&copy; 2026 Электронный образовательный ресурс НВТП.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
