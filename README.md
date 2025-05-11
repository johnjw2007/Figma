# Ex09 Event Registration Web Application
# Date:10-5-2025
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
PAGE 1
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Saveetha Engineering College</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #99b3e6;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .header {
      background-color: #001f4d;
      width: 100%;
      padding: 10px;
      text-align: center;
    }

    .header img {
      max-width: 100%;
      height: auto;
    }

    .container {
      margin-top: 100px;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .button {
      background-color: #f2f2f2;
      color: #000;
      padding: 15px 30px;
      margin: 15px;
      border: none;
      font-size: 16px;
      cursor: pointer;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      transition: 0.3s;
    }

    .button:hover {
      background-color: #e0e0e0;
    }
  </style>
</head>
<body>
  <div class="header">
    <img src="https://i.imgur.com/SZyFHlg.png" alt="Saveetha Engineering College Banner">
  </div>

  <div class="container">
    <button class="button">LOGIN</button>
    <button class="button">REGISTER</button>
  </div>
</body>
</html>
```
PAGE 2
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Events - Saveetha Engineering College</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-image: url('https://i.imgur.com/mKnxwEL.png'); /* Replace with your own image path */
      background-size: cover;
      background-position: center;
      height: 100vh;
      color: black;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .events-container {
      text-align: center;
      background-color: rgba(255, 255, 255, 0.1); /* optional overlay */
      padding: 20px;
    }

    .events-container h1 {
      font-size: 28px;
      font-style: italic;
      font-weight: bold;
      margin-bottom: 20px;
    }

    .events-container ul {
      list-style-type: none;
      padding: 0;
      font-size: 22px;
      font-style: italic;
    }

    .events-container li {
      margin: 10px 0;
    }
  </style>
</head>
<body>
  <div class="events-container">
    <h1>EVENTS</h1>
    <ul>
      <li>Football</li>
      <li>Cricket</li>
      <li>Basketball</li>
      <li>Tennis Table</li>
      <li>Badminton</li>
      <li>Volleyball</li>
      <li>Hockey</li>
      <li>Athletics</li>
    </ul>
  </div>
</body>
</html>
```
PAGE 3

```<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Event Registration</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-image: url('https://i.imgur.com/mKnxwEL.png'); /* Replace with your actual image path */
      background-size: cover;
      background-position: center;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
    } 

    .form-container {
      text-align: center;
      width: 80%;
      max-width: 400px;
    }

    .form-container input,
    .form-container select,
    .form-container button {
      width: 100%;
      padding: 12px;
      margin: 12px 0;
      font-size: 18px;
      text-align: center;
      border: none;
      background-color: rgba(255, 255, 255, 0.8);
      box-shadow: 2px 2px 5px rgba(0,0,0,0.2);
    }

    .form-container button {
      font-weight: bold;
      cursor: pointer;
      transition: background-color 0.3s;
    }

    .form-container button:hover {
      background-color: #ddd;
    }
  </style>
</head>
<body>
  <div class="form-container">
    <form>
      <input type="text" placeholder="REGISTRATION" name="registration" required>
      <input type="text" placeholder="NAME" name="name" required>
      <input type="tel" placeholder="PHONE NUMBER" name="phone" required>
      <select name="event" required>
        <option value="" disabled selected>CHOOSE EVENT</option>
        <option value="Football">Football</option>
        <option value="Cricket">Cricket</option>
        <option value="Basketball">Basketball</option>
        <option value="Tennis Table">Tennis Table</option>
        <option value="Badminton">Badminton</option>
        <option value="Volleyball">Volleyball</option>
        <option value="Hockey">Hockey</option>
        <option value="Athletics">Athletics</option>
      </select>
      <input type="text" placeholder="DEPARTMENT" name="department" required>
      <button type="submit">SUBMIT</button>
    </form>
  </div>
</body>
</html>

```
PAGE4

```<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Registration Success</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #99b3e6;
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
    }

    .header {
      background-color: #001f4d;
      width: 100%;
      padding: 10px;
    } 

    .header img {
      max-width: 100%;
      height: auto;
    }

    .message {
      margin-top: 100px;
      font-size: 24px;
      font-style: italic;
      font-weight: bold;
    }

    .contact {
      margin-top: 100px;
      font-size: 16px;
      font-style: italic;
    }

    .contact a {
      display: block;
      font-weight: bold;
      font-style: normal;
      text-decoration: none;
      color: black;
      margin-top: 5px;
    }

    .contact p {
      margin: 5px 0 0;
    }
  </style>
</head>
<body>
  <div class="header">
    <img src="https://i.imgur.com/SZyFHlg.png" alt="Saveetha Engineering College Banner">
  </div>

  <div class="message">
    THANK YOU FOR REGISTERING
  </div>

  <div class="contact">
    CONTACT US <br>
    <a href="https://www.saveetha.com" target="_blank">WWW.SAVEETHA.COM</a>
    <p>saveethaengineerin@gmail.com</p>
  </div>
</body>
</html>

```
# OUTPUT:
![alt text](<Screenshot 2025-05-11 185713.png>)
# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
