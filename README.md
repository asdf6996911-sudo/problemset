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

/* Header */
header{
    text-align: center;
    background-color: navy;
    color: white;
    padding: 30px;
    font-size: 28px;
}

/* Main content wrapper */
.container{
    width: 85%;
    margin: 40px auto;
}

/* Section layout */
.section{
    display: flex;
    align-items: center;
    gap: 40px;
    background-color: white;
    padding: 30px;
    margin-bottom: 40px;
    border-radius: 10px;
}

/* Alternate layout */
.reverse{
    flex-direction: row-reverse;
}

/* Images */
.section img{
    width: 40%;
    max-width: 300px;
    height: auto;
    border-radius: 8px;
}

/* Text styling */
.text{
    width: 60%;
    color: navy;
}

.text h1, .text h2{
    margin-top: 0;
}

ul, ol{
    padding-left: 20px;
}

/* Mobile Responsive */
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
Welcome to Pacific Orca College! We're excited to have you consider joining our community. Below you’ll find everything you need to know about the application process, tuition, deadlines, and financial aid.
</header>

<div class="container">

<!-- Section 1 -->
<div class="section">
    <img src="deadline.jpg" alt="Application Deadlines">
    <div class="text">
        <h2>Application Deadlines</h2>
        <ul>
            <li>Early Action: November 1</li>
            <li>Regular Decision: January 15</li>
            <li>Transfer Application: March 1</li>
        </ul>
    </div>
</div>

<!-- Section 2 -->
<div class="section reverse">
    <img src="apply.jpg" alt="How to Apply">
    <div class="text">
        <h2>How to Apply</h2>
        <p>
            We accept applications via the Common Application and our Pacific Orca College Application Portal.
        </p>
        <p>To apply, simply:</p>
        <ol>
            <li>Complete the application form</li>
            <li>Submit your high school transcripts or college transcripts (for transfer students)</li>
            <li>Provide 1-2 letters of recommendation</li>
            <li>Write your personal statement or essay</li>
        </ol>
    </div>
</div>

<!-- Section 3 -->
<div class="section">
    <img src="study.jpg" alt="Admission Requirements">
    <div class="text">
        <h2>Admission Requirements</h2>
        <ul>
            <li>High School GPA: 3.0 or higher (on a 4.0 scale)</li>
            <li>SAT/ACT Scores: Optional for the 2026 cycle (superscoring accepted)</li>
            <li>Essay: Personal statement or response to a provided prompt</li>
            <li>Letters of Recommendation: 1-2 letters from teachers, mentors, or employers</li>
        </ul>
    </div>
</div>

<!-- Section 4 -->
<div class="section reverse">
    <img src="piggy.jpg" alt="Tuition and Fees">
    <div class="text">
        <h2>Tuition & Fees</h2>
        <ul>
            <li>In-State Tuition: $22,500 per year</li>
            <li>Out-of-State Tuition: $27,000 per year</li>
            <li>Room & Board: $14,000 per year</li>
            <li>Additional Fees: Technology, activity, and health fees apply.</li>
        </ul>
    </div>
</div>

</div>

</body>
</html>
