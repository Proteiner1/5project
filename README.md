<!DOCTYPE html>
<html>
<head>
    <style>
        .report {
            max-width: 800px;
            margin: 40px auto;
            padding: 30px;
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
        }
        .header {
            text-align: center;
            border-bottom: 3px solid #2c3e50;
            padding-bottom: 20px;
            margin-bottom: 30px;
        }
        .section {
            margin-bottom: 35px;
        }
        .section-title {
            color: #2c3e50;
            font-size: 1.4em;
            margin-bottom: 15px;
            padding-left: 10px;
            border-left: 4px solid #3498db;
        }
        .highlight {
            color: #3498db;
            font-weight: 600;
        }
        ul.custom-list {
            list-style-type: none;
            padding-left: 20px;
        }
        ul.custom-list li {
            margin-bottom: 10px;
            padding-left: 25px;
            position: relative;
        }
        ul.custom-list li:before {
            content: "•";
            color: #3498db;
            position: absolute;
            left: 0;
        }
        .dashboard-link {
            display: inline-block;
            padding: 10px 20px;
            background: #3498db;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 15px;
        }
    </style>
</head>
<body>
    <div class="report">
        <div class="header">
            <h1>Анализ оттока клиентов в телеком-компании</h1>
            <p>Исследование ключевых факторов лояльности клиентов</p>
        </div>

        <div class="section">
            <div class="section-title">Основные выводы</div>
            <ul class="custom-list">
                <li>Клиенты с ежемесячной подпиской уходят в <span class="highlight">3 раза чаще</span>, чем с двухгодичным контрактом</li>
                <li>Отсутствие техподдержки увеличивает риск оттока на <span class="highlight">67%</span></li>
                <li>Пользователи Fiber optic демонстрируют <span class="highlight">на 40% выше</span> вероятность ухода</li>
            </ul>
        </div>

        <div class="section">
            <div class="section-title">Рекомендации</div>
            <ul class="custom-list">
                <li>Внедрить бонусную систему для перехода на годовые контракты</li>
                <li>Добавить базовую техподдержку в стандартные пакеты</li>
                <li>Разработать специальные условия для пенсионеров</li>
            </ul>
        </div>

        <div class="section">
            <div class="section-title">Визуализация данных</div>
            <p>Интерактивный дашборд включает:</p>
            <ul class="custom-list">
                <li>Динамику оттока по регионам</li>
                <li>Сравнение эффективности тарифов</li>
                <li>Прогноз риска ухода клиентов</li>
            </ul>
            <a href="#" class="dashboard-link">Посмотреть полный отчёт</a>
        </div>
    </div>
</body>
</html>
