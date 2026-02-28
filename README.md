<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Pacific Crest University</title>

<style>

body{
    margin: 0;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    background-color: lightblue;
    color: navy;
}

.top-header{
    text-align: center;
    background-color: navy;
    color: white;
    padding: 25px;
    font-size: 30px;
}

.mascot-container{
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 40px;
    padding: 40px 10%;
}

.mascot-container img{
    width: 45%;
    max-width: 800px;
    height: auto;
    border-radius: 8px;
}

.mascot-text{
    width: 40%;
}

.mascot-text ul{
    list-style: none;
    padding: 0;
}

.mascot-text li{
    margin: 12px 0;
}

.mascot-text a{
    text-decoration: none;
    color: navy;
    font-weight: bold;
}

.mascot-text a:hover{
    text-decoration: underline;
}

.words{
    text-align: center;
    padding: 30px 10%;
}

.content-box{
    background-color: white;
    border-radius: 10px;
    padding: 25px;
    margin: 30px auto;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

.content-box img{
    margin-top: 15px;
    max-width: 30%;
    height: auto;
    border-radius: 6px;
}

.cta{
    display: flex;
    align-items: center;
    gap: 30px;
    background-color: white;
    padding: 30px;
    border-radius: 10px;
    margin-top: 40px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

.cta img{
    width: 35%;
    height: auto;
    border-radius: 8px;
}

.cta-text{
    width: 65%;
}

.cta-text a{
    color: navy;
    font-weight: bold;
    text-decoration: none;
}

.cta-text a:hover{
    text-decoration: underline;
}

@media (max-width:768px){

    .mascot-container{
        flex-direction: column;
        text-align: center;
    }

    .mascot-container img,
    .mascot-text{
        width: 100%;
    }

    .cta{
        flex-direction: column;
        text-align: center;
    }

    .cta img,
    .cta-text{
        width: 100%;
    }

    .content-box img{
        max-width: 80%;
    }
}

</style>
</head>

<body>

<div class="top-header">
    Pacific Crest University
</div>

<div class="mascot-container">
    <img src="oceans.jpg" alt="ocean">
    <div class="mascot-text">
        <ul>
            <li><a href="aboutus.html">About Us</a></li>
            <li><a href="admission.html">Admission</a></li>
            <li><a href="studentlife.html">Student Life</a></li>
            <li><a href="academics.html">Academics</a></li>
            <li><a href="faculty.html">Faculty Directory</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </div>
</div>

<div class="words">

    <h1>Welcome to Pacific Crest University</h1>
    <h3>"Where innovation meets opportunity on the beautiful West Coast"</h3>

    <div class="content-box">
        <h2>About Us</h2>
        <h3>
            At Pacific Coast College, students enjoy small, personalized classes, accredited programs across arts and sciences, and a vibrant campus community. Explore our mission, programs, and campus life on our About page.
        </h3>
        <h3>
            Founded in 1898, Northbridge Heights University (NHU) is a private research institution dedicated to academic excellence, innovation, and community impact. Located on a scenic 250-acre campus, NHU serves over 18,000 undergraduate and graduate students from more than 60 countries worldwide.
        </h3>
        <h3>
            At Northbridge Heights, we prepare students not just for careers — but for leadership in a rapidly evolving world.
        </h3>
    </div>

    <div class="content-box">
        <h2>Announcements / News Ticker</h2>
        <h3>Spring semester classes start March 15</h3>
        <h3>Student Art Showcase this weekend</h3>
        <img src="campus.jpg" alt="campus">
    </div>

    <div class="cta">
        <img src="thumbsup.jpg" alt="thumbs up">
        <div class="cta-text">
            <h2>
                With 2,800 students, nationally ranked programs, and affordable degrees that make you workforce ready, the math just makes sense at Pacific Crest University. You can't afford to wait. Learn more about us today.
            </h2>
            <h2><a href="aboutus.html">About PCU</a></h2>
        </div>
    </div>

</div>

</body>
</html>
