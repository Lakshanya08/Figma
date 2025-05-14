# Ex09 Event Registration Web Application
## Date:14/05/2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
Home Page-1

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Rhythm @ Saveetha</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <div class="header">
    <div class="college-details">
      <strong>SAVEETHA ENGINEERING COLLEGE</strong><br>
      <em>Autonomous | Approved by AICTE | Affiliated to Anna University</em>
    </div>
    <div class="tnea-code">
      TNEA CODE<br>1216
    </div>
  </div>

  <div class="content">
    <h1>RHYTHM @ SAVEETHA</h1>
    <h2>DANCE COMPETITION</h2>
  </div>

  <div class="footer-img"></div>

</body>
</html>

body {
  margin: 0;
  font-family: 'Arial', sans-serif;
  background: linear-gradient(to bottom, #cbe6ff, #ffffff);
  text-align: center;
  color: black;
}

.header {
  background: white;
  padding: 10px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-bottom: 2px solid #ccc;
}

.header img.logo {
  height: 50px;
}

.college-details {
  text-align: left;
  font-size: 14px;
}

.college-details strong {
  color: #003366;
  font-size: 16px;
}

.tnea-code {
  background-color: #1c2b91;
  color: white;
  padding: 10px 15px;
  font-weight: bold;
  font-size: 18px;
  border-radius: 5px;
}

.content {
  padding: 40px 20px;
  background: linear-gradient(to top, #fff, #cce5ff);
}

.content h1 {
  font-size: 32px;
  font-family: 'Courier New', monospace;
  margin-bottom: 10px;
}

.content h2 {
  font-size: 20px

Page 2

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Dance Competition Registration</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <div class="form-container">
    <input type="text" placeholder="NAME">
    <input type="text" placeholder="REGISTER NUMBER">
    <input type="text" placeholder="DEPARTMENT">
    <input type="text" placeholder="CONTACT INFO">
    
    <button class="register-btn">REGISTER</button>

    <div class="prizes">
      <div class="prize"><span class="star">★</span> 1 - 1,00,000</div>
      <div class="prize"><span class="star">★</span> 2 - 50,000</div>
      <div class="prize"><span class="star">★</span> 3 - 25,000</div>
    </div>
  </div>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Dance Competition Registration</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <div class="form-container">
    <input type="text" placeholder="NAME">
    <input type="text" placeholder="REGISTER NUMBER">
    <input type="text" placeholder="DEPARTMENT">
    <input type="text" placeholder="CONTACT INFO">
    
    <button class="register-btn">REGISTER</button>

    <div class="prizes">
      <div class="prize"><span class="star">★</span> 1 - 1,00,000</div>
      <div class="prize"><span class="star">★</span> 2 - 50,000</div>
      <div class="prize"><span class="star">★</span> 3 - 25,000</div>
    </div>
  </div>

</body>
</html>

Page 3

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Chief Guests</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <div class="chief-container">
    <h1>CHIEF GUEST</h1>

    <div class="guest-row">
      <img src="sneha.jpg" alt="Sneha">
      <div class="guest-name">SNEHA</div>
    </div>

    <div class="guest-row reverse">
      <div class="guest-name">SUDHA<br>CHANDRAN</div>
      <img src="sudha.jpg" alt="Sudha Chandran">
    </div>

    <div class="guest-row">
      <img src="sandy.jpg" alt="Sandy">
      <div class="guest-name">SANDY</div>
    </div>

  </div>

</body>
</html>

body {
  margin: 0;
  padding: 0;
  font-family: 'Arial Black', sans-serif;
  background: linear-gradient(to bottom, #a28cc2, #4a3c70);
  color: black;
  display: flex;
  justify-content: center;
}

.chief-container {
  width: 300px;
  padding: 20px;
  text-align: center;
}

.chief-container h1 {
  font-size: 20px;
  margin-bottom: 30px;
}

.guest-row {
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 20px 0;
}

.guest-row.reverse {
  flex-direction: row-reverse;
}

.guest-row img {
  width: 80px;
  height: 80px;
  object-fit: cover;
  border-radius: 5px;
  margin: 0 10px;
}

.guest-name {
  font-size: 16px;
  font-weight: bold;
  text-align: center;
}

Page 4

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Event Details</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <div class="info-container">
    <div class="info-box">
      <strong>VENUE :</strong> MAJESTORIUM
    </div>

    <div class="info-box">
      <strong>DATE & TIME :</strong><br>
      21/05/2025 & 10.00 AM
    </div>

    <div class="info-box">
      sec.rhythm@saveetha.com
    </div>

    <div class="star">
      <span>ALL THE<br>BEST</span>
    </div>
  </div>

</body>
</html>

body {
  margin: 0;
  padding: 0;
  font-family: 'Arial Black', sans-serif;
  background: linear-gradient(to bottom, #5a3956, #e97b37);
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.info-container {
  width: 300px;
  text-align: center;
  color: black;
}

.info-box {
  background-color: white;
  padding: 12px;
  margin: 15px 0;
  font-size: 16px;
  font-family: 'Arial Black', sans-serif;
  border-radius: 4px;
}

.star {
  width: 0;
  height: 0;
  margin: 40px auto 0;
  position: relative;
}

.star::before {
  content: "";
  position: absolute;
  top: 0;
  left: -75px;
  width: 150px;
  height: 150px;
  background: yellow;
  clip-path: polygon(
    50% 0%,
    61% 35%,
    98% 35%,
    68% 57%,
    79% 91%,
    50% 70%,
    21% 91%,
    32% 57%,
    2% 35%,
    39% 35%
  );
}

.star span {
  position: relative;
  display: inline-block;
  top: 60px;
  font-size: 16px;
  font-weight: bold;
  font-family: 'Arial Black', sans-serif;
}
```

## OUTPUT:

![Screenshot 2025-05-14 213617-2](https://github.com/user-attachments/assets/3c5908a2-766b-4e61-9ff0-ca96b6f4534a)
![Screenshot 2025-05-14 213626](https://github.com/user-attachments/assets/ae78913e-6704-4b7d-b365-0660ed9bce6a)
![Screenshot 2025-05-14 213637](https://github.com/user-attachments/assets/8fd92913-5ff0-4954-92eb-1a4e46de2d65)
![Screenshot 2025-05-14 213648-1](https://github.com/user-attachments/assets/4004ec01-18f3-434c-86a0-ad4e8622b794)
![Screenshot 2025-05-14 213606](https://github.com/user-attachments/assets/5994dd96-c58f-44e6-8d06-0c5a07ed83d2)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
