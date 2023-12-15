<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

    <style>
        body {
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            background-color: rgb(235, 227, 213);
        }

        #welcome-message {
            text-align: left;
            margin-bottom: 0.5in;
            margin-top: 0.5in;
        }
        #welcome-message h1 {
            font-size: 2em;
            font-family: Georgia, 'Times New Roman', Times, serif;
        }
        #welcome-message h2 {
            font-size: 7em;
            font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
            color: rgb(65, 56, 46);
        }
        #welcome-message p {
            margin-top: 10%;
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
            text-align: right;
        }

        #about h2, #portfolio h5{
            font-family: Georgia, 'Times New Roman', Times, serif;
        }

        #about p, #portfolio p{
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }
        #portfolio h2{
            font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
            color: rgb(65, 56, 46);
        }
        .navbar {
            background-color: rgb(119, 107, 93);
        }

        .main_cards {
            background-color: rgb(243, 238, 234); 
            padding: 20px;
            border-radius: 15px;
            margin-top: 40px;
            margin-bottom: 20px;
            margin-left: 10%;
            margin-right: 10%;
        }
        .mini_card {
            background-color:  rgb(248, 247, 245);
            padding: 20px;
            border-radius: 15px;
            margin: auto;
        }

        .a1{
            text-align: right;
        }

        .btn {
            background-color: rgb(176, 166, 149);
            border: none;
            border-radius: 100px;
            width: 2in;
        }

        .center{
            padding: 10px;
        }
        .center_both {
            padding: 0.70in 0;
            text-align: left;
        }

        hr{
            margin-top: 0.25in;
            margin-bottom: 0.25in;
        }

        img {
            width: 100%;
            height: 3in;
            object-fit: contain;
        }

        footer {
            background-color: rgb(119, 107, 93);
            padding: 30px;
            color: white;
        }
    </style>
</head>

<body>
    <header>
        <nav class="navbar navbar-expand-md navbar-dark fixed-top">
            <a class="navbar-brand" href="#">Chloe's Corner</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="collapsibleNavbar">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link" href="#welcome">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#portfolio">Portfolio</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>

    <main>
        <div class="card-body main_cards" id="welcome">
            <section class="container">
                <div id="welcome-message">
                    <h1>Welcome to</h1>
                    <h2>Chloe's Corner!</h2>
                    <p>Chloe Irish T. Espino
                        <br>
                        <i>Web Developer</i></p>
                </div>
            </section>
        </div>

        <div class="card-body main_cards" id="about">
            <section class="container">
                <div class="row">
                    <div class="col-4 center">
                        <img src="https://scontent.fcrk2-2.fna.fbcdn.net/v/t39.30808-6/353439263_7054150701277971_8776468548002822779_n.jpg?_nc_cat=100&ccb=1-7&_nc_sid=efb6e6&_nc_eui2=AeG5zAWgsvfAqtoGKaqVuDM8OGCnEAjLjNU4YKcQCMuM1VrcrFQiHdjJJxUX0eDPAH-85Wd-gy9Ytuj8pTySXvPm&_nc_ohc=bOcNLKrCYm0AX-BKcoD&_nc_ht=scontent.fcrk2-2.fna&oh=00_AfBT6JOeW4GvcgkGk2msLI_s7FZmG3FzXuG--VjMbLtpiQ&oe=657F3D6E" alt="Pfp">
                    </div>
                    <div class="col-8 center_both">
                        <h2>About Me</h2>
                        <p>Pull up a virtual chair and get ready to dive into the world of my beginner web development adventures. It's a bit like a digital playground where I've tinkered, coded, and experimented to create something special. From wonky lines of code to triumphant "Aha!" moments, you're in for a ride. So, kick back, take a scroll, and remember – we're all learning as we go. Thanks for dropping by — I'm thrilled to have you here! q(≧▽≦q)</p>
                    </div>
                </div>
            </section>
        </div>
        
        <div class="card-body main_cards"  id="portfolio">
            <section class="container">
                <h2>My Portfolio</h2>
                <hr>
                <div class="row">
                    <div class="col-8">
                        <div class="card mini_card">
                            <h5 class="card-title a1">Project 1</h5>
                            <p class="card-text a1">Bootstrap + Jquery, Midterm Exam</p>
                        </div>
                    </div>
                    <div class="col-4">
                        <div class="card-body">
                            <a href="EspinoChloe_Project1.js" class="btn btn-primary">View Project</a>
                        </div>
                    </div>
                </div>
                <hr>
                <div class="row">
                    <div class="col-4">
                        <div class="card-body">
                            <a href="EspinoChloe_Project2.html" class="btn btn-primary">View Project</a>
                        </div>
                    </div>
                    <div class="col-8">
                        <div class="card mini_card">
                            <h5 class="card-title">Project 2</h5>
                            <p class="card-text">Bootstrap + Jquery, Progress Bars with buttons and event handlers</p>
                        </div>
                    </div>
                </div>
                <hr>
                <div class="row">
                    <div class="col-8">
                        <div class="card mini_card">
                            <h5 class="card-title a1">Project 3</h5>
                            <p class="card-text a1">Bootstrap + Jquery, Registration form</p>
                        </div>
                    </div>
                    <div class="col-4">
                        <div class="card-body">
                            <a href="EspinoChloe_Project3.html" class="btn btn-primary">View Project</a>
                        </div>
                    </div>
                </div>
                <hr>
                <div class="row">
                    <div class="col-4">
                        <div class="card-body">
                            <a href="EspinoChloe_Project4.html" class="btn btn-primary">View Project</a>
                        </div>
                    </div>
                    <div class="col-8">
                        <div class="card mini_card">
                            <h5 class="card-title">Project 4</h5>
                            <p class="card-text">Details, Table Rows</p>
                        </div>
                    </div>
                </div>
            </section>
        </div>
    </main>
     
    <footer>
        <div class="container text-center" id="contact">
            <div>
                <h3>Contacts</h3>
                <p>chloeijhf@gmail.com</p>
                <h4>- or -</h4>
                <p>Feel free to connect with me on social media:</p>
                <div class="social-links">
                    <a href="https://www.facebook.com/chloeirish.espino/" target="_blank"><img src="facebook_icon.png" alt="Facebook"></a>
                    <a href="https://www.instagram.com/soshipan/" target="_blank"><img src="instagram_icon.png" alt="Instagram"></a>
                </div>
            </div>
            <p>&copy; 2023 Chloe's Corner. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
