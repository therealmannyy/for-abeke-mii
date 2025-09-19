<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For Abeke Faith Oluwaseun</title>
<style>
body {
margin: 0;
font-family: Arial, sans-serif;
background: linear-gradient(135deg, #fde2e4, #fad2e1, #e2ece9, #bee1e6);
color: #333;
text-align: center;
overflow-x: hidden;
}

header {
padding: 30px 15px 15px;
}
header h1 {
font-size: 1.8rem;
margin: 0;
color: #c72c48;
}
header p {
max-width: 600px;
margin: 15px auto;
font-size: 1rem;
line-height: 1.6;
padding: 0 10px;
}

.quote {
font-style: italic;
font-size: 0.95rem;
margin: 15px auto;
color: #444;
}

.gallery {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
gap: 15px;
padding: 20px;
}
.gallery img {
width: 100%;
border-radius: 10px;
box-shadow: 0 4px 8px rgba(0,0,0,0.2);
transition: transform 0.3s ease;
}
.gallery img:hover {
transform: scale(1.05);
}

footer {
margin: 30px 0;
font-size: 0.9rem;
color: #555;
}

/* Floating hearts */
.heart {
position: fixed;
bottom: -20px;
color: #ff4d6d;
font-size: 20px;
animation: floatUp 6s linear infinite;
}
@keyframes floatUp {
0% { transform: translateY(0) scale(1); opacity: 1; }
100% { transform: translateY(-100vh) scale(1.5); opacity: 0; }
}
</style>
</head>
<body>
<header>
<h1>For Abeke Faith Oluwaseun</h1>
<p>
I know I have not been the best man for you. I failed in ways I should not have, but I want you to know that I am truly sorry.
You deserve nothing but peace, love, and happiness. I will not disturb you anymore, but I want to leave this as a reminder
of my apology and the beautiful moments we shared.
</p>
<p class="quote">
"In you, I found love; in losing you, I found regret. But always, I will wish you peace and happiness."
</p>
</header>

<!-- ✅ Background music -->
<audio autoplay loop>
<source src="music.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>

<!-- ✅ Gallery -->
<section class="gallery">
<img src="images/photo1.jpg" alt="Memory 1">
<img src="images/photo2.jpg" alt="Memory 2">
<img src="images/photo3.jpg" alt="Memory 3">
<img src="images/photo4.jpg" alt="Memory 4">
<img src="images/photo5.jpg" alt="Memory 5">
<img src="images/photo6.jpg" alt="Memory 6">
<img src="images/photo7.jpg" alt="Memory 7">
<img src="images/photo8.jpg" alt="Memory 8">
</section>

<footer>
<p>With sincerity, always. ❤️</p>
</footer>

<!-- ✅ Floating hearts -->
<script>
function createHeart() {
const heart = document.createElement("div");
heart.className = "heart";
heart.innerHTML = "❤";
heart.style.left = Math.random() * 100 + "vw";
heart.style.fontSize = Math.random() * 15 + 15 + "px";
document.body.appendChild(heart);

setTimeout(() => heart.remove(), 6000);
}
setInterval(createHeart, 500);
</script>
</body>
</html>
# for-abeke-mii
