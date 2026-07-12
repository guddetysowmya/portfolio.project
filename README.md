# portfolio.project
#html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>

    <!-- CSS File -->
    <link rel="stylesheet" href="syamala.css">


    <!-- Google Font -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700&display=swap" rel="stylesheet">

    <!-- Font Awesome -->
    <link rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.1/css/all.min.css">
</head>

<body>


<header>
    <nav>
        <h2 class="logo">MyPortfolio</h2>

        <ul id="menu">
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>



<section id="home">

    <h1>Hello, I'm <span>Sowmya Guddety</span></h1>

    <p><b>Software engineer</b></p>

    <div class="home-container">

        <!-- Profile Image -->
        <img  class="main-pic" src="/sonu.jpeg"alt="Sowmya">

        <!-- Social Links -->
        <div class="social-links">

            <div class="social-item">
            <img class="icon" src="linkdin.png">
                <a href="https://www.linkedin.com/in/g-sowmya-sowmya-a5729a352">
                    LinkedIn
                </a>
            </div>

            <div class="social-item">
                <img class="icon" src="data:image/png;base64,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">
                <a href="https://share.google/ISqzj5czYefmAsk86">
                    Github
                </a>
            </div>

            <div class="social-item">
                <img class="icon" src="data:image/jpeg;base64,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">
                <a href="https://www.codechef.com/users/pride_sock_82">
                    Codechef
                </a>
            </div>

            <br>

            <a class="resume-btn"
            href="https://1drv.ms/w/c/b00c9f6e8326c5b0/IQDQInfZ43kkQ5zuWL_vwjUyAZ-p4htYdTRjt6oBJ9whPNY?e=33mXWq">
                Download Resume
            </a>

        </div>

    </div>

</section>



<section id="about">

    <div class="about-container">

        <!-- Left Side Image -->
        <!--div class="about-image">
            <img src="images/sowmya.jpeg" alt="Sowmya">
        </div-->

        <!--- Right Side Content/-->
        <div class="about-content">

            <h2>About Me</h2>

            <p>
                I am G. Sowmya. I am studying B.Tech in the stream
                of Computer Science Engineering at Ashoka Women's
                Engineering College.
            </p>

            <p>
                I am from Bethamcherla and interested in becoming
                a Software Engineer.
            </p>

            <p>
                My skills are:
                Python, HTML, CSS and JavaScript (Basics).
            </p>

        </div>

    </div>

</section>



<section id="projects">

    <h2>My Projects</h2>

    <div class="project-card">

        <a href="https://github.com/guddetysowmya/ATM-project.py">
            <h3>ATM Project</h3>
        </a>

        <p>
            A simple ATM project developed using Python.
        </p>

    </div>

    <div class="project-card">

        <a href="10th.png">
            <h3>10th Certificate</h3>
        </a>

        <p>
            Secondary Board Certificate
        </p>

    </div>

    <div class="project-card">

        <a href="inter.png">
            <h3>Intermediate Certificate</h3>
        </a>

        <p>
            Intermediate Board Certificate
        </p>

    </div>

</section>



<section id="contact">

    <h2>Contact Me</h2>

    <form id="contactForm">

        <input type="text" id="name"
        placeholder="Your Name">

        <input type="email" id="email"
        placeholder="Your Email">

        <textarea id="message"
        placeholder="Your Message"></textarea>

        <button type="submit">Send</button>

    </form>

    <p id="formMessage"></p>

</section>

<script src="project.js"></script>
#css
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body{
    line-height: 1.6;
}



header{
    background: #333;
    color: white;
    padding: 15px 0;
}

nav{
    display: flex;
    justify-content: space-around;
    align-items: center;
}

.logo{
    font-size: 28px;
}

nav ul{
    display: flex;
    list-style: none;
}

nav ul li{
    margin: 0 15px;
}

nav ul li a{
    color: white;
    text-decoration: none;
    font-size: 18px;
}

nav ul li a:hover{
    color: #007bff;
}



section{
    padding: 60px 20px;
    text-align: center;
}



#home{
    background: #f4f4f4;
    min-height: 100vh;
}

#home h1{
    font-size: 40px;
    margin-bottom: 10px;
}

#home span{
    color: #007bff;
    font-family: "Roboto", sans-serif;
    font-style: italic;
}

#home p{
    font-size: 22px;
    margin-bottom: 30px;
}

.home-container{
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 50px;
    flex-wrap: wrap;
    
}

.main-pic{
    width: 250px;
    height: 300px;
    border-radius: 15px;
    object-fit: cover;
    box-shadow: 0px 4px 10px rgba(0,0,0,0.3);
    align-content:left;
    
}

.social-links{
    text-align: left;
}

.social-item{
    display: flex;
    align-items: center;
    margin-bottom: 20px;
}

.icon{
    width: 45px;
    height: 45px;
    margin-right: 15px;
}

.social-item a{
    text-decoration: none;
    color: black;
    font-size: 18px;
}

.resume-btn{
    display: inline-block;
    margin-top: 20px;
    padding: 10px 20px;
    background: #007bff;
    color: white;
    text-decoration: none;
    border-radius: 6px;
}



.about-container{
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 50px;
    flex-wrap: wrap;
}

.about-image img{
    width: 250px;
    height: 300px;
    border-radius: 10px;
    object-fit: cover;
    box-shadow: 0px 4px 10px rgba(0,0,0,0.3);
}

.about-content{
    max-width: 500px;
    text-align: left;
}

.about-content h2{
    color: #007bff;
    margin-bottom: 20px;
    font-size: 35px;
}

.about-content p{
    margin-bottom: 15px;
    font-size: 18px;
}



#projects{
    background: #f4f4f4;
}

.project-card{
    background: white;
    margin: 20px auto;
    padding: 20px;
    width: 60%;
    border-radius: 10px;
    box-shadow: 0px 3px 10px rgba(0,0,0,0.2);
}

.project-card h3{
    color: #007bff;
    margin-bottom: 10px;
}

.project-card a{
    text-decoration: none;
}


form{
    display: flex;
    flex-direction: column;
    width: 320px;
    margin: auto;
}

form input,
form textarea{
    margin: 10px 0;
    padding: 12px;
    border: 1px solid gray;
    border-radius: 5px;
}

button{
    background: #007bff;
    color: white;
    border: none;
    padding: 12px;
    cursor: pointer;
    border-radius: 5px;
    font-size: 16px;
}

button:hover{
    background: #0056b3;
}



@media (max-width:768px){

    nav{
        flex-direction: column;
    }

    nav ul{
        margin-top: 10px;
    }

    .home-container{
        flex-direction: column;
    }

    .about-container{
        flex-direction: column;
    }

    .about-content{
        text-align: center;
    }

    .project-card{
        width: 90%;
    }
}
#script
document.querySelectorAll('nav ul li a').forEach(anchor => {
    anchor.addEventListener('click', function(e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href'))
            .scrollIntoView({ behavior: 'smooth' });
    });
});

// Form Validation
document.getElementById("contactForm").addEventListener("submit", function(e) {
    e.preventDefault();

    let name = document.getElementById("name").value.trim();
    let email = document.getElementById("email").value.trim();
    let message = document.getElementById("message").value.trim();
    let formMessage = document.getElementById("formMessage");

    if (name === "" || email === "" || message === "") {
        formMessage.style.color = "red";
        formMessage.textContent = "All fields are required!";
    } else {
        formMessage.style.color = "green";
        formMessage.textContent = "Message sent successfully!";
        document.getElementById("contactForm").reset();
    }
});

</body>
</html>
