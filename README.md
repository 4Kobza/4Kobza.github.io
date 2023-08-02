<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KgKobe Personal Portfolio Website | KgKobe</title>
    
    <!-----box icons-->

    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>

    <!----custom css--->
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!----header design---->

    <header class="header">

        <a href="#" class="logo">Portfolio</a>

        <i class='bx bx-menu' id="menu-icon"></i>

        <nav class="navbar">
            <a href="#home" class="active">Home</a>
            <a href="#about">About</a>
            <a href="#services">Services</a>
            <a href="#portfolio">Portfolio</a>
            <a href="#contact">Contact</a>  
        </nav>
    </header>

<!-----Home Section Design---->
    
    <section class="home" id="home">
        <div class="home-content">
            <h3>Hola, It's Me </h3>
            <h1>Kaygee Kobe</h1>
            <h3>And I'm a <span class="multiple-text"></span></h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing 
                elit. Repellendus atque rem voluptatem animi, dolor 
                dolorem fuga voluptates.</p>
            <div class="social-media">
                <a href="https://web.facebook.com/kaygee.kobe/" target="_blank"><i class='bx bxl-facebook'></i></a>
                <a href="https://twitter.com/KgKobe" target="_blank"><i class='bx bxl-twitter'></i></a>
                <a href="https://www.instagram.com/kgkobe/" target="_blank"><i class='bx bxl-instagram-alt'></i></a>
                <a href="https://www.linkedin.com/in/kaygee-mohlala-1736b952/" target="_blank"><i class='bx bxl-linkedin' ></i></a>
                <a href="https://www.youtube.com/channel/UCV36Dz6u7bh7MOx7dgTIzLQ" target="_blank"><i class='bx bxl-youtube' ></i></a>
            </div>
            <a href="#" class="btn">Download CV</a>
        </div>

        <div class="home-img">
            <img src="images/KayGee Kobe.png">
        </div>
    </section>

    <!----About Section Design----->

    <section class="about" id="about">
        <div class="about-img">
            <img src="images/KgKobe @ Umthunzini.png" alt="">
        </div>

        <div class="about-content">
            <h2 class="heading">About <span>Me</span></h2>
            <h3>Frontend Developer!</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing
            elit. Eaque nam voluptates, quas adipisci quia 
            exercitationem magnam cupiditate sapiente totam fuga? 
            Eveniet distinctio consequuntur porro in dolor earum 
            ipsum expedita ex veritatis? Dolore nam at exercitationem?
            Sunt.</p>
            <a href="#" class="btn">Read More</a>
        </div>
    </section>

    <!-----Services Section Design------->
    <section class="services" id="services">
        <h2 class="heading">Our <span>Services</span></h2>

        <div class="services-container">
            <div class="services-box">
                <i class='bx bx-code-alt'></i>
                <h3>Web Development</h3>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing 
                elit. Natus officiis voluptatum sit nostrum eos possimus
                voluptates architecto laborum assumenda praesentium?</p>
                <a href="#" class="btn">Read More</a>
            </div>

            <div class="services-box">
                <i class='bx bxs-paint' ></i>
                <h3>Graphics Design</h3>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing 
                elit. Natus officiis voluptatum sit nostrum eos possimus
                voluptates architecto laborum assumenda praesentium?</p>
                <a href="#" class="btn">Read More</a>
            </div>

            <div class="services-box">
                <i class='bx bx-bar-chart-alt'></i>
                <h3>Digital Marketing</h3>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing 
                elit. Natus officiis voluptatum sit nostrum eos possimus
                voluptates architecto laborum assumenda praesentium?</p>
                <a href="#" class="btn">Read More</a>
            </div>

            <div class="services-box">
                <i class='bx bxs-music'></i>
                <h3>DeeJay</h3>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing 
                elit. Natus officiis voluptatum sit nostrum eos possimus
                voluptates architecto laborum assumenda praesentium?</p>
                <a href="#" class="btn">Read More</a>
            </div>
        </div>

    </section>
    
    <!------Portfolio Section Design-------->
    <section class="portfolio" id="portfolio">
        <h1 class="heading">Where<span>Abouts</span></h1>

        <div class="portfolio-container">
            <div class="portfolio-box">
                <img src="images/KgKobe & DJ @ Umthuzini.png" alt="">
                <div class="portfolio-layer">
                    <h4>With a DJ @ Emthunzini</h4>
                    <p>Lorem ipsum dolor sit amet consectetur 
                        adipisicing elit. Soluta, eligendi.</p>
                    <a href="#"><i class='bx bxs-playlist'></i></a>
                </div>
            </div>

            <div class="portfolio-box">
                <img src="images/KgKobe & Rbz.png" alt="">
                <div class="portfolio-layer">
                    <h4>With Rbz @ RoseTown</h4>
                    <p>Lorem ipsum dolor sit amet consectetur 
                        adipisicing elit. Soluta, eligendi.</p>
                    <a href="#"><i class='bx bxs-volume-full' ></i></a>
                </div>
            </div>

            <div class="portfolio-box">
                <img src="images/KgKobe @ Cappello CPT.png" alt="">
                <div class="portfolio-layer">
                    <h4>At Cappello Cpt</h4>
                    <p>Lorem ipsum dolor sit amet consectetur 
                        adipisicing elit. Soluta, eligendi.</p>
                    <a href="#"><i class='bx bxs-music'></i></a>
                </div>
            </div>

            <div class="portfolio-box">
                <img src="images/KgKobe @ DurbanVille.png" alt="">
                <div class="portfolio-layer">
                    <h4>@ DurbanVille</h4>
                    <p>Lorem ipsum dolor sit amet consectetur 
                        adipisicing elit. Soluta, eligendi.</p>
                    <a href="#"><i class='bx bxs-volume-full' ></i></a>
                </div>
            </div>

            <div class="portfolio-box">
                <img src="images/KgKobe @ R-Town.png" alt="">
                <div class="portfolio-layer">
                    <h4>@ Turfontein with Mango</h4>
                    <p>Lorem ipsum dolor sit amet consectetur 
                        adipisicing elit. Soluta, eligendi.</p>
                    <a href="#"><i class='bx bxs-playlist'></i></a>
                </div>
            </div>

            <div class="portfolio-box">
                <img src="images/KgKobe @ Umthunzini-2.png" alt="">
                <div class="portfolio-layer">
                    <h4>At Emthunzini</h4>
                    <p>Lorem ipsum dolor sit amet consectetur 
                        adipisicing elit. Soluta, eligendi.</p>
                    <a href="#"><i class='bx bxs-music'></i></a>
                </div>
            </div>
        </div>
    </section>

    <!-----Contact Section Design------->
    <section class="contact" id="contact">
        <h2 class="heading">Contact <span>Me!</span></h2>

        <form action="#">
            <div class="input-box">
                <input type="text" placeholder="Full Name">
                <input type="email" placeholder="Email Address">
            </div>
            <div class="input-box">
                <input type="number" placeholder="Mobile Number">
                <input type="text" placeholder="Email Subject">
            </div>
            <textarea name="" id="" cols="30" rows="10" placeholder="Your Message"></textarea>
            <input type="submit" value="Send Message" class="btn">
        </form>
    </section>

    <!-----Footer Design----->
    <footer class="footer">
        <div class="footer-text">
            <p>Copyright &copy; 2023 by KgKobe | All Rights Reserved</p>
        </div>

        <div class="footer-iconTop">
            <a href="#home"><i class='bx bx-up-arrow-alt'></i></a>
        </div>
    </footer>

    <!----Scroll reveal------>
    <script src="https://unpkg.com/scrollreveal"></script>

    <!------Typed JS----->
    <script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>

    <!----Custom JS------>

    <script src="script.js"></script>    
</body>
</html>
