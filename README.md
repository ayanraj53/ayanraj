<!DOCTYPE html>

<html>

<head>

	<title>HTML By Ayan</title>

	<style>

		body {

			background-color: #F0EDE5;

			font-family: Arial, sans-serif;

			color: #555;

			margin: 0;

			padding: 0;

		}

		h1, h2, h3 {

			font-weight: normal;

			color: #B6814A;

			margin: 20px 0;

			text-align: center;

			text-transform: uppercase;

			letter-spacing: 2px;

		}

		h1 {

			font-size: 40px;

		}

		h2 {

			font-size: 30px;

		}

		h3 {

			font-size: 20px;

		}

		p {

			font-size: 18px;

			line-height: 1.5;

			margin: 0 0 20px;

			padding: 0 20px;

			text-align: justify;

		}

		img {

			display: block;

			margin: 0 auto;

			max-width: 100%;

			height: auto;

			border: 5px solid #B6814A;

			border-radius: 10px;

		}

		ul {

			list-style: none;

			padding: 0;

			margin: 20px 0;

			display: flex;

			flex-wrap: wrap;

			justify-content: center;

		}

		li {

			margin: 10px;

			font-size: 18px;

			background-color: #B6814A;

			padding: 10px;

			border-radius: 5px;

		}

		li a {

			color: #fff;

			text-decoration: none;

			font-weight: bold;

			text-transform: uppercase;

			letter-spacing: 1px;

			transition: color 0.3s ease;

		}

		li a:hover {

			color: #F0EDE5;

		}

		ol {

			margin: 20px 0;

			padding: 0 20px;

			font-size: 18px;

		}

		table {

			width: 100%;

			border-collapse: collapse;

			margin: 20px 0;

			font-size: 18px;

		}

		th, td {

			padding: 10px;

			text-align: left;

			border: 1px solid #B6814A;

		}

		form {

			max-width: 500px;

			margin: 20px auto;

			padding: 20px;

			background-color: #fff;

			box-shadow: 0 0 10px rgba(0,0,0,0.1);

			border-radius: 10px;

		}

		label {

			display: block;

			margin-bottom: 10px;

			font-size: 18px;

			color: #B6814A;

		}

		input[type="text"], input[type="email"], textarea {

			width: 100%;

			padding: 10px;

			margin-bottom: 20px;

			border: none;

			border-radius: 5px;

			font-size: 18px;

			color: #555;

			background-color: #F0EDE5;

			resize: none;

		}

		input[type="submit"] {

			background-color: #B6814A;

			color:  #fff;

		padding: 10px 20px;

		border: none;

		border-radius: 5px;

		font-size: 18px;

		font-weight: bold;

		text-transform: uppercase;

		letter-spacing: 1px;

		cursor: pointer;

		transition: background-color 0.3s ease;

	}

	input[type="submit"]:hover {

		background-color: #FFC857;

	}

	footer {

		background-color: #555;

		color: #fff;

		padding: 20px;

		text-align: center;

		font-size: 18px;

		position: absolute;

		bottom: 0;

		width: 100%;

	}

	@media (max-width: 768px) {

		h1 {

			font-size: 30px;

		}

		h2 {

			font-size: 25px;

		}

		h3 {

			font-size: 20px;

		}

		p {

			font-size: 16px;

		}

		ul {

			margin: 10px 0;

		}

		li {

			margin: 5px;

			font-size: 16px;

			padding: 5px;

		}

		table {

			font-size: 16px;

		}

		input[type="text"], input[type="email"], textarea {

			font-size: 16px;

		}

	}

</style>

</head>

<body>

	<header>

		<h1>HTML By Ayan</h1>

		<nav>

			<ul>

				<li><a href="#section1">Section 1</a></li>

				<li><a href="#section2">Section 2</a></li>

				<li><a href="#section3">Section 3</a></li>

			</ul>

		</nav>

	</header>

<main>

	<section id="section1">

		<h2>Section 1</h2>

		<p>"HTML (Hypertext Markup Language) is a programming language used to create and design web pages. It provides the structure and content of a webpage, defining the layout, text, images, and other multimedia elements. HTML is considered the backbone of the internet as it forms the basis for most websites. It uses a system of tags and attributes to describe how content should be displayed on a page. HTML is easy to learn and use, making it accessible to beginners as well as professional web developers. It is also compatible with a wide range of web browsers and devices, making it an essential tool for creating websites that can be accessed by anyone, anywhere, anytime.</p>

		<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEi-OppMHDP1mPU1Q_D-gLFIWTmIt7o4BZqZK5NYtzFOgVIb8i6eC4rz0t1_CWmsS7rphq3JD7BtZBF6EYGHe8IIR5HRSHIE5m0PcUfcxqJfsb1QRTZL6USuUWOJGzwouRESdQZzNoSzs41ZNEbY1cUfYuIyTpqbdsK27gr7dpssaLebk0fsGbgc2ei2/s2828/_ayanraj_.jpg" alt="Placeholder Image">

	</section>

	<section id="section2">

		<h2>Section 2</h2>

		<ol>

			<li>Item 1</li>

			<li>Item 2</li>

			<li>Item 3</li>

		</ol>

		<table>

			<thead>

				<tr>

					<th>Positions</th>

					<th>Languages</th>

				</tr>

			</thead>

			<tbody>

				<tr>

					<td>1<sup>st</sup></td>
					<td>JS</td>

				</tr>

				<tr>

					<td>2<sup>nd</sup></td>

					<td>Python</td>

</tr>

<tr>

<td>3<sup>rd</sup></td>
<td>HTML</td>

</tr>

</tbody>

</table>

<form action="https://formsubmit.co/el/pidino" method="POST"/>

<label for="name">Name:</label>

<input type="text" id="name" name="name" required>

<label for="email">Email:</label>

<input type="email" id="email" name="email" required>

<label for="message">Message:</label>

<textarea id="message" name="message" required></textarea>

<input type="submit" value="Submit">

</form>

</section>

	<section id="section3">

		<h2>Section 3</h2>

		<ul>

			<li>Item 1</li>

			<li>Item 2</li>

			<li>Item 3</li>

		</ul>

		<h3>Contact Us</h3>

		<p>Contact me</p>

		<p>Whatapp: <a href="https://wa.me/message/FQWQ6MHFEYUFB1">ㅤ</a></p>

		<p>Email:av0oxo0va@gmail.com
</p>

	</section>

</main>
</body>

</html>
