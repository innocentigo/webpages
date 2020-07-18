# webpages<!DOCTYPE html>
<html lang="eng">
    <head>
        <meta charset="UFT -8">
        <meta name="viewport" content="width=device-width,initail-scale=1.0">
        <meta http-equiv="X-UA-compatible" content="ie=egde">
        <title>website design</title>
        <link rel="stylesheet" href="coding.css">
        <script>
            function openSlideMenu(){
               document.getElementById("inside-menu").style.width='250px';
               document.getElementById("content").style.marginLeft='250px';
            }
            function closeSlideMenu(){
               document.getElementById("inside-menu").style.width='0';
               document.getElementById("content").style.marginLeft='0';
            }
        </script>
    </head>
    <body>
        <!--header-->
        <header>
            <div class="content">
            <h1><span class="highlight">Acme</span> web design</h1>
            </div>
            <div class="content" id="content">
               <span id="side-menu">
                   <a href="#" onclick="openSlideMenu()">
                   <svg width="30" height="30">
                       <path d="M0,5 30,5" stroke="black" stroke-width="5"></path>
                       <path d="M0,15 30,15" stroke="black" stroke-width="5"></path>
                       <path d="M0,25 30,25" stroke="black" stroke-width="5"></path>
                    </svg>
                    </a>
               </span>
                <div id="inside-menu" class="inside-menu">
                    <a href="#" class="close-btn"onclick="closeSlideMenu()">&times;</a>
                    <a href="coding.html">Home</a>
                    <a href="coding-a.html">About</a>
                    <a class="current" href="coding-s.html">Services</a>
                </div>
           </div>
        </header>
        <!--showcase--->
        <div id="showcase">
            <div class="pic"></div>
            <div class="content">
                <h1>Affordable Professional Websites</h1>
                <p>Lorem jfhihief jhefhiohefh ughegoeu ugeageu  ipsum dolor sit amet consectetur adipisicing elit. Veritatis, culpa. Vel deserunt est reprehenderit quod!</p>
             </div>
        </div>
        <!--newsletter-->
        <div id="newsletter">
             <div class="content">
                 <h2>subscribe to our website</h2>
                 <form>
                     <input type="text" name="enter your mail" placeholder="enter your mail">
                     <input class="btn" type="submit" value="subscribe">
                </form>

            </div>
        </div>
        <!--section-A-->
        <div id="section-A">
            <div class="content">
            <div class="grid">
                <div class="card">
                    <img src="css.png">
                    <h2 class="p">html markup</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Officia, saepe. Voluptatibus eos sit obcaecati aliquam.</p>
                </div>
                <div class="card">
                    <img src="html.png">
                    <h2>html markup</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Officia, saepe. Voluptatibus eos sit obcaecati aliquam.</p>
                </div>
                <div class="card">
                    <img src="graphics.png">
                    <h2>html markup</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Officia, saepe. Voluptatibus eos sit obcaecati aliquam.</p>
                </div>
            </div>

            </div>

        </div>
        <footer>
            <p>Acme web design copy &copy 2020</p>
        </footer>
        


    </body>
</html>

