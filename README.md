<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Гаевик Назар Романович — Википедия</title>
    <style>
        /* Стили Википедии */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #202122;
            background-color: #f6f6f6;
        }
        
        .wrapper {
            display: flex;
            max-width: 1600px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Боковая панель */
        .sidebar {
            width: 250px;
            padding: 20px 10px;
            position: sticky;
            top: 0;
            height: 100vh;
            overflow-y: auto;
        }
        
        .logo {
            text-align: center;
            margin-bottom: 20px;
        }
        
        .logo img {
            max-width: 150px;
        }
        
        .sidebar-nav ul {
            list-style: none;
        }
        
        .sidebar-nav li {
            margin-bottom: 5px;
        }
        
        .sidebar-nav a {
            display: block;
            padding: 8px 12px;
            color: #3366cc;
            text-decoration: none;
            font-size: 14px;
            border-radius: 3px;
        }
        
        .sidebar-nav a:hover {
            background-color: #eaecf0;
        }
        
        /* Основной контент */
        .main-content {
            flex: 1;
            background-color: white;
            border: 1px solid #a7d7f9;
            border-right: none;
            padding: 30px;
            margin: 20px 0;
            box-shadow: 0 1px 3px rgba(0,0,0,0.1);
        }
        
        /* Шапка Википедии */
        .wiki-header {
            border-bottom: 1px solid #a2a9b1;
            padding-bottom: 15px;
            margin-bottom: 30px;
        }
        
        .wiki-header h1 {
            font-size: 28px;
            font-weight: normal;
            color: #000;
            margin-bottom: 10px;
        }
        
        .language-switcher {
            font-size: 14px;
            color: #54595d;
        }
        
        /* Контентная часть */
        .content-body {
            display: flex;
            gap: 30px;
        }
        
        .article-content {
            flex: 3;
        }
        
        .info-box {
            flex: 1;
            border: 1px solid #a2a9b1;
            background-color: #f8f9fa;
            padding: 20px;
            min-width: 300px;
        }
        
        .info-box h2 {
            font-size: 18px;
            text-align: center;
            background-color: #eaecf0;
            padding: 10px;
            margin: -20px -20px 20px -20px;
            border-bottom: 1px solid #a2a9b1;
        }
        
        .info-table {
            width: 100%;
            border-collapse: collapse;
        }
        
        .info-table tr {
            border-bottom: 1px solid #eaecf0;
        }
        
        .info-table td {
            padding: 8px 5px;
            vertical-align: top;
        }
        
        .info-label {
            font-weight: bold;
            width: 40%;
            color: #54595d;
        }
        
        .photo-container {
            text-align: center;
            margin: 20px 0;
        }
        
        .photo-container img {
            max-width: 100%;
            border: 1px solid #a2a9b1;
            border-radius: 3px;
        }
        
        .photo-caption {
            font-size: 12px;
            color: #54595d;
            margin-top: 5px;
        }
        
        /* Табы вкладок */
        .tabs {
            display: flex;
            border-bottom: 1px solid #a2a9b1;
            margin-bottom: 20px;
        }
        
        .tab {
            padding: 10px 20px;
            background-color: #f8f9fa;
            border: 1px solid #a2a9b1;
            border-bottom: none;
            margin-right: 5px;
            cursor: pointer;
            border-radius: 5px 5px 0 0;
        }
        
        .tab.active {
            background-color: white;
            border-bottom: 1px solid white;
            margin-bottom: -1px;
        }
        
        /* Стили контента */
        h2 {
            font-size: 22px;
            border-bottom: 1px solid #a2a9b1;
            padding-bottom: 5px;
            margin: 30px 0 15px 0;
            color: #000;
        }
        
        h3 {
            font-size: 18px;
            margin: 20px 0 10px 0;
        }
        
        p {
            margin-bottom: 15px;
        }
        
        .infobox {
            border: 1px solid #a2a9b1;
            background-color: #f8f9fa;
            padding: 15px;
            margin: 15px 0;
            border-radius: 3px;
            float: right;
            width: 250px;
            margin-left: 20px;
        }
        
        .references {
            font-size: 14px;
            color: #54595d;
            border-top: 1px solid #eaecf0;
            padding-top: 20px;
            margin-top: 30px;
        }
        
        /* Футер */
        .footer {
            background-color: #f8f9fa;
            border-top: 1px solid #a2a9b1;
            padding: 20px;
            margin-top: 40px;
            font-size: 12px;
            color: #54595d;
            text-align: center;
        }
        
        /* Адаптивность */
        @media (max-width: 1024px) {
            .content-body {
                flex-direction: column;
            }
            
            .info-box {
                width: 100%;
            }
        }
        
        @media (max-width: 768px) {
            .wrapper {
                flex-direction: column;
            }
            
            .sidebar {
                width: 100%;
                height: auto;
                position: static;
            }
        }
    </style>
</head>
<body>
    <div class="wrapper">
        <!-- Боковая панель -->
        <aside class="sidebar">
            <div class="logo">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/80/Wikipedia-logo-v2.svg/150px-Wikipedia-logo-v2.svg.png" alt="Wikipedia Logo">
            </div>
            <nav class="sidebar-nav">
                <ul>
                    <li><a href="#biography">Биография</a></li>
                    <li><a href="#education">Образование</a></li>
                    <li><a href="#personality">Личность</a></li>
                    <li><a href="#gallery">Галерея</a></li>
                    <li><a href="#references">Ссылки</a></li>
                </ul>
            </nav>
        </aside>

        <!-- Основной контент -->
        <main class="main-content">
            <!-- Шапка с названием статьи -->
            <header class="wiki-header">
                <h1>Гаевик Назар Романович</h1>
                <div class="language-switcher">
                    Язык: <strong>Русский</strong> | <a href="#">Українська</a> | <a href="#">English</a>
                </div>
            </header>

            <!-- Вкладки -->
            <div class="tabs">
                <div class="tab active">Статья</div>
                <div class="tab">Обсуждение</div>
                <div class="tab">Править</div>
                <div class="tab">Править код</div>
                <div class="tab">История</div>
            </div>

            <!-- Основное содержимое -->
            <div class="content-body">
                <!-- Текст статьи -->
                <article class="article-content">
                    <div class="infobox">
                        <h3>Краткая информация</h3>
                        <p><strong>Дата рождения:</strong> 2009 год</p>
                        <p><strong>Место рождения:</strong> Винница, Украина</p>
                        <p><strong>Место жительства:</strong> Снежное, ДНР</p>
                        <p><strong>Образование:</strong> Школа №1 г. Снежное</p>
                    </div>

                    <section id="biography">
                        <h2>Биография</h2>
                        <p><strong>Гаевик Назар Романович</strong> (род. 2009) — школьник, проживающий в городе Снежное Донецкой Народной Республики.</p>
                        <p>Родился в 2009 году в городе Винница, Украина. В настоящее время проживает и учится в городе Снежное ДНР.</p>
                    </section>

                    <section id="education">
                        <h2>Образование</h2>
                        <p>Назар учится в средней общеобразовательной школе №1 города Снежное. Является учеником средних классов, активно осваивает школьную программу.</p>
                        <p>Учебное заведение известно своими традициями и качеством образования в регионе.</p>
                    </section>

                    <section id="personality">
                        <h2>Личность и характер</h2>
                        <p>По описанию знакомых и друзей, Назар характеризуется как <strong>малословный, но твёрдый в общении</strong> человек.</p>
                        <p>Несмотря на немногословность, отличается прямотой и определённостью в суждениях. В общении ценит искренность и содержательность.</p>
                        <h3>Интересы и увлечения</h3>
                        <p>Интересы Назара включают современные технологии, компьютерные игры и активный отдых. Как и многие сверстники, следит за развитием IT-индустрии.</p>
                    </section>

                    <section id="gallery">
                        <h2>Галерея</h2>
                        <div class="photo-container">
                            <img src="https://via.placeholder.com/600x400/cccccc/666666?text=Фото+Назара+Гаевик" alt="Фото Назара Гаевик">
                            <div class="photo-caption">Назар Гаевик (архивное фото)</div>
                        </div>
                        <p><em>Примечание: Для добавления фотографии загрузите файл в папку images и замените src у тега img</em></p>
                    </section>

                    <section id="references">
                        <h2>Ссылки и примечания</h2>
                        <div class="references">
                            <ol>
                                <li>Личная информация предоставлена самим Назаром</li>
                                <li>Данные об образовании подтверждены открытыми источниками</li>
                                <li>Характеристика личности основана на самоописании</li>
                            </ol>
                        </div>
                    </section>
                </article>

                <!-- Инфобокс (справа) -->
                <aside class="info-box">
                    <h2>Гаевик Назар Романович</h2>
                    <div class="photo-container">
                        <img src="https://via.placeholder.com/250x300/e6e6e6/666666?text=Фото+будет+здесь" alt="Назар Гаевик">
                        <div class="photo-caption">Назар  Гаевик, 2024 год</div>
                    </div>
                    <table class="info-table">
                        <tr>
                            <td class="info-label">Дата рождения:</td>
                            <td>2009 год</td>
                        </tr>
                        <tr>
                            <td class="info-label">Место рождения:</td>
                            <td>Винница, Украина</td>
                        </tr>
                        <tr>
                            <td class="info-label">Место жительства:</td>
                            <td>Снежное, ДНР</td>
                        </tr>
                        <tr>
                            <td class="info-label">Гражданство:</td>
                            <td>Украина / ДНР</td>
                        </tr>
                        <tr>
                            <td class="info-label">Образование:</td>
                            <td>Школа №1, Снежное</td>
                        </tr>
                        <tr>
                            <td class="info-label">Известен как:</td>
                            <td>Школьник</td>
                        </tr>
                        <tr>
                            <td class="info-label">Характер:</td>
                            <td>Малословный, твёрдый в общении</td>
                        </tr>
                    </table>
                </aside>
            </div>
        </main>
    </div>

    <!-- Футер -->
    <footer class="footer">
        <p>Эта страница в последний раз была отредактирована сегодня.</p>
        <p>Текст доступен по лицензии Creative Commons Attribution-ShareAlike; в отдельных случаях могут действовать дополнительные условия.</p>
        <p>Wikipedia® — зарегистрированный товарный знак некоммерческой организации Wikimedia Foundation, Inc.</p>
    </footer>

    <script>
        // Простой скрипт для вкладок
        document.addEventListener('DOMContentLoaded', function() {
            const tabs = document.querySelectorAll('.tab');
            
            tabs.forEach(tab => {
                tab.addEventListener('click', function() {
                    // Удаляем активный класс у всех вкладок
                    tabs.forEach(t => t.classList.remove('active'));
                    // Добавляем активный класс текущей вкладке
                    this.classList.add('active');
                });
            });
            
            // Плавная прокрутка для навигации
            document.querySelectorAll('.sidebar-nav a').forEach(anchor => {
                anchor.addEventListener('click', function(e) {
                    e.preventDefault();
                    const targetId = this.getAttribute('href');
                    const targetElement = document.querySelector(targetId);
                    
                    window.scrollTo({
                        top: targetElement.offsetTop - 100,
                        behavior: 'smooth'
                    });
                });
            });
        });
    </script>
</body>
</html>
