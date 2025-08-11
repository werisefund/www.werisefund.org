<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>We Rise Fund</title>
<link href="https://fonts.googleapis.com/css2?family=Lora&family=Montserrat:wght@600&display=swap" rel="stylesheet">
<style>
  body {
    margin: 0;
    font-family: 'Lora', serif;
    background-color: #F5F9F9;
    color: #333;
    scroll-behavior: smooth;
  }
  header {
    background: linear-gradient(rgba(0, 121, 107, 0.8), rgba(0, 121, 107, 0.8)), 
                url('hero-image.jpg') center/cover no-repeat;
    color: white;
    text-align: center;
    padding: 80px 20px;
  }
  header h1 {
    font-family: 'Montserrat', sans-serif;
    font-size: 3rem;
    margin-bottom: 10px;
  }
  header p {
    font-size: 1.3rem;
    max-width: 600px;
    margin: auto;
  }
  .btn {
    background: #FF7043;
    color: white;
    padding: 14px 28px;
    border-radius: 8px;
    text-decoration: none;
    display: inline-block;
    margin-top: 20px;
    font-family: 'Montserrat', sans-serif;
    transition: 0.3s;
  }
  .btn:hover { background: #e85c2d; transform: scale(1.05); }
  .section {
    padding: 60px 20px;
    text-align: center;
    max-width: 1100px;
    margin: auto;
  }
  .section h2 {
    color: #00796B;
    font-family: 'Montserrat', sans-serif;
    font-size: 2rem;
    margin-bottom: 20px;
  }
  .cards {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
  }
  .card {
    background: white;
    border-radius: 10px;
    padding: 25px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    flex: 1 1 calc(33% - 20px);
    max-width: 300px;
    transition: transform 0.3s ease;
  }
  .card:hover { transform: translateY(-8px); }
  footer {
    background: #00796B;
    color: white;
    text-align: center;
    padding: 20px;
  }
  footer a {
    color: #FFD180;
    margin: 0 10px;
    text-decoration: none;
  }
  @media (max-width: 768px) {
    .card { flex: 1 1 100%; }
    header h1 { font-size: 2.2rem; }
  }
</style>
</head>
<body>

<header>
  <h1>Break Free From Debt — Together</h1>
  <p>Join a movement helping people escape debt with the power of community support.</p>
  <a href="#donate" class="btn">Donate Now</a>
</header>

<section class="section" id="how">
  <h2>How It Works</h2>
  <div class="cards">
    <div class="card"><h3>1. Join</h3><p>Become part of our community of supporters.</p></div>
    <div class="card"><h3>2. Nominate</h3><p>Help someone by nominating them to receive funds.</p></div>
    <div class="card"><h3>3. Pay Off Debt</h3><p>We send funds directly to pay off their debt.</p></div>
  </div>
</section>

<section class="section" id="donate">
  <h2>Donation Tiers</h2>
  <div class="cards">
    <div class="card"><h3>Lift a Little — $5</h3><a href="#" class="btn">Give $5</a></div>
    <div class="card"><h3>Lift a Lot — $25</h3><a href="#" class="btn">Give $25</a></div>
    <div class="card"><h3>Sponsor a Story — $100</h3><a href="#" class="btn">Give $100</a></div>
  </div>
</section>

<footer>
  <p>© 2025 We Rise Fund | <a href="#">Facebook</a> | <a href="#">Instagram</a></p>
</footer>

</body>
</html>
