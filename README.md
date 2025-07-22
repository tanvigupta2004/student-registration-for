<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Student Registration Form with HTML5 Validation</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 40px;
    }

    h1 {
      color: #333;
    }

    label {
      display: block;
      margin-top: 10px;
    }

    input {
      padding: 8px;
      width: 250px;
      margin-top: 5px;
    }

    button {
      margin-top: 15px;
      padding: 10px 15px;
      background-color: #4CAF50;
      color: white;
      border: none;
      cursor: pointer;
    }

    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>
  <h1>Student Registration Form</h1>
  <form>
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" placeholder="Enter your full name" required>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" placeholder="Enter your email" required>

    <label for="age">Age:</label>
    <input type="number" id="age" name="age" min="1" max="120" placeholder="Enter your age" required>

    <button type="submit">Register</button>
  </form>
</body>
</html>
