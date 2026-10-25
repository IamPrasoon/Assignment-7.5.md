
<!DOCTYPE html>
<html lang="en">
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>CodeWithPrasoon</title>
<style>
* { box-sizing: border-box; }
body { margin: 0; font-family: Arial; color: #222; }
header, .hero, .features {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    gap: 20px;
    padding: 25px;
}
header, footer { background: navy; color: white; }
nav { display: flex; flex-wrap: wrap; gap: 15px; }
nav a { color: white; text-decoration: none; }
.hero { background: lightblue; }
.hero img { width: 300px; max-width: 100%; }
.card {
    flex: 1 1 200px;
    background: #eee;
    padding: 20px;
    border-radius: 10px;
}
.cta, footer { text-align: center; padding: 30px; }
button { padding: 12px; background: orange; border: 0; }
</style>
</head>
<body>
<header>
    <h2>CodeWithPrasoon</h2>
    <nav>
        <a href="#home">Home</a>
        <a href="#features">Features</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<main>
    <section class="hero" id="home">
        <div>
            <h1>Learn Web Development</h1>
            <p>Build websites using HTML, CSS and JavaScript.</p>
            <button onclick="location.href='#features'">Get Started</button>
        </div>
        <img src="coding.jpg" alt="Coding illustration">
    </section>

    <section class="features" id="features">
        <div class="card"><h3>HTML</h3><p>Learn structure.</p></div>
        <div class="card"><h3>CSS</h3><p>Learn styling.</p></div>
        <div class="card"><h3>JavaScript</h3><p>Learn interactivity.</p></div>
    </section>

    <section class="cta">
        <h2>Start Learning Today!</h2>
        <button onclick="location.href='#contact'">Join Now</button>
    </section>
</main>

<footer id="contact">
    <p>Contact: anandprasoon6@gmail.com</p>
    <p>&copy; 2026 Prasoon Anand</p>
</footer>
</body>
</html>
