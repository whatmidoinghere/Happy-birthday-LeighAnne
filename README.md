# Happy-birthday-LeighAnne
A simple birthday website for our project
<!doctype html>

<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Happy 19th Birthday Princess LeighAnne</title>
  <meta name="description" content="A simple birthday landing page for Princess LeighAnne." />
  <style>
    :root{--bg:#0f1724;--card:#0b1220;--accent:#fddb92;--muted:#94a3b8}
    *{box-sizing:border-box}
    body{margin:0;font-family:system-ui,-apple-system,Segoe UI,Roboto,'Helvetica Neue',Arial;color:#e6eef8;background:linear-gradient(180deg,#071129 0%, #081023 60%);line-height:1.4}
    .container{max-width:980px;margin:36px auto;padding:24px}
    header{display:flex;align-items:center;gap:16px}
    .sparkle{font-size:22px}
    h1{margin:0;font-size:40px;letter-spacing:1px}
    h2{margin:6px 0 18px;color:var(--accent);font-weight:600}
    .hero{background:linear-gradient(180deg,rgba(255,255,255,0.02),transparent);padding:22px;border-radius:16px;box-shadow:0 6px 30px rgba(2,6,23,0.6)}
    .dates{color:var(--muted);margin-bottom:14px}
    .btn{display:inline-block;padding:10px 16px;border-radius:10px;background:#111827;color:#fff;text-decoration:none;font-weight:600;box-shadow:0 6px 18px rgba(0,0,0,0.4)}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:14px;margin-top:18px}
    .card{background:rgba(255,255,255,0.03);padding:12px;border-radius:12px;border:1px solid rgba(255,255,255,0.03)}
    .card img{width:100%;height:160px;object-fit:cover;border-radius:8px}
    .section{margin-top:22px}
    .muted{color:var(--muted)}
    footer{margin-top:28px;color:var(--muted);font-size:14px}
    .contact a{display:inline-block;margin-right:8px;padding:8px 12px;border-radius:10px;background:rgba(255,255,255,0.02);text-decoration:none;color:#fff}
    .upload{display:inline-flex;align-items:center;gap:10px}
    @media (max-width:520px){h1{font-size:28px}}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="sparkle">✨</div>
      <div>
        <h1>Princess</h1>
        <h2>LeighAnne</h2>
      </div>
    </header><main class="hero">
  <p><strong>Celebrating 19 Years of Amazing</strong></p>
  <p class="dates">September 11, 2006 → September 11, 2025</p>
  <a class="btn" href="#gallery">View Photo Memories</a>

  <div class="section" id="gallery">
    <h3>Beautiful Memories</h3>
    <div class="grid">
      <!-- placeholder images; replace src with real pictures -->
      <div class="card"><img src="https://picsum.photos/seed/leigh1/800/600" alt="Birthday memory 1"><h4>Princess LeighAnne</h4><p class="muted">Add your beautiful birthday photos here!</p></div>
      <div class="card"><img src="https://picsum.photos/seed/leigh2/800/600" alt="Birthday memory 2"><h4>Special Moments</h4><p class="muted">Celebrating 19 amazing years!</p></div>
      <div class="card"><img src="https://picsum.photos/seed/leigh3/800/600" alt="Birthday memory 3"><h4>Princess Moments</h4><p class="muted">Every moment is special with you</p></div>
      <div class="card"><img src="https://picsum.photos/seed/leigh4/800/600" alt="Birthday memory 4"><h4>Princess Moments</h4><p class="muted">Every moment is special with you</p></div>
    </div>

    <p class="muted" style="margin-top:12px">Upload your favorite photos of Princess LeighAnne to create a personalized slideshow!</p>
    <form class="upload" onsubmit="event.preventDefault();alert('Upload feature is a placeholder in this demo. Replace with a server endpoint or storage provider.');">
      <input type="file" accept="image/*" />
      <button class="btn">Upload Photos</button>
    </form>
  </div>

  <div class="section">
    <h3>Our Journey Together</h3>
    <p class="muted"><strong>Achimota Beginnings</strong><br>Where it all started — from those early days at Achimota School when we were just getting to know each other. Little did we know this would blossom into such a beautiful friendship.</p>

    <h4>Growing Connection</h4>
    <p>Building trust & love — Princess, I never imagined writing birthday codes for you back then! But here we are — calling each other during tough times, celebrating together, proving what real friendship means.<br><em>~ With love, Afia</em></p>

    <h4>Unbreakable Bond</h4>
    <p>Forever friends — My fish! You're genuinely one of a kind.</p>
  </div>

  <div class="section">
    <h3>Send Birthday Wishes</h3>
    <p class="muted">Choose your preferred way to wish Princess LeighAnne a happy birthday!</p>
    <div class="contact">
      <a href="https://wa.me/233244680041" target="_blank" rel="noopener">WhatsApp Message</a>
      <a href="https://snapchat.com/add/Far_eeda11" target="_blank" rel="noopener">Snapchat</a>
      <a href="tel:+233244680041">Call / SMS</a>
    </div>
  </div>

  <div class="section">
    <h3>Why You're Amazing</h3>
    <p class="muted">Princess LeighAnne, your loving heart, genuine care, and the incredible person you've become inspires everyone around you. Your presence lights up every room you enter.</p>
    <div class="grid" style="margin-top:10px">
      <div class="card"><h4>Caring Heart</h4><p class="muted">Always there for friends</p></div>
      <div class="card"><h4>Bright Spirit</h4><p class="muted">Brings joy to everyone</p></div>
      <div class="card"><h4>True Princess</h4><p class="muted">Royal in every way</p></div>
    </div>
  </div>

  <footer>
    <h3>Happy 19th Birthday, Princess!</h3>
    <p class="muted">May this special day bring you endless joy, wonderful surprises, and all the happiness your heart can hold. ✨</p>
    <p class="muted">Made with ❤️ for Princess LeighAnne's 19th Birthday — Website created by Phenyl - 0537872807</p>
  </footer>

</main>

  </div>  <script>
    // small JS: simple lightbox for gallery images
    document.querySelectorAll('.card img').forEach(img => {
      img.style.cursor = 'pointer';
      img.addEventListener('click', ()=>{
        const overlay = document.createElement('div');
        overlay.style.position='fixed';overlay.style.left=0;overlay.style.top=0;overlay.style.width='100%';overlay.style.height='100%';overlay.style.background='rgba(0,0,0,0.8)';overlay.style.display='flex';overlay.style.alignItems='center';overlay.style.justifyContent='center';overlay.style.zIndex=9999
        const big = document.createElement('img');big.src=img.src;big.style.maxWidth='92%';big.style.maxHeight='92%';big.style.borderRadius='10px'
        overlay.appendChild(big);
        overlay.addEventListener('click', ()=>overlay.remove());
        document.body.appendChild(overlay);
      })
    })
  </script></body>
</html>
