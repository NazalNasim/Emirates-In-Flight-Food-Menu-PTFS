# Emirates-In-Flight-Food-Menu-PTFS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Emirates In-Flight Food Menu</title>
    <style>
        /* Global Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background-color: #f8f8f8;
        }

        /* Header Styling */
        .header {
            background-color: #d91828;
            text-align: center;
            padding: 20px;
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .logo {
            height: 40px;
            margin-right: 10px;
        }
        .logo {
    height: 40px;
    margin-left: 20px; /* Adds spacing from the edge */
}

.header h1 {
    flex-grow: 1; /* Makes the title take available space */
    text-align: center;
    margin: 0;
}
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    height: 100vh; /* Full screen height */
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    font-family: Arial, sans-serif;
}

.header {
    background-color: #d91828;
    color: white;
    padding: 20px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 100%; /* Full width */
}

.logo {
    height: 40px;
    margin-left: 20px;
}

.header h1 {
    flex-grow: 1;
    text-align: center;
    margin: 0;
}

.main-content {
    flex-grow: 1; /* Expands to fill available space */
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 20px;
    background-color: #f8f8f8;
}

.menu-container {
    display: flex;
    justify-content: space-evenly;
    width: 100%;
}

.menu-box {
    background-color: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    text-align: center;
    width: 30%; /* Adjust width for even spacing */
}

.footer {
    background-color: black;
    color: white;
    text-align: center;
    padding: 10px;
    width: 100%;
}

        h1 {
            font-size: 2em;
        }

        /* Menu Section */
        .menu {
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 20px;
            flex-wrap: wrap;
        }

        .class-card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
            width: 300px;
        }

        .class-card h2 {
            color: #d91828;
            font-size: 1.5em;
        }

        .class-card img {
            width: 50px;
            height: auto;
            margin: 10px 0;
        }

        .class-card h3 {
            font-weight: bold;
            margin: 10px 0;
        }

        .class-card ul {
            list-style-type: none;
            font-size: 0.9em;
        }

        /* Footer */
        .footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }

        .footer a {
            color: white;
            text-decoration: none;
            margin: 0 10px;
        }
    </style>
</head>
<body>
    <header class="header">
        <img src="img/fly.png" alt="Emirates Logo" class="logo">
        <h1>Emirates In-Flight Food Menu</h1>
    </header>

    <section class="menu">
        <div class="class-card economy">
            <h2>Economy Class</h2>
            <img src="img/fly.png" alt="Economy Class Meals">
            <h3>Meals & Snacks</h3>
            <ul>
                <li>Chicken or Vegetarian Main Course</li>
                <li>Fresh Salad & Bread Rolls</li>
                <li>Fruit Platter</li>
                <li>Selection of Beverages (Tea, Coffee, Juices)</li>
                <li>Snack Packs (Cookies, Chips, etc.)</li>
            </ul>
        </div>

        <div class="class-card business">
            <h2>Business Class</h2>
            <img src="img/fly.png" alt="Business Class Meals">
            <h3>Gourmet Dining</h3>
            <ul>
                <li>Grilled Salmon with Asparagus</li>
                <li>Charcuterie and Cheese Platter</li>
                <li>Fine Wine Selection</li>
                <li>Seasonal Fruit and Dessert Selection</li>
                <li>Premium Beverages (Cocktails, Wines, Champagne)</li>
            </ul>
        </div>

        <div class="class-card first">
            <h2>First Class</h2>
            <img src="img/fly.png" alt="First Class Meals">
            <h3>Luxury Dining</h3>
            <ul>
                <li>Exquisite Caviar with Blinis</li>
                <li>Wagyu Beef Tenderloin with Truffle Sauce</li>
                <li>Gourmet Lobster and Crab Salad</li>
                <li>Specialty Cheese & Fruit Pairing</li>
                <li>Premium Champagne & Fine Wine</li>
            </ul>
        </div>
    </section>

    <footer class="footer">
        <p>Emirates Airlines | All Rights Reserved</p>
        <p><a href="#">Terms & Conditions</a> | <a href="#">Privacy Policy</a></p>
    </footer>
</body>
</html>
