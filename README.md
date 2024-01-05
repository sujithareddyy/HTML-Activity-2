<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0px;
            color:aqua;
            background-color:black;
            padding:20px;
            font-family: Arial, sans-serif;
        }

        .row {
            display: flex;
            width: 100%;
        }

        .column {
            flex: 1;
            box-sizing: border-box;
            padding: 20px;
        }

        .logo {
            max-width: 30%;
            height: auto;
        }

        .header {
            text-align: right;
            color:whitesmoke;
            background-color: red;

        }

        .services {
            display: flex;
            flex-direction: column;
        }

        .links {
            display: flex;
            justify-content: space-around;
        }

        .links a {
            text-decoration: none;
            color: red;
            padding: 5px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
    </style>
</head>
<body>

    <!-- First Row -->
    <div class="row">
        <!-- First Column (Logo) -->
        <div class="column">
            <img src="image.jpg" alt="Logo" class="logo">
        </div>

        
        <div class="column heaYourder">
            <h1> Amazon</h1>
        </div>
    </div>

    <!-- Second Row with Links -->
    <div class="row links">
         
        <a href="https://www.amazon.in/">Home</a>
        <a href="https://www.amazon.in/s?k=login">Login</a>
        <a href="https://www.amazon.in/">Registration</a>
        <a href="https://www.amazon.in/">Catalogue</a>
        <a href="https://www.amazon.in/">Cart</a>
        <a href="https://www.amazon.in/gp/help/customer/display.html">Contact Us</a>

    </div>

    <!-- Third Row -->
    <div class="row">
        <!-- Left Column (Services) -->
        <div class="column services">
            <a href="https://www.amazon.com/">service1/a>
            <a href="https://www.myntra.com/">service2</a>
            <a href="https://www.ajio.com/">service2</a>
            <!-- Add more service links as needed -->
        </div>
        <div class="column">
            <h2>Contact Us</h2>
            <p>Email: info@example.com</p>
            <p>Phone: +1 (123) 456-7890</p>
            <p>Address: 123 Main Street, Cityville</p>
        </div>


        <!-- Right Column (Description) -->
        <div class="column">
            <p>This version includes information about Amazon and its key features, such as registration, login, contact details, shopping cart, and product catalog. </p>
        </div>
    </div>

</body>
