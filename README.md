<!DOCTYPE html>
<html>
<head>
<title>SignUp</title>
<style>
input[type="text"],input[type="email"],input[type="password"] {
display:block;
width: 100%;
padding: 10px;
font-size: 16px;
line-height: 1.5;
border-radius: 5px;
border: 1px solid #ccc;
box-sizing: border-box;
margin-bottom: 20px;
}
input[type="submit"] {
display: block;
width: 100%;
padding: 10px;
background-color: red;
color: #fff;
font-size: 16px;
line-height: 1.5;
border: none;
border-radius: 5px;
cursor: pointer;
}
</style>
</head>
<body>
<div class="container">
<h1>Sign Up</h1>
<form action="submit.php" method="post">
<label for="username">Username:</label>
<input type="text" id="username" name="username" required>
<label for="email">Email:</label>
<input type="email" id="email" name="email" required>
<label for="password">Password:</label>
<input type="password" id="password" name="password" minlength="8" required>
<label for="conform-password">Conform Password:</label>
<input type="password id="conform-password" name="conform-password" minlength="8" required>
<input type="submit" value="Sign Up">
</form>
</div>
</body>
</html>
