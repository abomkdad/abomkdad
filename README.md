<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Special Offer - Narcotic Intense</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #000;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2rem;
        }
        header p {
            margin: 10px 0 0;
            font-size: 1.2rem;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        .hero-image {
            text-align: center;
        }
        .hero-image img {
            max-width: 100%;
            border-radius: 8px;
        }
        .offer-details {
            margin: 20px 0;
        }
        .offer-details h2 {
            color: #e91e63;
            text-align: center;
        }
        .offer-details p {
            font-size: 1.1rem;
            line-height: 1.6;
        }
        .company-details {
            margin: 20px 0;
            padding: 15px;
            background: #f3f3f3;
            border-left: 5px solid #e91e63;
            border-radius: 5px;
        }
        .company-details h3 {
            color: #333;
        }
        .company-details p {
            margin: 10px 0;
            font-size: 1rem;
        }
        .countdown {
            background: #000;
            color: #fff;
            padding: 10px;
            text-align: center;
            border-radius: 8px;
            margin: 20px 0;
            font-size: 1.2rem;
        }
        .form-container {
            text-align: center;
        }
        .form-container form {
            max-width: 400px;
            margin: 0 auto;
        }
        .form-container input[type="text"],
        .form-container input[type="email"],
        .form-container input[type="tel"] {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .form-container button {
            background-color: #e91e63;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1.1rem;
        }
        .form-container button:hover {
            background-color: #c2185b;
        }
        .whatsapp-button {
            margin: 20px 0;
            text-align: center;
        }
        .whatsapp-button a {
            display: inline-block;
            background-color: #25D366;
            color: #fff;
            padding: 10px 20px;
            border-radius: 5px;
            text-decoration: none;
            font-size: 1.1rem;
            font-weight: bold;
        }
        .whatsapp-button a:hover {
            background-color: #1da851;
        }
        footer {
            text-align: center;
            margin: 20px 0;
            font-size: 0.9rem;
            color: #777;
        }
    </style>
    <script>
        function startCountdown() {
            const countdownElement = document.getElementById('countdown');
            let time = 24 * 60 * 60; // 24 hours in seconds

            function updateCountdown() {
                const hours = Math.floor(time / 3600);
                const minutes = Math.floor((time % 3600) / 60);
                const seconds = time % 60;

                countdownElement.textContent = `${hours}h ${minutes}m ${seconds}s`;
                time--;

                if (time < 0) {
                    clearInterval(timer);
                    countdownElement.textContent = "انتهى العرض!";
                }
            }

            const timer = setInterval(updateCountdown, 1000);
            updateCountdown();
        }

        window.onload = startCountdown;
    </script>
</head>
<body>
    <header>
        <h1>احصل على عطرك الفاخر الآن!</h1>
        <p>ناركوتك إنتنس - عرض خاص لفترة محدودة</p>
    </header>

    <div class="container">
        <div class="hero-image">
            <img src="https://images.ravpages.co.il/xsite_resources/user_content/cp_new_production/91/83/6b/f8/91836bf88cd439d3c9085be2a19572db/images/cebb6bece7fa4798774ed9b8b80e570e.png" alt="Narcotic Intense Perfume">
        </div>

        <div class="offer-details">
            <h2>🔥 لا تفوت الفرصة!</h2>
            <p>عطر Narcotic Intense برائحة لا تُنسى، يدوم لأكثر من 12 ساعة، ويمنحك إحساساً بالرقي والأناقة. متوفر الآن بسعر خاص لفترة محدودة فقط.</p>
            <p><strong>✔️ تركيز عالي للعطر<br>✔️ سعر تنافسي<br>✔️ موافقة وزارة الصحة</strong></p>
        </div>

        <div class="company-details">
            <h3>عن MAD Perfume</h3>
            <p>نحن شركة رائدة في صناعة العطور، نقدم عطورًا فاخرة بجودة عالية ومكونات أصلية. هدفنا هو توفير تجربة مميزة لعملائنا عبر منتجات تجمع بين الأناقة والطابع العصري. مع أكثر من 28 فرعًا في البلاد، نحن فخورون بخدمة عملائنا وتقديم الأفضل دائمًا.</p>
            <p>✔️ منتجات معتمدة من وزارة الصحة<br>✔️ شهادات ISO للجودة<br>✔️ أكثر من 10 سنوات من التميز</p>
        </div>

        <div class="countdown">
            ⏳ العرض ينتهي خلال: <span id="countdown">24h 0m 0s</span>
        </div>

        <div class="form-container">
            <h3>اطلب الآن واحجز عطرك الفاخر</h3>
            <form>
                <input type="text" placeholder="الاسم الكامل" required>
                <input type="tel" placeholder="رقم الهاتف" required>
                <input type="text" placeholder="المدينة / العنوان" required>
                <button type="submit">احجز الآن</button>
            </form>
        </div>

        <div class="whatsapp-button">
            <a href="https://wa.me/972524033442?text=أريد%20طلب%20عطر%20Narcotic%20Intense">تواصل عبر واتساب</a>
        </div>
    </div>

    <footer>
        <p>© 2024 MAD Perfume - كل الحقوق محفوظة</p>
    </footer>
</body>
</html>
