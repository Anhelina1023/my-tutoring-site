<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Репетитор математики</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; background-color: #eef2f3; margin: 0; }
        .container { max-width: 600px; margin: 50px auto; background: white; padding: 30px; border-radius: 15px; box-shadow: 0px 4px 10px rgba(0,0,0,0.1); }
        h1 { color: #333; }
        p { color: #666; }
        .form-group { margin: 15px 0; text-align: left; }
        input, textarea { width: 100%; padding: 12px; margin-top: 5px; border: 1px solid #ccc; border-radius: 5px; font-size: 16px; }
        button { background: #007bff; color: white; padding: 12px 20px; border: none; border-radius: 5px; cursor: pointer; font-size: 16px; }
        button:hover { background: #0056b3; }
        .header { background: #007bff; color: white; padding: 20px; border-radius: 15px 15px 0 0; }
        .footer { margin-top: 20px; color: #777; font-size: 14px; }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Репетитор з математики</h1>
        </div>
        <p>Допомагаю учням будь-якого рівня підготуватися до іспитів та покращити знання.</p>
        <h2>Запис на заняття</h2>
        <form action="https://formspree.io/f/your-email" method="POST">
            <div class="form-group">
                <label>Ім'я:</label>
                <input type="text" name="name" required>
            </div>
            <div class="form-group">
                <label>Email:</label>
                <input type="email" name="email" required>
            </div>
            <div class="form-group">
                <label>Повідомлення:</label>
                <textarea name="message" rows="4" required></textarea>
            </div>
            <button type="submit">Надіслати заявку</button>
        </form>
        <div class="footer">&copy; 2025 Репетитор математики. Всі права захищені.</div>
    </div>
</body>
</html>
