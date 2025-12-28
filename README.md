<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Anime Review Page</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background: #0f172a;
            color: #e5e7eb;
        }

        header {
            text-align: center;
            padding: 30px;
            background: linear-gradient(90deg, #7c3aed, #2563eb);
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        .container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            padding: 30px;
        }

        .card {
            background: #1e293b;
            border-radius: 12px;
            padding: 20px;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .card:hover {
            transform: translateY(-8px);
            box-shadow: 0 15px 30px rgba(0,0,0,0.4);
        }

        .card h2 {
            margin-top: 0;
            color: #a78bfa;
        }

        .rating {
            color: #facc15;
            font-size: 1.1rem;
            margin-bottom: 10px;
        }

        footer {
            text-align: center;
            padding: 15px;
            background: #020617;
            font-size: 0.9rem;
            color: #94a3b8;
        }
    </style>
</head>
<body>

<header>
    <h1>🔥 Anime Review Hub 🔥</h1>
    <p>Top Anime Worth Watching</p>
</header>

<div class="container">

    <div class="card">
        <h2>Death Note</h2>
        <div class="rating">⭐⭐⭐⭐⭐</div>
        <p>A psychological thriller about intelligence, morality, and power. Light vs L is legendary.</p>
    </div>

    <div class="card">
        <h2>Attack on Titan</h2>
        <div class="rating">⭐⭐⭐⭐⭐</div>
        <p>Dark, emotional, and philosophical. A masterpiece that questions freedom and humanity.</p>
    </div>

    <div class="card">
        <h2>Demon Slayer</h2>
        <div class="rating">⭐⭐⭐⭐☆</div>
        <p>Stunning animation with emotional storytelling and intense sword fights.</p>
    </div>

    <div class="card">
        <h2>Re:Zero</h2>
        <div class="rating">⭐⭐⭐⭐☆</div>
        <p>A dark isekai that focuses on suffering, growth, and psychological depth.</p>
    </div>

    <div class="card">
        <h2>Dr. Stone</h2>
        <div class="rating">⭐⭐⭐⭐☆</div>
        <p>Science meets survival. Educational, fun, and highly unique.</p>
    </div>

    <div class="card">
        <h2>Your Lie in April</h2>
        <div class="rating">⭐⭐⭐⭐⭐</div>
        <p>Beautiful, emotional, and heartbreaking. Music and emotions blend perfectly.</p>
    </div>

    <div class="card">
        <h2>Jujutsu Kaisen</h2>
        <div class="rating">⭐⭐⭐⭐☆</div>
        <p>Modern shonen with insane animation, cursed energy, and powerful characters.</p>
    </div>

    <div class="card">
        <h2>Classroom of the Elite</h2>
        <div class="rating">⭐⭐⭐⭐☆</div>
        <p>Mind games, manipulation, and a cold genius protagonist.</p>
    </div>

    <div class="card">
        <h2>Tokyo Revengers</h2>
        <div class="rating">⭐⭐⭐☆☆</div>
        <p>Time travel mixed with gang drama and emotional storytelling.</p>
    </div>

    <div class="card">
        <h2>Erased</h2>
        <div class="rating">⭐⭐⭐⭐☆</div>
        <p>Thrilling mystery involving time travel and saving innocent lives.</p>
    </div>

    <div class="card">
        <h2>Spy × Family</h2>
        <div class="rating">⭐⭐⭐⭐☆</div>
        <p>Comedy, action, and wholesome family moments with Anya stealing the show.</p>
    </div>

    <div class="card">
        <h2>Solo Leveling</h2>
        <div class="rating">⭐⭐⭐⭐⭐</div>
        <p>Pure hype. Power fantasy done right with amazing fights and growth.</p>
    </div>

</div>

<footer>
    © 2025 Anime Review Hub | Made for Anime Fans ❤️
</footer>

</body>
</html>

