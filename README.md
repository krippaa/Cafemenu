<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cafe Landing Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #735536;
        }
        header {
            background-color: #524131;
            color: white;
            text-align: center;
            padding: 30px 0;
        }
        header h1 {
            margin: 0;
            font-size: 3em;
        }
        .menu-section {
            padding: 40px;
            background-color: #fff;
        }
        .menu-section h2 {
            text-align: center;
            margin-bottom: 30px;
            color: #d19875;
        }
        .menu-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .menu-item {
            background-color: #ded9d9;
            border: 1px solid #ddd;
            margin: 10px;
            padding: 20px;
            width: 200px;
            text-align: center;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .menu-item h3 {
            font-size: 1.5em;
            margin-bottom: 10px;
        }
        .menu-item p {
            font-size: 1.1em;
            color: #363131;
            margin: 10px 0;
        }
        footer {
            background-color: #0a0705;
            color: white;
            text-align: center;
            padding: 20px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>But first,coffee!</h1>
    <p>the only coffee you need in the city ;)</p>
</header>

<section class="menu-section">
    <h2>Our Menu</h2>
    <div class="menu-list">
        <div class="menu-item">
            <h3>Americano</h3>
            <p>Freshly brewed espresso added with hot water</p>
            <p><strong>₹200</strong></p>
        </div>
        <div class="menu-item">
            <h3>Caffe Macchiato</h3>
            <p>Shot of espresso diluted slightly by 1-2 teaspoons of steamed milk</p>
            <p><strong>₹250</strong></p>
        </div>
        <div class="menu-item">
            <h3>Latte</h3>
            <p>Espresso with steamed milk and a touch of foam.</p>
            <p><strong>₹300</strong></p>
        </div>
        <div class="menu-item">
            <h3>Chocolate Cake</h3>
            <p>Rich and decadent chocolate cake topped with frosting.</p>
            <p><strong>₹270</strong></p>
        </div>
        <div class="menu-item">
            <h3>Burger with fries</h3>
            <p>Burger (veg/non-veg) with fries on the side</p>
            <p><strong>₹350</strong></p>
        </div>
        <div class="menu-item">
            <h3>Blueberry Cheescake</h3>
            <p>Rich,creamy and tangy smoothness of cheesecake with the sweetness of blueberries</p>
            <p><strong>₹400</strong></p>
        </div>
    </div>
</section>

<footer>
    <p>&copy; 2025 But first,coffee! | All Rights Reserved</p>
</footer>

</body>
</html>
