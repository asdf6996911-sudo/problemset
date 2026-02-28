<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Pacific Orca College</title>

<style>
body{
    margin: 0;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    background-color: lightblue;
}

header{
    text-align: center;
    background-color: navy;
    color: white;
    padding: 30px;
    font-size: 32px;
}

.container{
    width: 85%;
    margin: 40px auto;
}

.section{
    display: flex;
    align-items: center;
    gap: 40px;
    background-color: white;
    padding: 40px;
    margin-bottom: 40px;
    border-radius: 10px;
}

.reverse{
    flex-direction: row-reverse;
}

.section img{
    width: 45%;
    max-width: 600px;
    height: auto;
    border-radius: 8px;
}

.text{
    width: 55%;
    color: navy;
}

.text h1,
.text h2,
.text h3{
    margin-top: 0;
}

ul{
    padding-left: 20px;
}

@media (max-width: 768px){
    .section{
        flex-direction: column;
        text-align: center;
    }

    .section img,
    .text{
        width: 100%;
    }
}
</style>
</head>

<body>

<header>
Introducing the Orcas
</header>

<div class="container">

<div class="section">
    <div class="text">
        <h2>
        Welcome to Pacific Orca College, where academic excellence meets coastal inspiration. Founded to blend rigorous scholarship with innovation and community engagement, Pacific Orca College stands as a beacon of opportunity on the West Coast. Nestled near the Pacific shoreline, our campus fosters a vibrant learning environment where future leaders explore new ideas, embrace global challenges, and make meaningful contributions to society.
        </h2>

        <h2>
        At Pacific Orca College, students benefit from a personalized educational experience with small class sizes, expert faculty mentorship, and hands-on learning opportunities — including cutting-edge research, internships with industry partners, and immersive fieldwork along the coast. Our Orca mascot symbolizes strength, intelligence, teamwork, and adaptability — qualities we encourage in every student.
        </h2>

        <h2>
        Whether pursuing undergraduate degrees, advanced research, or community-centered service, Orca students grow academically, socially, and professionally in a supportive and inclusive culture.
        </h2>
    </div>
</div>

<div class="section reverse">
    <img src="achieve.jpg" alt="Books">
    <div class="text">
        <h1>Our Achievements</h1>
        <h2>
        Pacific Orca College has earned recognition for academic excellence, innovation, and community leadership:
        </h2>

        <h3>
        Academic & Research Honors
        </h3>
        <ul>
            <li>Top 50 National College for Undergraduate Research — Recognized for student involvement in original research projects across sciences and humanities.</li>
            <li>Excellence in Marine Science Award — Faculty and students honored for breakthroughs in ocean conservation and climate resilience studies.</li>
            <li>Innovators in Technology Grant — Multi-year funding secured for development of sustainable coastal technology initiatives.</li>
        </ul>

        <h3>
        Impact & Community Engagement
        </h3>
        <ul>
            <li>Community Catalyst Award — Acknowledged for service programs that support local communities through education, health outreach, and environmental stewardship.</li>
            <li>Orca Service Corps — A student-led initiative providing tutoring, coastal cleanups, and public awareness campaigns that reached over 10,000 individuals regionally.</li>
        </ul>

        <h3>
        Athletics & Spirit
        </h3>
        <ul>
            <li>Conference Champions — Mens Soccer (2024) — Orcas soccer team clinched the championship with a record-breaking season.</li>
            <li>Spirit of the Coast Award — Recognized for outstanding student engagement and campus culture centered on pride and school spirit.</li>
        </ul>
    </div>
</div>

</div>

</body>
</html>
