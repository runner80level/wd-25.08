<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мария & Владислав | 25.08.2025</title>
    <style>
        :root {
            --bg-color: #000;
            --text-color: #fff;
            --accent-color: #e0aaff;
            --card-bg: rgba(17, 17, 17, 0.85);
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
        }
        
        body {
            color: var(--text-color);
            line-height: 1.6;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            background: 
                linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)),
                url('https://i.postimg.cc/njPYntM7/photo.jpg') no-repeat center center fixed;
            background-size: cover;
        }
        
        .container {
            max-width: 100%;
            width: 100%;
            padding: 20px;
            margin: 0 auto;
        }
        
        /* Шапка с фоновым фото */
        header {
            text-align: center;
            padding: 100px 0 60px;
            margin-bottom: 30px;
            position: relative;
            overflow: hidden;
            background: 
                linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.4)),
                url('https://i.postimg.cc/njPYntM7/photo.jpg') no-repeat center center;
            background-size: cover;
            border-radius: 10px;
            box-shadow: 0 4px 30px rgba(0, 0, 0, 0.3);
        }
        
        header::after {
            content: "";
            position: absolute;
            bottom: 0;
            left: 25%;
            width: 50%;
            height: 1px;
            background: linear-gradient(90deg, transparent, var(--accent-color), transparent);
        }
        
        h1 {
            font-size: clamp(1.8rem, 5vw, 2.5rem);
            color: var(--accent-color);
            margin-bottom: 15px;
            font-weight: 300;
            letter-spacing: 2px;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.5);
        }
        
        .names {
            font-size: clamp(2rem, 6vw, 3rem);
            font-weight: 300;
            margin-bottom: 10px;
            letter-spacing: 1px;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.5);
        }
        
        .date {
            font-size: clamp(1.2rem, 4vw, 1.5rem);
            color: #ddd;
            margin-bottom: 20px;
            text-shadow: 0 1px 3px rgba(0, 0, 0, 0.5);
        }
        
        /* Остальные стили остаются без изменений */
        .invitation-text {
            background-color: var(--card-bg);
            padding: 25px;
            border-radius: 8px;
            margin-bottom: 30px;
            text-align: center;
            font-size: clamp(1rem, 3vw, 1.1rem);
            line-height: 1.8;
            border: 1px solid #333;
            backdrop-filter: blur(5px);
        }
        
        /* ... (остальной CSS код из предыдущего примера остается без изменений) ... */
    </style>
    <!-- Остальные скрипты и метатеги -->
</head>
<body>
    <!-- Весь HTML-код из предыдущего примера остается без изменений -->
    <div class="container">
        <header>
            <h1>Мы женимся</h1>
            <div class="names">Мария & Владислав</div>
            <div class="date">25 августа 2025 года</div>
        </header>
        
        <!-- Остальное содержимое -->
    </div>
</body>
</html>
