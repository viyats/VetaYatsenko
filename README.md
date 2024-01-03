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
		<div class="hero">
			<h1>Hi, I'm [Your Name]</h1>
			<p>I'm an illustrator based in [Your City].</p>
			<button class="cta">View My Work</button>
		</div>
	</header>
	<main>
		<section id="about">
			<div class="about-content">
				<h2>About Me</h2>
				<p>Hi, my name is [Your Name] and I am an illustrator based in [Your City]. I specialize in [Your Illustration Style] and have been creating illustrations for [Number of Years] years. I am passionate about [Your Interests or Hobbies] and love to incorporate them into my work whenever possible.</p>
			</div>
			<div class="skills">
				<h2>Skills</h2>
				<ul>
					<li>Illustration</li>
					<li>Graphic Design</li>
					<li>Web Design</li>
				</ul>
			</div>
		</section>
		<section id="work">
			<h2>My Work</h2>
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
			<h2>Contact Me</h2>
			<form method="post" action="submit.php">
				<label for="name">Name:</label>
				<input type="text" name="name" required>
				<label for="email">Email:</label>
				<input type="email" name="email" required>
				<label for="message">Message:</label>
				<textarea name="message" required></textarea>
				<input type="submit" value="Send">
			</form>
             