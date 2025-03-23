<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>This is just a demo, proceed at your own descretion</title>
<style>
body {
font-family: Arial, sans-serif;
margin: 20px;
background-color: #f5f5f5;
}
form {
background: #fff;
padding: 20px;
border-radius: 10px;
width: 350px;
box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
}
table {
width: 100%;
border-collapse: collapse;
margin-top: 20px;
}
table, th, td {
border: 1px solid black;
padding: 10px;
text-align: left;
}
ol {
background: #fff;
padding: 15px;
border-radius: 5px;
}
</style>
</head>
<body>

<h1>Let's try a couple of things here</h1>

<!-- Audio Element -->
<h2>Background Music</h2>
<audio controls>
<source src="audio.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>

<!-- Video Element -->
<h2>Introduction Video</h2>
<video width="500" controls>
<source src="video.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>

<!-- Ordered List with Roman Numerals -->
<h2>Website Features</h2>
<ol type="I">
<li>Interactive Multimedia</li>
<li>Well-Structured Forms</li>
<li>Contact Information Table</li>
<li>External Images</li>
<li>HTML5 Best Practices</li>
</ol>

<!-- External Image -->
<h2>Featured Image</h2>
<img src="https://images.pexels.com/photos/3183153/pexels-photo-3183153.jpeg" 
alt="People Working on Laptops" width="400">

<!-- Contacts Table -->
<h2>Contact List</h2>
<table>
<tr>
<th>Name</th>
<th>Address</th>
<th>Mobile</th>
<th>Email</th>
</tr>
<tr>
<td>John Kirabati</td>
<td>1070345, NY</td>
<td>+1234567890</td>
<td>johnkirabati@gmail.com</td>
</tr>
<tr>
<td>James Bond</td>
<td>456 London Rd, UK</td>
<td>+44987654321</td>
<td>jamesbond@hotmail.com</td>
</tr>
<tr>
<td>Michael Jordan</td>
<td>789 Bulls St, Chicago</td>
<td>+1 456 789 012</td>
<td>michaelthagoat@yahoo.com</td>
</tr>
<tr>
<td>Magic Johnson</td>
<td>101 Lakers St, CA</td>
<td>+1321654987</td>
<td>thebestmj@gmail.com</td>
</tr>
<tr>
<td>Larry Bird</td>
<td>202 Boston St, MA</td>
<td>+1654987123</td>
<td>celticlarry@larrybird.com</td>
</tr>
</table>

<!-- Registration Form -->
<h2>Register Here</h2>
<form action="#" method="post">
<!-- Name Field -->
<label for="name">Full Name:</label><br>
<input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>

<!-- Email Field -->
<label for="email">Email:</label><br>
<input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

<!-- Password Field -->
<label for="password">Password:</label><br>
<input type="password" id="password" name="password" placeholder="Choose a password" required minlength="6"><br><br>

<!-- Date Field -->
<label for="dob">Date of Birth:</label><br>
<input type="date" id="dob" name="dob" required><br><br>

<!-- Dropdown -->
<label for="country">Select Country:</label><br>
<select id="country" name="country" required>
<option value="">--Choose--</option>
<option value="USA">USA</option>
<option value="Canada">Canada</option>
<option value="UK">UK</option>
<option value="Australia">Australia</option>
</select><br><br>

<!-- Radio Buttons -->
<label>Gender:</label><br>
<input type="radio" id="male" name="gender" value="male" required>
<label for="male">Male</label>
<input type="radio" id="female" name="gender" value="female" required>
<label for="female">Female</label><br><br>

<!-- Checkboxes -->
<label>Interests:</label><br>
<input type="checkbox" id="coding" name="interests" value="coding">
<label for="coding">Coding</label>
<input type="checkbox" id="design" name="interests" value="design">
<label for="design">Design</label>
<input type="checkbox" id="gaming" name="interests" value="gaming">
<label for="gaming">Gaming</label><br><br>

<!-- Submit Button -->
<input type="submit" value="Register">
</form>

</body>
</html>
