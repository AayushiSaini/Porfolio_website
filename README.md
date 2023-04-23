<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Porfolio website</title>
    <link rel="stylesheet" href="index.css">
    <script src="https://kit.fontawesome.com/e75baa04d6.js" crossorigin="anonymous"></script>
</head>
<body>
    <div id="header">
        <div class="container">
            <nav>
                <img src="images/logo.png" class="logo">
                <ul id="sidemenu">
                    <li><a href="#header">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#porfolio">Portfolio</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <i class="fa-sharp fa-solid fa-circle-xmark" onclick="closemenu()"></i>
                </ul>
                <i class="fa-solid fa-bars" onclick="openmenu()"></i>
            </nav>
<div class="header-text">
    <p>Web and App Developer</p>
    <h1>Hi, I'm <span>Aayushi Saini</span</h1>
</div>

        </div>
    </div>
    <!---About section-->
<div id="about">
    <div class="container">
        <div class="row">
            <div class="about-col-1">
                <img src="images/img1.png" >
            </div>
            <div class="about-col-2">
                <h1 class="sub-title">About Me</h1>
                <br>
                <p>I am Student pursuing BTECH in computer science from kiet group of instituions.
                    I am a student who loves to explore new technology.I have some basic knowledge
                    of C,C++,JAVA and also have some experience in Web and Android developement.<br>
                    Want to work for an Organization that provides me the opportunity to
                    utilize my operational skills and knowledge in a challenging atmosphere to help
                    grow with the organization.
                
                </p>
                <div class="tab-titles">
                    <p class="tab-links active-link" onclick="opentab('skills')">Skills</p>
                    <p class="tab-links" onclick="opentab('Education')">Education</p>
                    <p class="tab-links" onclick="opentab('Internships')">Internships</p>
                </div>
                <div class="tab-contents active-tab " id="skills">
                    <ul>
                        <li><span>UI/UX</span><br>Designing App interface</li>
                        <li><span>Web developement</span><br>Website Developement</li>
                        <li><span>App developement</span><br>Building Android developement</li>
                    </ul>
                </div>


                <div class="tab-contents" id="Education">
                    <ul>
                        <li><span>BTECH</span><br>KIET GROUP OF INSTITUTIONS,GHAZIABAD</li>
                        <li><span>Current Percentage</span><br>82.5</li>
                        <li><span>Intermediate</span><br>BLUE BIRD'S INTERNATIONAL SCHOOL</li>
                        <li><span>Overall Percentage</span><br>86.17</li>
                        <li><span>High School</span><br>PINEWOOD SCHOOL</li>
                        <li><span>Overall Percentage</span><br>84.5</li>
                       
                    </ul>
                </div>

                <div class="tab-contents" id="Internships">
                    <ul>
                        <li><span>Oasis Infobyte Web developement and Designing</span><br>15-0-2023 - 15-02-2023</li>
                        <li><span>AICTE Eduskills</span><br><ul><li>AWS Cloud Fondation</li><li>AI/ML Virtual INternship</li></ul></li>
                        <li><span>Mood Indigo</span><br>Digital Marketing</li>
                        
                    </ul>
                </div>


            </div>
        </div>
    </div>
</div>
<!--Services-->
<div id="services">
    <div class="container">
        <h1 class="sub-title"> My Services</h1>
        <div class="services-list">
<div>
    <i class="fa-solid fa-code"></i>
    <h2>Web Design</h2>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur, deleniti? Iusto pariatur cupiditate quae amet. Rerum qui sequi doloribus, libero maxime beatae blanditiis quisquam, eius est autem porro dolor a?</p>
    <a href="#">Learn More</a>
</div>

<div>
    <i class="fa-sharp fa-solid fa-crop"></i>
    <h2>UI/UX Design</h2>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur, deleniti? Iusto pariatur cupiditate quae amet. Rerum qui sequi doloribus, libero maxime beatae blanditiis quisquam, eius est autem porro dolor a?</p>
    <a href="#">Learn More</a>
</div>

<div>
    <i class="fa-brands fa-apple"></i>
    <h2>Android Design</h2>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur, deleniti? Iusto pariatur cupiditate quae amet. Rerum qui sequi doloribus, libero maxime beatae blanditiis quisquam, eius est autem porro dolor a?</p>
    <a href="#">Learn More</a>
</div>
        </div>
    </div>
</div>

<!-------------------------Portfolio---------------------------------------->

<div id="porfolio">
    <div class="container">
        <div class="sub-title">My Work</div>
        <div class="work-list">
            <div class="work">
                <img src="images/img 21.png">
                <div class="layer">
                    <h3>Social media app</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi dolores eveniet est voluptates! Eveniet, nesciunt culpa magnam aspernatur iste qui magni voluptates rem officiis fugit consequuntur accusantium deserunt neque ex!</p>
                    <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>

                </div>
            </div>
            <div class="work">
                <img src="images/per.png">
                <div class="layer">
                    <h3>Social media app</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi dolores eveniet est voluptates! Eveniet, nesciunt culpa magnam aspernatur iste qui magni voluptates rem officiis fugit consequuntur accusantium deserunt neque ex!</p>
                    <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                    
                </div>
            </div>
            <div class="work">
                <img src="images/work-3.png">
                <div class="layer">
                    <h3>Social media app</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi dolores eveniet est voluptates! Eveniet, nesciunt culpa magnam aspernatur iste qui magni voluptates rem officiis fugit consequuntur accusantium deserunt neque ex!</p>
                    <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                    
                </div>
            </div>
        </div>

        <a href="#" class="btn">See More</a>
    </div>
</div>

<div id="contact">
    <div class="container">
        <div class="row">
            <div class="contact-left">
                <h1 class="sub-title">Contact Me</h1>
                <p><i class="fa-sharp fa-solid fa-paper-plane"></i>Contact@example.com</p>
                <p><i class="fa-solid fa-phone-volume"></i>7505349949</p>
                <div class="social-icon">
                    <a href="provide link here"><i class="fa-brands fa-linkedin"></i></a>
                    <a href=""><i class="fa-brands fa-square-instagram"></i></a>
                    <a href=""><i class="fa-brands fa-facebook"></i></a>
                </div>
               <a href="images/Resume Aayushi Saini.pdf" download class="btn btn2">Download Cv</a>



            </div>
            <div class="contact-Right">
                <form name="submit-to-google-sheet" >
                    <input type="text" name="Name" placeholder="Your name" required>
                    <input type="email" name="Email" placeholder="Your email" required>
                    <textarea name="Message" rows="6" placeholder="Your messgae"></textarea>
                    <button type="submit" class="btn btn2">Submit</button>
                </form>
                <span id="msg"></span>
            </div>
        </div>
        <div class="copyright">
            <p>Copyright @aayushi Made By Aayushi Saini <i class="fa-solid fa-heart"> </i></p>
        </div>
    </div>
</div>



<script>
    var tablinks = document.getElementsByClassName("tab-links");
    var tabcontents = document.getElementsByClassName("tab-contents");
    function opentab(tabname){
        for(tablink of tablinks){
            tablink.classList.remove("active-link");
        }
        for(tabcontent of tabcontents){
            tabcontent.classList.remove("active-tab");
        }
      event.currentTarget.classList.add("active-link");
document.getElementById(tabname).classList.add("active-tab");
    }
</script>
<script>
    var sidemenu=document.getElementById("sidemenu");
    function openmenu(){
        sidemenu.style.right="0";
    }
    function closemenu(){
        sidemenu.style.right="-200px";
    }
</script>
<script>
    const scriptURL = 'https://script.google.com/macros/s/AKfycbzsTVvbscLTwohQ65Ihcywezqhk77bbG_bc5l2cXpJa95t8Ws2WMxuHUo5F90AW_C-e/exec'
    const form = document.forms['submit-to-google-sheet']
    const msg=document.getElementById("msg")
  
    form.addEventListener('submit', e => {
      e.preventDefault()
      fetch(scriptURL, { method: 'POST', body: new FormData(form)})
        .then(response => {
            msg.innerHTML="Message sent succesfuuly"
            setTimeout(function(){
                msg.innerHTML=""
            },5000)
            form.reset()
        })
        .catch(error => console.error('Error!', error.message))
    })
  </script>

</body>
</html>
