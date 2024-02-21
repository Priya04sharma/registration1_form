# registration1_form
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Registration Form</title>
<style>
  /* Form Styles */
  form {
    max-width: 400px;
    margin: 0 auto;
    padding: 20px;
    background: #f4f7f6;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }

  h2 {
    margin-top: 0;
    text-align: center;
    color: #333;
  }

  label {
    display: block;
    margin-bottom: 5px;
    color: #555;
  }

  input[type="text"],
  input[type="password"],
  input[type="email"],
  select {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ccc;
    border-radius: 5px;
    box-sizing: border-box;
  }

  input[type="submit"] {
    background-color: #4CAF50;
    color: white;
    padding: 12px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    width: 100%;
    font-size: 16px;
  }

  input[type="submit"]:hover {
    background-color: #45a049;
  }

  /* Background Image */
  body {
    background-image: url('background-image.jpg'); /* Replace 'background-image.jpg' with the path to your image */
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
    font-family: Arial, sans-serif; /* Ensure readable text on top of background image */
  }
</style>
</head>
<body>

<h2>Registration Form</h2>

<form>
  <h3>Personal Information</h3>
  <label for="username">Username:</label>
  <input type="text" id="username" name="username">

  <label for="password">Password:</label>
  <input type="password" id="password" name="password">

  <label for="email">Email:</label>
  <input type="email" id="email" name="email">

  <label for="location">Location:</label>
  <input type="text" id="location" name="location">

  <h3>Service Information</h3>
  <label for="service">Type of Service Required:</label>
  <select id="service" name="service">
    <option value="plumbing">Plumbing</option>
    <option value="electrician">Electrician</option>
    <option value="scrap dealer">Scrap Dealer</option>
    <option value="other">Other</option>
  </select>

  <input type="submit" value="Submit">
</form>

</body>
</html>
