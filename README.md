<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Student Life</title>

<style>

body {
    margin: 0;
    font-family: Verdana, sans-serif;
    background-color: #dbeeff; /* light blue background */
}

header {
    text-align: center;
    padding: 30px;
    background-color: #1b3a6b; /* navy */
    color: white;
    font-size: 36px;
}

.section {
    display: flex;
    align-items: center;
    gap: 40px;
    background-color: white;
    margin: 40px auto;
    padding: 40px;
    width: 85%;
    border-radius: 10px;
}

.section img {
    width: 45%;
    height: auto;
    border-radius: 8px;
}

.text {
    width: 55%;
    color: navy;
}

/* Alternate second section */
.reverse {
    flex-direction: row-reverse;
}

/* Mobile responsiveness */
@media (max-width: 768px) {
    .section {
        flex-direction: column;
        text-align: center;
    }

    .section img,
    .text {
        width: 100%;
    }
}

</style>
</head>

<body>

<header>
    Student Life
</header>

<div class="section">
    <img src="https://images.unsplash.com/photo-1523050854058-8df90110c9f1" alt="Students studying">
    <div class="text">
        <h2>Campus Community</h2>
        <p>
            Student life is filled with opportunities to connect with others, join clubs, 
            and build lifelong friendships. From study groups to campus events, students 
            experience a vibrant and welcoming community that encourages growth and collaboration.
        </p>
    </div>
</div>

<div class="section reverse">
    <img src="https://images.unsplash.com/photo-1509062522246-3755977927d7" alt="Students at event">
    <div class="text">
        <h2>Activities & Events</h2>
        <p>
            Beyond academics, student life includes sports, organizations, volunteer work, 
            and social events. These activities help students develop leadership skills, 
            discover new interests, and create unforgettable memories throughout their journey.
        </p>
    </div>
</div>

</body>
</html>
