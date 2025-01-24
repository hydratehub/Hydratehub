<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hydrate Hub by Salman Co.</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff;
            color: #333;
        }
        header {
            background-color: #007BFF;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #0056b3;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        .container {
            padding: 20px;
        }
        .order-form {
            background-color: #ffffff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            max-width: 500px;
            margin: 0 auto;
        }
        .dashboard {
            background-color: #f9f9f9;
            padding: 20px;
            border-radius: 10px;
            margin-top: 20px;
        }
        footer {
            background-color: #007BFF;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        button {
            background-color: #007BFF;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
        input, select {
            width: calc(100% - 20px);
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Hydrate Hub by Salman Co.</h1>
        <p>Order fresh water bottles easily!</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#order">Order Water</a>
        <a href="#dashboard">Admin Dashboard</a>
        <a href="#contact">Contact Us</a>
    </nav>
    <div class="container" id="home">
        <h2>Welcome to Hydrate Hub by Salman Co.</h2>
        <p>We make it simple for employees to order water bottles online. Place your order now, and stay hydrated throughout the day!</p>
    </div>
    <div class="container" id="order">
        <h2>Order Water</h2>
        <form class="order-form">
            <label for="name">Your Name:</label><br>
            <input type="text" id="name" name="name" placeholder="Enter your name" required><br>
            <label for="department">Department:</label><br>
            <input type="text" id="department" name="department" placeholder="Enter your department" required><br>
            <label for="quantity">Number of Bottles:</label><br>
            <input type="number" id="quantity" name="quantity" placeholder="Enter quantity" min="1" required><br>
            <button type="submit">Place Order</button>
        </form>
    </div>
    <div class="container" id="dashboard">
        <h2>Admin Dashboard</h2>
        <div class="dashboard">
            <p>All orders will appear here for admin review and delivery scheduling.</p>
            <p><strong>Note:</strong> This is a placeholder. In a functional website, this section would display live order data.</p>
        </div>
    </div>
    <div class="container" id="contact">
        <h2>Contact Us</h2>
        <p>If you have any questions, feel free to reach out to us at:</p>
        <p>Email: contact@hydratehub.com</p>
        <p>Phone: +971-50-123-4567</p>
    </div>
    <footer>
        <p>&copy; 2025 Hydrate Hub by Salman Co. All rights reserved.</p>
    </footer>
</body>
</html>
