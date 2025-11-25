<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Y-Tech - Innovative Supplies | حاسبة التكلفة الذكية</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header class="header">
        <div class="logo">
            <img src="logo.png" alt="شعار Y-Tech">
        </div>
        <nav>
            <a href="#">الرئيسية</a>
            <a href="#">المنتجات</a>
            <a href="#">من نحن</a>
            <a href="#" class="cta-button">تواصل معنا</a>
        </nav>
    </header>

    <section class="hero-section">
        <div class="hero-content">
            <h1>شريكك المتكامل للتوريدات العامة.</h1>
            <p>حلول مبتكرة لتوريدات المعادن، الأخشاب، الكهرباء، والمزيد. احسب تكلفة مشروعك الآن!</p>
        </div>

        <div class="calculator-container">
            <h2>✨ حاسبة التكلفة الذكية</h2>

            <div class="input-group">
                <label for="productCategory">اختر صنف التوريد:</label>
                <select id="productCategory">
                    <option value="" disabled selected>-- اختر الصنف --</option>
                    <option value="metals">المعادن</option>
                    <option value="wood">الأخشاب</option>
                    <option value="electricity">أدوات الكهرباء</option>
                </select>
            </div>

            <div class="input-group">
                <label for="quantity">الكمية المطلوبة (وحدة):</label>
                <input type="number" id="quantity" min="1" value="1">
            </div>

            <button id="calculateBtn" class="neon-button">احسب التكلفة الفورية</button>

            <div class="result-box" id="resultBox">
                <p>إجمالي التكلفة التقريبية:</p>
                <span id="finalCost">0.00</span>
                <span class="currency">ر.س</span>
            </div>

            <p class="disclaimer">الأسعار تقريبية. اضغط على زر <a href="#">طلب عرض سعر رسمي</a> للمواصفات النهائية.</p>
        </div>
    </section>

    <script src="script.js"></script>
</body>
</html>
