# surveyform
<html lang="en">
<head>

</head>

<body>
<h1 id="title">Popular Music Survey</h1>
<p id="description">This is a survey where you can tell us about your favorite music hosted by freecodecamp.</p><br>
<p>Contact Information</p><br>
<form id="survey-form">
	<label id="name-label">Name:</label> <input type="text" name="name" id="name" required placeholder="first"></input><br>
	<label id="email-label">Email:</label> <input type="email" name="email" id="email" required placeholder="john@123.com"></input><br>
	<label id="number-label">Number:</label> <input type="number" name="number" id="number" min="0" max="9" required placeholder="123"></input><br>
	<input type="submit"><br>
<p>Please select your favorite type of music</p><br>
	<label for="music">Choose a genre:</label>
		<select id="dropdown" name="music">
  			<option value="rap">Rap</option>
 			 <option value="county">County</option>
  			<option value="metal">Metal</option>
  			<option value="electronic">Elecrtonic</option>
		</select><br>
<p>Please help us sort our surveyors:</p><br>
<input type="radio" id="male" name="gender" value="Male"><label for="male">Male</label><br>
<input type="radio" id="female" name="gender" value="Female"><label for="female">Female</label><br>
<input type="radio" id="transgender" name="gender" value="Transgender"><label for="transgender">Transgender</label><br>
<p>would you like to get your results emailed to you?</p>
<input type="checkbox" id="yes-emails" name="yes" value="yes"><label for="yes-emails"> Yes I want emails!</label><br>
<input type="checkbox" id="no-emails" name="no" value="No"><label for="no-emails"> No, fuck emails</label><br>
<textarea placeholder="Additional comments"></textarea>
<input type="submit" id="submit">
</form>
</body>
</html>
