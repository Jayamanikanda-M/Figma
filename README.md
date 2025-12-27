# Ex09 Event Registration Web Application
## Date: 26-12-25

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Event Registration</title>
  <style>
    body {
      background-color: #f0f8ff;
      font-family: Arial, sans-serif;
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    .container {
      background: #ffffff;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.15);
      width: 400px; /* fixed width for form */
    }
    h1 {
      text-align: center;
    }
    form {
      margin-top: 20px;
    }
    label {
      display: block;
      margin-top: 10px;
      text-align: left;
    }
    input[type="text"],
    input[type="email"],
    input[type="tel"],
    textarea,
    select {
      width: 100%; /* full width */
      padding: 8px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    .gender-group {
      display: flex;
      gap: 15px; /* spacing between options */
      margin-top: 5px;
    }
    .gender-group label {
      display: inline; /* keep labels inline with radios */
      margin-top: 0;
    }
    input[type="submit"], input[type="reset"] {
      margin: 15px 5px 0;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      background: #4682b4;
      color: #fff;
      font-weight: bold;
    }
    input[type="reset"] {
      background: #999;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Event Registration Form</h1>
    <form action="thankyou.html" method="post">
      <!-- First Name -->
      <label for="fname">First Name:</label>
      <input type="text" id="fname" name="fname" required>

      <!-- Last Name -->
      <label for="lname">Last Name:</label>
      <input type="text" id="lname" name="lname" required>

      <!-- Email -->
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>

      <!-- Mobile -->
      <label for="mobile">Mobile Number:</label>
      <input type="tel" id="mobile" name="mobile" required>

      <!-- Gender -->
      <label>Gender:</label>
      <div class="gender-group">
        <input type="radio" id="male" name="gender" value="male">
        <label for="male">Male</label>

        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label>

        <input type="radio" id="other" name="gender" value="other">
        <label for="other">Other</label>
      </div>

      <!-- Address -->
      <label for="address">Address:</label>
      <textarea id="address" name="address" rows="3"></textarea>

      <!-- Event Selection -->
      <label for="event">Select Event:</label>
      <select id="event" name="event" required>
        <option value="">--Choose an event--</option>
        <option value="workshop">Workshop</option>
        <option value="seminar">Seminar</option>
        <option value="concert">Concert</option>
      </select>

      <!-- Submit -->
      <input type="submit" value="Register">
      <input type="reset" value="Reset">
    </form>
  </div>
</body>
</html>
```


## OUTPUT:
<img width="677" height="999" alt="image" src="https://github.com/user-attachments/assets/36206683-4379-4709-a844-0b6fbd589cb2" />



## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
