# Photography-Website
Simple photography website/portfolio
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta http-equiv="X-UA-Compatible" content="ie=edge">
        <title>I'm a Photographer </title>
        <link rel="stylesheet" href="style.css">
        <!---font awesome-->
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css" 
        integrity="sha512-Evv84Mr4kqVGRNSgIGL/F/aIDqQb7xQ2vcrdIwxfjThSH8CSR7PBEakCr51Ck+w+/U6swU2Im1vVX0SVk9ABhg==" 
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    </head>
    <body>
        <!----header-->
        <header id ="header" class="vh-100 flex">
            <div class="container">
                <div class = "header-content">
                    <h1><br><span class = "typewrite"
                        data-loop = "yes" data-speed = "100"
                        data-delay = "2000" data-words = '["Madelyn Lopez", "Photographer"]'></span>
                    </h1>
                        <h3>Portrait, Artistic, and Wedding Photography</h3>
                    
                    <ul class = "social-links">
                        <li><a href="#" class = "flex"><i class="fab fa-instagram"></i></a></li>
                        <li><a href="#" class = "flex"><i class="fab fa-pinterest"></i></a></li>
                        <li><a href="#" class = "flex"><i class="fab fa-snapchat"></i></a></li>
                        <li><a href="#" class = "flex"><i class="fab fa-facebook-f"></i></a></li>
                    </ul>       
                </div>
            </div>
        </header>
        <!----end of header---->

        <!----main content---->
        <main>
             <!----about section-->
             <section id = "about" class="about py-7">
                <div class="container">
                    <div class="about-content grid">
                        <div class="about-left">
                            <img src = "images/about-pic.jpg" alt="">
                        </div>
                        <div class = "about-right">
                           <div class = "title">
                            <h2>About Me</h2>
                           </div>
                           <p class = "lead">
                            Hello! My name is Madelyn Lopez. I am a class of 2024 graduate from the University of Houston with a Bachelor of Arts in Psychology. I am from Houston, Texas and I am 27 years old. 
                            I am a first generation college student. I am a very hardworking and dedicated student. I am always looking for ways to improve my skills and knowledge. 
                            I am very excited to be taking this class and I am looking forward to learning more about web development.
                           </p> 
                           <p class = "lead"> 
                            I am a very creative person and I love to take pictures. I have been taking pictures since I was in high school. I have taken pictures of my friends and family and I have also taken pictures of nature. 
                            I love to take pictures of the beach and the sunset. I love to capture the beauty of the world around me. I am very passionate about photography and I am always looking for ways to improve my skills. 
                            I am always looking for new ways to take pictures and I am always looking for new places to take pictures. I am very excited to be taking this class and I am looking forward to learning more about photography.
                           </p>
                           <a href = "work" class = "btn-down">
                            <i class = "fas fa-chevron-down"></i> 
                           </a>
                            
                        </div>
                    </div>
                </div>    
             </section>
             <!----end of about section---->

             <!----work section-->
             <section id="work" class = "vh-100 flex py-7">
                <div class = "container">
                    <div class = "work-content">
                        <div class = "title">
                            <h2>My Work</h2>
                        </div>
                        <ul class = "work-top grid">
                            <li class = "lead">
                                <i class = "fas fa-dot-circle"> Detailed pictures</i>
                            </li>
                            <li class = "lead">
                                <i class = "fas fa-dot-circle"> Files</i>
                            </li>
                            <li class = "lead">
                                <i class = "fas fa-dot-circle"> Self-taught </i>
                            </li>
                            <li class = "lead">
                                <i class = "fas fa-dot-circle"> Back-up camera </i>
                            </li>
                        </ul>

                        <div class = "work-bottom grid">
                            <div>
                                <span class = "icon"><img src=
                                    "images/portrait-icon.png" alt="">
                                </span>
                                <h3>Portrait</h3>
                            </div>
                            <div>
                                <span class = "icon"><img src=
                                    "images/family-icon.png" alt="">
                                </span>
                                <h3>Family</h3>
                            </div>
                        </div>
                        <a href="#portfolio" class = "btn-down btn-down-white">
                            <i class = "fas fa-chevron-down"></i>
                        </a>
                    </div>
                </div>
             </section>
             <!----end of work section---->

             <!----portfolio section-->
             <section id = "portfolio" class = "vh-100 py-7">
                <div class = "container">
                    <div class = "portfolio-content">
                        <div class = "title">
                            <h2>Portfolio</h2>
                            <a href = "contact" class="btn-down">
                                <i class="fas fa-chevron-down"></i>
                            </a>
                        </div class = "portfolio-grid grid">
                        <div><img src = "images/"></div>
                        <div>
                        </div>
                    </div>
                </div>
             </section>
             <!----end of portfolio section---->

             <!----contact section---->
             <section id = "contact" class = "py-7">
                <div class = "container">
                    <div class = "contact-content flex">
                        <div class = "contact-left">
                            <div class = "title">
                                <h2>Contact Me</h2>
                            </div>
                            <p class = "lead"><i class = "fas fa-phone-alt">                                
                            </i> +281 757 (8169)</p>
                            <p class = "lead"><i class = "fas fa-envelope">                                
                            </i> madelyn.rendon99@gmail.com</p>
                            <form action="">
                                <input type = "text" class = 
                                "form-control" placeholder = "Your name here ...">
                                <input type = "email" class = "form-control"
                                placeholder = "Your email here">
                                <input type = "submit" class = "btn-submit btn" value = "Submit">
                            </form>
                        </div>

                        <div class = "contact-right">
                            <img src="images/contact.jpg" alt="contact pic">
                        </div>
                    </div>
                </div>
             </section>
        </main>

        <!----typewriting js-->
        <script src ="typewriting-master/typewriting.js"></script>

        <!----reference (https://www.youtube.com/watch?v=fFHyOjLdhuQ) ----->
        <!----reference (https://www.youtube.com/watch?v=VeOhsHkMaKQ&list=PLY3j36HMSHNWaKUC73RJlwi6oU-WTpTPM) ----->)-->
    </body>
</html>
