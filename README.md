# VetaYatsenko
<!DOCTYPE html>
<html>
<head>
	<title>My Portfolio</title>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<header>
		<nav>
			<ul>
				<li><a href="#about">About Me</a></li>
				<li><a href="#work">My Work</a></li>
				<li><a href="#contact">Contact Me</a></li>
			</ul>
		</nav>
	</header>
	<main>
		<section id="about">
			<h1>About Me</h1>
			<p>Hi, my name is [Your Name] and I am an illustrator based in [Your City]. I specialize in [Your Illustration Style] and have been creating illustrations for [Number of Years] years. I am passionate about [Your Interests or Hobbies] and love to incorporate them into my work whenever possible.</p>
		</section>
		<section id="work">
			<h1>My Work</h1>
			<div class="gallery">
				<a href="image1.jpg"><img src="thumb1.jpg"></a>
				<a href="image2.jpg"><img src="thumb2.jpg"></a>
				<a href="image3.jpg"><img src="thumb3.jpg"></a>
				<a href="image4.jpg"><img src="thumb4.jpg"></a>
				<a href="image5.jpg"><img src="thumb5.jpg"></a>
				<a href="image6.jpg"><img src="thumb6.jpg"></a>
			</div>
		</section>
		<section id="contact">
			<h1>Contact Me</h1>
			<form method="post" action="submit.php">
				<label for="name">Name:</label>
				<input type="text" name="name" required>
				<label for="email">Email:</label>
				<input type="email" name="email" required>
				<label for="message">Message:</label>
				<textarea name="message" required></textarea>
				<input type="submit" value="Send">
			</form>
		</section>
	</main>
	<footer>
		<p>Copyright © [Your Year]
		[Your Name]. All rights reserved.</p>
	</footer>
</body>
</html>
