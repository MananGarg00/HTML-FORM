# HTML-FORM
Basic details of user with name, phone no. and email ID

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>User Information Form</title>
</head>
<body>
<h1>User Information Form</h1>
<form action="submit_form.php" method="POST">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required><br><br>
    
    <label for="phone">Phone No.:</label>
    <input type="tel" id="phone" name="phone" pattern="[0-9]{10}" required><br><br>
    
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required><br><br>
    
    <label>Gender:</label>
    <input type="radio" id="male" name="gender" value="male" required>
    <label for="male">Male</label>
    <input type="radio" id="female" name="gender" value="female" required>
    <label for="female">Female</label>
    <input type="radio" id="other" name="gender" value="other" required>
    <label for="other">Other</label><br><br>
    
    <input type="submit" value="Submit">
</form>
</body>
</html>
