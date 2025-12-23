# Ex09 Event Registration Web Application
## Date:23/12/2025

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
EVENT DAY
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Event Days - SEC</title>
  <style>
    body {
      background: #000;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .mobile-frame {
      width: 320px;
      height: 600px;
      background: #111;
      border-radius: 40px;
      border: 4px solid #444;
      box-shadow: 0 0 20px #222;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding-top: 24px;
    }
    .logo {
      margin-bottom: 24px;
      width: 220px;
      height: 60px;
      background: #fff;
      display: flex;
      align-items: center;
      justify-content: center;
      border-radius: 10px;
      font-family: Arial, sans-serif;
      font-size: 16px;
      font-weight: bold;
      color: #0a3871;
    }
    .events {
      color: #0f0;
      font-family: Arial, sans-serif;
      font-size: 20px;
      text-align: center;
      margin-bottom: 12px;
    }
    .at-sec {
      color: #fff;
      font-family: Arial, sans-serif;
      font-size: 16px;
      text-align: center;
      margin-bottom: 28px;
    }
    .event-list {
      color: #fff;
      font-family: Arial, sans-serif;
      font-size: 17px;
      list-style: none;
      padding: 0;
      margin: 0;
    }
    .event-list li {
      margin-bottom: 18px;
      letter-spacing: 1px;
    }
    .event-list li::before {
      content: "★ ";
      color: #fff;
      margin-right: 7px;
    }
  </style>
</head>
<body>
  <div class="mobile-frame">
    <div class="logo">
      Saveetha Engineering College
    </div>
    <div class="events">
      "EVENT DAYS"
    </div>
    <div class="at-sec">
      AT SEC
    </div>
    <ul class="event-list">
      <li>ICEMS '25</li>
      <li>HACKATHON</li>
      <li>FLASH MOB</li>
      <li>CELENZA</li>
    </ul>
  </div>
</body>
</html>
```
ICEMS'24
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>ICEMS '25 Registration</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      margin: 0;
      background-color: #000;
      font-family: Arial, sans-serif;
    }

    .phone {
      width: 380px;
      max-width: 95%;
      background-color: yellow;
      border: 10px solid #000;
      border-radius: 40px;
      padding: 20px;
      box-sizing: border-box;
      text-align: center;
      position: relative;
    }

    .notch {
      width: 150px;
      height: 30px;
      background-color: black;
      border-radius: 0 0 20px 20px;
      position: absolute;
      top: 0;
      left: 50%;
      transform: translateX(-50%);
    }

    .logo {
      width: 100%;
      margin-top: 40px;
    }

    .title {
      font-size: 24px;
      font-weight: bold;
      margin: 20px 0 10px;
    }

    .subtitle {
      color: red;
      font-weight: bold;
      font-size: 14px;
      text-transform: uppercase;
      margin-bottom: 20px;
    }

    .info {
      font-size: 16px;
      margin: 10px 0;
    }

    .register-btn {
      background-color: lightgray;
      color: black;
      font-size: 18px;
      font-weight: bold;
      padding: 10px 20px;
      border: none;
      cursor: pointer;
      margin: 20px 0;
    }

    .register-btn:hover {
      background-color: #ddd;
    }

    .footer-text {
      font-size: 14px;
    }
  </style>
</head>
<body>
  <div class="phone">
    <div class="notch"></div>
    <img src="https://upload.wikimedia.org/wikipedia/commons/8/80/Saveetha_Engineering_College_logo.png" alt="College Logo" class="logo">

    <div class="title">“ICEMS ‘25”</div>

    <div class="subtitle">
      INTERNATIONAL CONFERENCE ON THE EDUCATION POST MILLENNIALS
    </div>

    <div class="info">DATE: 01/01/2026</div>
    <div class="info">PRIZE: 10,000/-</div>

    <button class="register-btn">REGISTER</button>

    <div class="footer-text">
      Participate and win the cash prize
    </div>
  </div>
</body>
</html>
```
HACKATHON
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hackathon Event - SEC</title>
  <style>
    body {
      background: #000;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .mobile-frame {
      width: 320px;
      height: 600px;
      background: #19a73c;
      border-radius: 38px;
      border: 4px solid #444;
      box-shadow: 0 0 20px #222;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding-top: 22px;
      padding-bottom: 22px;
      box-sizing: border-box;
      position: relative;
    }
    .logo {
      width: 220px;
      height: 60px;
      background: #fff;
      display: flex;
      align-items: center;
      justify-content: center;
      border-radius: 10px;
      font-family: Arial, sans-serif;
      font-size: 16px;
      font-weight: bold;
      color: #0a3871;
      margin-bottom: 18px;
    }
    .event-title {
      color: #fff;
      font-family: Arial, sans-serif;
      font-size: 24px;
      font-weight: bold;
      text-align: center;
      margin-bottom: 10px;
    }
    .description {
      color: #fff;
      font-family: Arial, sans-serif;
      font-size: 16px;
      text-align: center;
      margin-bottom: 24px;
    }
    .details {
      color: #fff;
      font-family: Arial, sans-serif;
      font-size: 20px;
      text-align: center;
      margin-bottom: 18px;
    }
    .register-btn {
      display: block;
      margin: 0 auto 16px auto;
      padding: 7px 32px;
      background: #fff;
      color: #19a73c;
      font-family: Arial, sans-serif;
      font-size: 18px;
      font-weight: bold;
      border: 2px solid #fff;
      border-radius: 6px;
      cursor: pointer;
      text-align: center;
    }
    .cash-message {
      color: #fff;
      font-family: Arial, sans-serif;
      font-size: 18px;
      position: absolute;
      left: 50%;
      bottom: 32px;
      transform: translateX(-50%);
      width: 90%;
      text-align: center;
    }
  </style>
</head>
<body>
  <div class="mobile-frame">
    <div class="logo">
      Saveetha Engineering College
    </div>
    <div class="event-title">
      "HACKATHON"
    </div>
    <div class="description">
      The word "hackathon"<br>
      is a combination of the word "hack" and<br>
      "marathon".
    </div>
    <div class="details">
      DATE:03/01/2026<br>
      PRIZE:1,00,000/-
    </div>
    <button class="register-btn">REGISTER</button>
    <div class="cash-message">
      Participate and win<br>
      the cash money
    </div>
  </div>
</body>
</html>
```
FLASH MOB
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Flash Mob Event - SEC</title>
  <style>
    body {
      background: #000;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .mobile-frame {
      width: 320px;
      height: 600px;
      background: #f71010;
      border-radius: 40px;
      border: 4px solid #444;
      box-shadow: 0 0 20px #222;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 24px 16px;
      box-sizing: border-box;
      position: relative;
    }
    .logo {
      width: 220px;
      height: 54px;
      background: #fff;
      display: flex;
      align-items: center;
      justify-content: center;
      border-radius: 10px;
      font-family: Arial, sans-serif;
      font-size: 15px;
      font-weight: bold;
      color: #0a3871;
      margin-bottom: 10px;
      margin-top: 2px;
    }
    .event-title {
      color: #fff;
      font-family: Arial, sans-serif;
      font-size: 28px;
      font-weight: bold;
      text-align: center;
      margin-bottom: 10px;
    }
    .description {
      color: #fff;
      font-family: Arial, sans-serif;
      font-size: 16px;
      text-align: center;
      margin-bottom: 26px;
    }
    .details {
      color: #fff;
      font-family: Arial, sans-serif;
      font-size: 22px;
      text-align: center;
      margin-bottom: 12px;
    }
    .register-btn {
      display: block;
      margin: 0 auto 18px auto;
      padding: 8px 30px;
      background: #fff;
      color: #f71010;
      font-family: Arial, sans-serif;
      font-size: 18px;
      font-weight: bold;
      border: 2px solid #f71010;
      border-radius: 6px;
      cursor: pointer;
      text-align: center;
      box-shadow: 1px 1px 2px #bbb;
    }
    .cash-message {
      color: #fff;
      font-family: Arial, sans-serif;
      font-size: 18px;
      background: rgba(0,0,0,0.11);
      border-radius: 8px;
      padding: 10px;
      position: absolute;
      left: 50%;
      bottom: 24px;
      transform: translateX(-50%);
      width: 88%;
      text-align: center;
    }
    .details .date,
    .details .prize {
      display: block;
      margin-bottom: 6px;
    }
    .details .date {
      color: #fc8989;
      font-size: 22px;
      font-weight: bold;
    }
    .details .prize {
      color: #870000;
      font-size: 22px;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <div class="mobile-frame">
    <div class="logo">
      Saveetha Engineering College
    </div>
    <div class="event-title">
      "FLASH MOB"
    </div>
    <div class="description">
      A celebration of joy,<br>
      energy, and rhythm,<br>
      where students dance<br>
      to the beats of a<br>
      live DJ.
    </div>
    <div class="details">
      <span class="date">DATE:05/01/2026</span>
      <span class="prize">PRIZE:50,000/-</span>
    </div>
    <button class="register-btn">REGISTER</button>
    <div class="cash-message">
      Participate and win<br>
      the prize money
    </div>
  </div>
</body>
</html>
```
CELENZA
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=320, initial-scale=1.0">
  <title>CELENZA - SEC</title>
  <style>
    body {
      background: #000;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .mobile-frame {
      width: 320px;
      height: 600px;
      background: #ef90e6;
      border-radius: 40px;
      border: 4px solid #444;
      box-shadow: 0 0 20px #222;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 24px 16px 0 16px;
      box-sizing: border-box;
      position: relative;
    }
    .logo {
      width: 220px;
      height: 54px;
      background: #fff;
      display: flex;
      align-items: center;
      justify-content: center;
      border-radius: 10px;
      font-family: Arial, sans-serif;
      font-size: 15px;
      font-weight: bold;
      color: #0a3871;
      margin-bottom: 12px;
      margin-top: 2px;
    }
    .event-title {
      color: #2a043f;
      font-family: Arial, sans-serif;
      font-size: 28px;
      font-weight: bold;
      text-align: center;
      margin-bottom: 14px;
    }
    .description {
      color: #121212;
      font-family: Arial, sans-serif;
      font-size: 16px;
      text-align: left;
      margin-bottom: 28px;
      line-height: 1.3;
    }
    .details {
      color: #e90038;
      font-family: Arial, sans-serif;
      font-size: 21px;
      font-weight: bold;
      text-align: left;
      margin-bottom: 22px;
    }
    .call-participate {
      color: #121212;
      font-family: Arial, sans-serif;
      font-size: 21px;
      font-weight: bold;
      text-align: left;
      margin-bottom: 32px;
      line-height: 1.2;
    }
  </style>
</head>
<body>
  <div class="mobile-frame">
    <div class="logo">
      Saveetha Engineering College
    </div>
    <div class="event-title">
      "CELENZA"
    </div>
    <div class="description">
      Cultural events and<br>
      activities that showcase<br>
      students talent,<br>
      innovation and<br>
      competitive spirit
    </div>
    <div class="details">
      DATE:10/01/2026
    </div>
    <div class="call-participate">
      COME AND<br>
      PARTICIPATE<br>
      AND ENJOY<br>
      THE EVENTS
    </div>
  </div>
</body>
</html>
```


## OUTPUT:
<img width="1916" height="965" alt="image" src="https://github.com/user-attachments/assets/eb6ad105-0cc9-47f0-b60e-86dfbb245b58" />
<img width="1913" height="965" alt="image" src="https://github.com/user-attachments/assets/d3020b41-326d-400d-9855-81dda0756d5f" />
<img width="1912" height="967" alt="image" src="https://github.com/user-attachments/assets/701d6dd3-1ced-4c6a-a82c-985799f92418" />
<img width="1916" height="971" alt="image" src="https://github.com/user-attachments/assets/d9ca8976-60e3-4fad-bebd-04431ed4f89a" />
<img width="1919" height="967" alt="image" src="https://github.com/user-attachments/assets/97ef396d-ab07-4d9e-8378-96db66b28ae6" />
<img width="1918" height="962" alt="image" src="https://github.com/user-attachments/assets/19344cb0-bc76-4225-ae4b-86d53c980698" />



## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
