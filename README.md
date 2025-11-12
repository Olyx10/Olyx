<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <title>مطعمنا / Notre Restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1 id="logo">مطعمنا / Notre Restaurant</h1>
        <nav>
            <button onclick="setLanguage('ar')">العربية</button>
            <button onclick="setLanguage('fr')">Français</button>
            <a href="cart.html" id="cart-link">🛒 سلة التسوق</a>
        </nav>
    </header>

    <main>
        <h2 id="menu-title">قائمة الطعام / Menu</h2>
        <div class="products">
            <div class="product">
                <img src="https://via.placeholder.com/150" alt="بيتزا / Pizza">
                <h3 class="product-name" data-ar="بيتزا" data-fr="Pizza">بيتزا</h3>
                <p class="product-price" data-price="50">50 ر.س</p>
                <button onclick="addToCart(0)">أضف إلى السلة / Ajouter</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/150" alt="سلطة / Salad">
                <h3 class="product-name" data-ar="سلطة" data-fr="Salade">سلطة</h3>
                <p class="product-price" data-price="30">30 ر.س</p>
                <button onclick="addToCart(1)">أضف إلى السلة / Ajouter</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/150" alt="عصير / Juice">
                <h3 class="product-name" data-ar="عصير" data-fr="Jus">عصير</h3>
                <p class="product-price" data-price="20">20 ر.س</p>
                <button onclick="addToCart(2)">أضف إلى السلة / Ajouter</button>
            </div>
        </div>
    </main>

    <script src="script.js"></script>
</body>
</html>
