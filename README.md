# Food-corner
Food delivery site
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MyAppetite.com</title>
    <link rel="stylesheet" href="CSS/style2.css">
</head>
<body>
    <nav id="navbar">
        <div id="logo">
            <img src="logo.png" alt="MyAppetite.com">
        </div>
        <ul>
            <li class="list"><a href="#">Home</a></li>
            <li class="list"><a href="#">About</a></li>
            <li class="list"><a href="#">Services</a></li>
            <li class="list"><a href="#">Contact us</a></li>
        </ul>
    </nav>
    <section id="home">
        <h1 class="h-primary">Welcome to MyAppetite.com</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Illum</p>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Beatae eos ducimus, minima fugit officia omnis!</p>
        <button class="btn">Order now</button>
    </section>
    <section class="services">
        <h1 class="h-primary center">Our Services</h1>
        <div id="service">
            <div class="box">
                <img src="1.jpg" alt="">
                <h2 class="h-secondary center">Food Ordering</h2>
                <p class="center">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Et at quam, quod accusantium quia harum officia maxime accusamus reiciendis </p>
            </div>
            <div class="box">
                <img src="3.jpg" alt="">
                <h2 class="h-secondary center">Food Catering</h2>
                <p class="center">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Et at quam, quod accusantium quia harum officia maxime accusamus reiciendis </p>
            </div>
            <div class="box">
                <img src="2.jpg" alt="">
                <h2 class="h-secondary center">Bulk Ordering</h2>
                <p class="center">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Et at quam, quod accusantium quia harum officia maxime accusamus reiciendis </p>
            </div>
        </div>
    </section>
    <section id="client-section">
        <h1 class="h-primary center">Our Clients</h1>
        <div id="clients">
            <div class="client-items">
                <img src="apple logo.jpg" alt="client1">
            </div>
            <div class="client-items">
                <img src="Skype-logo.png" alt="client1">
            </div>
            <div class="client-items">
                <img src="mslogo.png" alt="client1">
            </div>
            <div class="client-items">
                <img src="hplogo.png" alt="client1">
            </div>
        </div>
    </section>
    <section id="contact">
        <h1 class="h-primary center">Contact Us</h1>
        <div id="contact-box">
            <form action="">
                <div class="form-group">
                    <label for="name">Name:</label>
                    <input type="text" name="name" id="name" placeholder="Enter your Name">
                </div>
                <div class="form-group">
                    <label for="email">Email:</label>
                    <input type="text" name="email" id="email" placeholder="Enter your Email">
                </div>
                <div class="form-group">
                    <label for="contact">Contact no.:</label>
                    <input type="number" name="contact" id="contact1" placeholder="Enter your Contact No.">
                </div>
                <div class="form-group">
                    <label for="message">Message:</label>
                    <textarea name="message" id="message" cols="10" rows="10"></textarea>
                </div>
            </form>
        </div>
    </section>
    <footer>
        <div class="center">
            Copyright &copy; www.MyAppetite.com. All rights reserved!
        </div>
    </footer>
</body>
</html>
