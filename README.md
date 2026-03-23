

</body>
</html>
<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>अनसुलझा कवि</title>

<style>
body {
  margin: 0;
  font-family: "Noto Sans Devanagari", sans-serif;
  background: linear-gradient(135deg, #0f172a, #020617);
  color: #f1f5f9;
}

/* HEADER */
header {
  text-align: center;
  padding: 60px 20px;
  background: rgba(30,41,59,0.8);
  backdrop-filter: blur(10px);
}

header h1 {
  font-size: 42px;
  margin: 0;
  letter-spacing: 2px;
}

header p {
  font-size: 18px;
  color: #94a3b8;
}

/* NAVBAR */
nav {
  text-align: center;
  padding: 15px;
  background: #020617;
}

nav a {
  color: #38bdf8;
  margin: 0 15px;
  text-decoration: none;
  font-size: 18px;
  transition: 0.3s;
}

nav a:hover {
  color: #facc15;
}

/* SECTION */
section {
  padding: 40px;
  max-width: 800px;
  margin: auto;
}

/* POEM CARD */
.poem {
  background: #1e293b;
  padding: 20px;
  margin-bottom: 25px;
  border-radius: 12px;
  transition: 0.4s;
  box-shadow: 0 0 0 transparent;
}

.poem:hover {
  transform: translateY(-8px);
  box-shadow: 0 10px 25px rgba(0,0,0,0.5);
}

.poem h2 {
  margin-top: 0;
  color: #38bdf8;
}

/* FOOTER */
footer {
  text-align: center;
  padding: 20px;
  background: #020617;
  color: #64748b;
}

/* ANIMATION */
.fade-in {
  opacity: 0;
  transform: translateY(20px);
  animation: fadeIn 1s forwards;
}

@keyframes fadeIn {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
</style>
</head>

<body>

<header>
  <h1>अनसुलझा कवि</h1>
  <p>शब्दों में छुपी अधूरी कहानियाँ...</p>
</header>

<nav>
  <a href="#">होम</a>
  <a href="#">कविताएँ</a>
  <a href="#">मेरे बारे में</a>
</nav>

<section>

  <div class="poem fade-in">
    <h2>खामोशी</h2>
    <p>
      कुछ बातें कह नहीं पाता,<br>
      कुछ दर्द दिख नहीं पाता,<br>
      ये खामोशी ही मेरी आवाज़ है,<br>
      जिसे कोई सुन नहीं पाता...
    </p>
  </div>

  <div class="poem fade-in" style="animation-delay:0.3s;">
    <h2>अधूरी कहानी</h2>
    <p>
      वो मिला भी तो ऐसे जैसे सपना,<br>
      और चला भी गया बिना कुछ कहे,<br>
      अब बस यादें हैं...<br>
      जो पूरी होकर भी अधूरी लगती हैं।
    </p>
  </div>

</section>

<footer>
  © 2026 अनसुलझा कवि | Nitin
</footer>

</body>
</html>
