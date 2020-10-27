<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio Website</title>
    <link rel="stylesheet" href="main.css">
    <script src="https://kit.fontawesome.com/a076d05399.js"></script>
    <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.0.11/typed.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/waypoints/4.0.1/jquery.waypoints.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/owl.carousel.min.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.carousel.min.css"/>

</head>
<body>
    <div class="scroll-up-btn">
        <i class="fas fa-angle-up"></i>
    </div>
    <nav class="navbar">
        <div class="max-height">
            <div class="logo"><a href="#">Xwyz<span>Worm.</span></a></div>
            <ul class="menu">
                <li class = "h1"><a href="#home" class="menu-btn">Home</a></li>
                <li class = "ab"><a href="#about" class="menu-btn">About</a></li>
                <li class = "sv"><a href="#services" class="menu-btn">Services</a></li>
                <li class = "sks"><a href="#skills" class="menu-btn">Skills</a></li>
                <li class = "prj"><a href="#project" class="menu-btn">Projects</a></li>
                <li class = "cnt"><a href="#contact" class="menu-btn">Contact</a></li>
            </ul>
        </div>
    </nav>

<!-- Home Section -->
<section class = "home" id = "home">
    <div class = "max-width">
      <div class = "home-content">
          <div class = "text-1"> Hi ,my name is</div>
          <div class = "tony"> <img src = "images/Tony.png" class = "tonyimages"></div>
          <div class="signature"><img src = "images/signature.png"></div>
          <div class = "text-2">Pratama Azmi</div>
          <div class = "text-3">And I'm  <span class = "typing"></span></div>
          <a href = "#">Hire me</a>
      </div>
    </div>
</section>
<!-- About section -->
<section id ="about"  class = "about">
    <div class = 'max-width'>
      <h2 class = "title">About me</h2>
        <div class = "about-content">
            <div>
              <div class = "column left">
                  <img src = "images/Tony.png" alt ="" class="tonyabout">
              </div>
                  <div class = "column right">
                      <div class = "text"> I'm Pratama Azmi and I'm a <span class ="typing-2"></span></div>
                      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi ut voluptatum eveniet doloremque autem excepturi eaque, sit laboriosam voluptatem nisi delectus. Facere explicabo hic minus accusamus alias fuga nihil dolorum quae. Explicabo illo unde, odio consequatur ipsam possimus veritatis, placeat, ab molestiae velit inventore exercitationem consequuntur blanditiis omnis beatae. Dolor iste excepturi ratione soluta quas culpa voluptatum repudiandae harum non.</p>
                      <a href = "#"> Download CV</a>
                      </div>
                  </div>
            </div>
        </div>
    </div>
</section>
<!-- Services --->
<section class = "services" id = "services">
  <div class = "max-width">
    <h2 class = "title">My Services</h2>
      <div class = "serv-content">
          <div class = "card">
            <div class ="box">
              <i class = "fas fa-flask"></i>
              <div class = "text">Naon We Lah</div>
              <p>Lorem ipsum dolor sit amet consectetur adipsi delecm quae. Explicabo illo unde, odio consequatur ipsam possimus veritatis, placeat, ab molestiae velit inventore epa voluptatum repudiandae harum non.</p>
            </div>
          </div>
          <div class="card">
            <div class ="box">
                <i class = "far fa-lightbulb"></i>
                <div class = "text">Analyzing Data</div>
                  <p>Lorem ipsum dolor sit amet consecteet on.</p>
            </div>
          </div>
          <div class = "card">
            <div class = "box">
              <i class = "fas fa-robot"></i>
              <div class = "text">Build Model</div>
                  <p>Lorem ipsum dolor sit amet consectetur adipisici.</p>
            </div>
          </div>
          <div class = "card">
              <div class = "box">
                <i class = "fas fa-rocket"></i>
                <div class ="text"> Odading Mang Ole</div>
                <p> apa Cok</p>
              </div>
      </div>
      <div class = "card">
        <div class = "box">
          <i class = "fas fa-mobile"></i>
          <div class ="text">Mobile Apps</div>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi ut voluptatum eveniet doloremque autem excepturi eaque, sit</p>
        </div>
      </div>
  </div>
</section>

<!-- Skills Biyy -->
<section class = "skills" id = "skills">
    <div class = "max-width">
      <h2 title = "title">My Skills</h2>
      <div class = "skills-content">
          <div class = "column left">
              <div class = "text">My Skills and Experience</div>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos, ratione error est recusandae consequatur, iusto illum deleniti quidem impedit, quos quaerat quis minima sequi. Cupiditate recusandae laudantium esse, harum animi aspernatur quisquam et delectus ipsum quam alias quaerat? Quasi hic quidem illum. Ad delectus natus aut hic explicabo minus quod.</p>
              <a href = "#">Read More</a>

          </div>
          <div class ="column right">
              <div class = "bars">
                <div class = "info">
                  <span>Data Science</span>
                  <span>80%</span>
              </div>
            </div>
            <div class = "line ds"></div>
              <div class ="bars">
                <div class = "info">
                  <span>Python</span>
                  <span>86%</span>
                </div>
              </div>
              <div class = "line python"></div>
              <div class ="bars">
                <div class= "info">
                  <span>Mathematics</span>
                  <span>65%</span>
                </div>
              </div>
              <div class = "line math"></div>
              <div class = "bars">
                <div class = "info">
                  <span>Deep Learning</span>
                  <span>68%</span>
                </div>
              </div>
              <div class="line dl"></div>
              <div class ="bars">
                <div class ="info">
                  <span>Ya itulah</span>
                  <span>90%</span>
                </div>
              </div>
              <div class = "line it"></div>
              <a href = "#">Show More</a>


      </div>
    </div>
</section>

<section class = "teams" id = "teams">
  <div class = "max-width">
    <h2 class ="title">Projects</h2>
    <div class ="carousel owl-carousel">
      <div class = "card">
        <div class = "box">
            <img src = "images/Tony.png">
            <div class = "text">Project1</div>
        </div>
      </div>
      <div class = "card">
        <div class ="box">
          <img src ="images/Tony.png">
          <div class = "text">Project2</div>
        </div>
      </div>
      <div class = "card">
        <div class ="box">
          <img src ="images/Tony.png">
          <div class = "text">Project3</div>
        </div>
      </div>
      <div class = "card">
        <div class ="box">
          <img src ="images/Tony.png">
          <div class = "text">Project4</div>
        </div>
      </div>
      <div class = "card">
        <div class ="box">
          <img src ="images/Tony.png">
          <div class = "text">Project5</div>
        </div>
      </div>
      <div class = "card">
        <div class ="box">
          <img src ="images/Tony.png">
          <div class = "text">Project6</div>
        </div>
      </div>
      <div class = "card">
        <div class ="box">
          <img src ="images/Tony.png">
          <div class = "text">Project7</div>
        </div>
      </div>
    </div>
  </div>
</section>

    <script src="main.js"></script>
</body>
</html>
