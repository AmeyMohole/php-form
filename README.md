<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to Travel form</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <img class="bg" src="photo.jpg" alt="college">
    <div class="container">
        <h1>Welcome to GESCOE Trip form</h1>
        <p>Enter yout details and submit this form to confirm your participation</p>
        <p class="submitMsg">Thank you for Submiting</p>
        <script src="index.js"></script>
        <form action="index.php" method="post">
            <input type="text" name="name" id="name" placeholder="Enter your name">
            <input type="text" name="age" id="age" placeholder="Enter your age">
            <input type="text" name="gender" id="gender" placeholder="Gender">
            <input type="email" name="email" id="email" placeholder="Enter your email">
            <input type="number" name="number" id="number" placeholder="Enter your mobile number">
            <textarea name="desc" id="desc" cols="30" rows="10" placeholder="Other information"></textarea>
            <button class="btn">submit</button>
            <button class="btn">Reset</button>
        </form>

    </div>
</body>

</html>
