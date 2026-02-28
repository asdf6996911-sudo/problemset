<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body{
            margin: 0;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
        }

        .words{
            background-color: lightblue;
            color: navy;
            padding: 20px;
            box-sizing: border-box;
            text-align: center;
            padding-top: 10px;
        }

        .mascot-container{
            display: flex;
            align-items: center;
            width: 100%;
            min-heigt: 400px;
        }

        .mascot-container img{
            flex: 50%;
            max-width: 800px;
            height:auto;
            display: block ;
            margin-right: 20px;
        }

        .mascot-text{
            flex:1;
            background-color: lightblue;
            color: navy;
            padding: 80px;
            box-sizing: border-box;
        }

        @media (max-width:768px){
            .mascot-container{
                flex-direction: column;
                align-items: center;
            }

            .mascot-container img{
                width: 80;
                max-width: 300px;
                margin-right: 0;
                margin-bottom: 20px;
            }

            .mascot-text{
                width: 90%;
                padding: 15px;
            }
        }
    </style>
</head>
<body>
    <div style="border: 5px solid lightblue; paddding:10px">
        <h1>Pacific Crest University</h1>
    </div>

    <div class="mascot-container">
        
        <img src="oceans.jpg" alt="ocean">
        <div class = "mascot-text">
        <h1>
            <ul>
                <li>
                    <a href="aboutus.html">AboutUs</a>
                </li>
                <li>
                    <a href="admission.html">Admission</a>
                </li>
                <li>
                    <a href="studentlife.html">Student Life</a>
                </li>
                <li>
                    <a href="academics.html">Academics</a>
                </li>
                <li>
                    <a href="faculty.html">Faculty Directory</a>
                </li>
                <li>
                    <a href="contact.html">Contact</a>
                </li>
            </ul>
        </h1>
        </div>
    </div>
    <div class = "words">
        <h1>
            Welcome to Pacific Crest University
            <h3>
                "Where innovation meets opportunity on the beautiful West Coast"
            </h3>
        </h1>
        <div style = "background-color: white; border: 5px solid black; paddding:10px">
        <h2>
            About Us
        </h2>
        <h3>
            At Pacific Coast College, students enjoy small, personalized classes, accredited programs across arts and sciences, and a vibrant campus community. Explore our mission, programs, and campus life on our About page.
        </h3>
        <h3>
            Founded in 1898, Northbridge Heights University (NHU) is a private research institution dedicated to academic excellence, innovation, and community impact. Located on a scenic 250-acre campus, NHU serves over 18,000 undergraduate and graduate students from more than 60 countries worldwide.

            At Northbridge Heights, we prepare students not just for careers — but for leadership in a rapidly evolving world.
        </h3>
        </div>
        <div style = "background-color: white; border: 5px solid black; paddding:10px">
        <h2>
            Announcements / News Ticker
        </h2>
        <h3>
            Spring semester classes start March 15
        </h3>
        <h3>
            Student Art Showcase this weekend
        </h3>
        <img src="campus.jpg" style = "max-width: 30%; height: auto;" alt ="campus">
        </div>
        <div class= "mascot-container" style="background-color: white; border: 5px solid black; paddding:10px">
            <img src="thumbsup.jpg" alt="ocean">
            <div class = "mascot-text">
                <h2>
                    Wtih 2,800 students, nationally ranked programs, and affordable degrees that make you workforce ready, the math just makes sense at Pacific Crest University. You can't afford to wait. Learn more about us today.
                </h2>
                <h2>
                    <a href="aboutus.html"> About PCU</a>
                </h2>
            </div>
    </div>
</body>
