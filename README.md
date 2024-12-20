<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Donation Page</title>
    <style>
        header {
            background: #008000; /* Dark green color */
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        nav {
            display: flex;
            justify-content: center;
            background: #005700; /* Slightly darker green */
            padding: 10px;
        }

        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .hero {
            background: url('https://via.placeholder.com/1920x600') no-repeat center center/cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #fff;
            text-align: center;
        }

        .hero h2 {
            font-size: 3rem;
            margin: 0;
        }

        .content {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
            background: #ffff99; /* Light yellow */
            text-align: center;
        }

        .content h3 {
            margin-top: 0;
        }

        .donate-btn {
            display: inline-block;
            background: #008000; /* Dark green */
            color: #fff;
            padding: 15px 30px;
            text-align: center;
            text-decoration: none;
            font-size: 1.2rem;
            border-radius: 5px;
            margin-top: 20px;
        }

        .donate-btn:hover {
            background: #005700; /* Slightly darker green */
        }

        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Support Our Cause</h1>
    </header>
    
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
    
    <div class="hero">
        <h2>Make a Difference Today</h2>
    </div>
    
    <div class="content">
        <h3>Your Donations Matter</h3>
        <p>Your contribution will help us achieve our mission and improve the lives of those we support.</p>
        <a class="donate-btn" href="https://www.paypal.com/donate?hosted_button_id=YOUR_BUTTON_ID" target="_blank">Donate with PayPal</a>
    </div>
    
    <footer>
        <p>&copy; 2024 Your Organization Name. All Rights Reserved.</p>
    </footer>
</body>
</html>
