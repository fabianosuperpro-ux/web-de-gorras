# web-de-gorras
index.html
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Vista previa — Gorras personalizadas</title>
</head>
<body>

<section class="caps-store">

  <!-- CABECERA -->
  <header class="caps-header">

    <div class="brand-band">
      <div class="brand-band-bg" style="background-image: url('https://images.unsplash.com/photo-1521369909029-2afed882baee?w=1600');"></div>
      <h1 class="brand-band-title">Studio Caps</h1>
      <p class="brand-band-slogan">Custom caps. Your style.</p>
    </div>

    <div class="caps-subheader">
      <nav class="caps-navigation">
        <a href="#caps">Gorras</a>
        <a href="#custom">Personalizadas</a>
        <a href="#about">Nosotros</a>
      </nav>
    </div>

  </header>

  <a class="floating-cart" href="#" aria-label="Carrito">
    🛒
    <span class="cart-count">2</span>
  </a>


  <!-- BANDA DE RESEÑAS -->
  <div class="reviews-marquee">
    <div class="marquee-track">
      <div class="marquee-content">
        <span class="marquee-item"><span class="marquee-stars">★★★★★</span>“La mejor gorra que he comprado, acabado perfecto” — <strong>Laura M.</strong></span>
        <span class="marquee-item"><span class="marquee-stars">★★★★★</span>“Personalización exacta a lo que pedí” — <strong>Diego R.</strong></span>
        <span class="marquee-item"><span class="marquee-stars">★★★★☆</span>“Envío rápido y calidad top” — <strong>Ana P.</strong></span>
      </div>
      <div class="marquee-content" aria-hidden="true">
        <span class="marquee-item"><span class="marquee-stars">★★★★★</span>“La mejor gorra que he comprado, acabado perfecto” — <strong>Laura M.</strong></span>
        <span class="marquee-item"><span class="marquee-stars">★★★★★</span>“Personalización exacta a lo que pedí” — <strong>Diego R.</strong></span>
        <span class="marquee-item"><span class="marquee-stars">★★★★☆</span>“Envío rápido y calidad top” — <strong>Ana P.</strong></span>
      </div>
    </div>
  </div>


  <!-- HERO -->
  <div class="caps-hero">
    <div class="hero-content">
      <p class="small-title">GORRAS PERSONALIZADAS</p>
      <h2>Diseñadas para<br>destacar.</h2>
      <p>Gorras seleccionadas y personalizadas a tu estilo. Diseños exclusivos, acabados cuidados y unidades limitadas.</p>
      <div class="hero-buttons">
        <a href="#caps" class="button button-dark">VER GORRAS</a>
        <a href="#custom" class="button button-light">CREA LA TUYA</a>
      </div>
    </div>
  </div>


  <!-- PRODUCTOS -->
  <div id="caps" class="products-section">
    <div class="section-heading">
      <p>COLECCIÓN</p>
      <h2>Nuestras gorras</h2>
    </div>

    <div class="product-grid">
      <article class="product-card">
        <a href="#" class="product-image"><img src="https://images.unsplash.com/photo-1521369909029-2afed882baee?w=800" alt="Gorra negra"></a>
        <div class="product-information">
          <div><h3><a href="#">Gorra Classic Negra</a></h3><p class="product-price">$25.00</p></div>
          <a href="#" class="product-button">VER</a>
        </div>
      </article>

      <article class="product-card">
        <a href="#" class="product-image"><img src="https://images.unsplash.com/photo-1588850561407-ed78c282e89b?w=800" alt="Gorra beige"></a>
        <div class="product-information">
          <div><h3><a href="#">Gorra Beige Bordada</a></h3><p class="product-price">$28.00</p></div>
          <a href="#" class="product-button">VER</a>
        </div>
      </article>

      <article class="product-card">
        <a href="#" class="product-image"><img src="https://images.unsplash.com/photo-1620231150904-a86add983b12?w=800" alt="Gorra verde"></a>
        <div class="product-information">
          <div><h3><a href="#">Gorra Verde Militar</a></h3><p class="product-price">$27.00</p></div>
          <a href="#" class="product-button">VER</a>
        </div>
      </article>

      <article class="product-card">
        <a href="#" class="product-image"><img src="https://images.unsplash.com/photo-1556306535-0f09a537f0a3?w=800" alt="Gorra blanca"></a>
        <div class="product-information">
          <div><h3><a href="#">Gorra Blanca Minimal</a></h3><p class="product-price">$25.00</p></div>
          <a href="#" class="product-button">VER</a>
        </div>
      </article>
    </div>
  </div>


  <!-- PERSONALIZADA -->
  <section id="custom" class="custom-section">
    <div class="custom-content">
      <p class="small-title">PERSONALIZACIÓN</p>
      <h2>Crea una gorra<br>completamente tuya.</h2>
      <p>Elige el modelo, el color y la personalización. Puedes enviarnos tu propio diseño y crear una pieza única.</p>
      <a href="#" class="button button-dark">PERSONALIZAR GORRA</a>
    </div>
    <div class="custom-image">
      <img src="https://images.unsplash.com/photo-1521369909029-2afed882baee?w=1000" alt="Gorra personalizada">
    </div>
  </section>


  <!-- NOSOTROS -->
  <section id="about" class="about-section">
    <p class="small-title">NUESTRA MARCA</p>
    <h2>Hechas para llevar<br>tu estilo.</h2>
    <p>Cada gorra se personaliza cuidadosamente para conseguir un acabado diferente y duradero.</p>
  </section>

</section>


<style>

@import url('https://fonts.googleapis.com/css2?family=Yellowtail&display=swap');

* { box-sizing: border-box; }

body { margin: 0; }

.caps-store {
  --black: #111111;
  --beige: #d8c7aa;
  --cream: #f4efe6;
  --white: #ffffff;

  position: relative;

  background: var(--cream);
  color: var(--black);
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
  padding: 0;
}

.caps-header {
  background: var(--beige);
  border-bottom: 1px solid rgba(17,17,17,.12);
}

.brand-band {
  position: relative;
  overflow: hidden;
  padding: 34px 5% 30px;
  text-align: center;
  background: var(--black);
}

.brand-band-bg {
  position: absolute;
  inset: 0;
  background-size: cover;
  background-position: center;
  opacity: .28;
  filter: grayscale(1);
}

.brand-band-title {
  position: relative;
  z-index: 1;
  margin: 0;
  font-family: 'Yellowtail', cursive;
  font-size: 44px;
  font-weight: 400;
  letter-spacing: .5px;
  color: var(--white);
}

.brand-band-slogan {
  position: relative;
  z-index: 1;
  margin: 4px 0 0;
  font-size: 11px;
  letter-spacing: 1.5px;
  text-transform: uppercase;
  color: var(--beige);
}

.caps-subheader {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 12px 5%;
}

.caps-navigation { display: flex; align-items: center; gap: 28px; }
.caps-navigation a { color: var(--black); text-decoration: none; font-size: 13px; font-weight: 600; text-transform: uppercase; letter-spacing: .8px; }

.floating-cart {
  position: fixed;
  top: 18px;
  right: 18px;
  z-index: 999;
  width: 50px;
  height: 50px;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 50%;
  background: var(--black);
  font-size: 22px;
  text-decoration: none;
  box-shadow: 0 4px 14px rgba(17,17,17,.25);
}

.cart-count {
  position: absolute;
  top: -4px;
  right: -4px;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 20px;
  height: 20px;
  border-radius: 50%;
  background: var(--beige);
  color: var(--black);
  font-size: 10px;
  font-weight: 700;
}

.reviews-marquee { overflow: hidden; background: var(--black); color: var(--white); padding: 12px 0; }
.marquee-track { display: flex; width: max-content; animation: marquee-scroll 28s linear infinite; }
.marquee-content { display: flex; gap: 50px; padding-right: 50px; white-space: nowrap; }
.marquee-item { font-size: 13px; letter-spacing: .3px; }
.marquee-stars { color: var(--beige); margin-right: 6px; letter-spacing: 1px; }
@keyframes marquee-scroll { from { transform: translateX(0); } to { transform: translateX(-50%); } }

.caps-hero { min-height: 600px; display: flex; align-items: center; padding: 80px 8%; background: linear-gradient(90deg, rgba(17,17,17,.96), rgba(17,17,17,.72)); color: var(--white); }
.hero-content { max-width: 620px; }
.small-title { margin: 0 0 18px; font-size: 11px; font-weight: 700; letter-spacing: 2px; text-transform: uppercase; }
.hero-content h2, .custom-content h2, .about-section h2 { margin: 0 0 25px; font-size: clamp(42px, 6vw, 82px); line-height: .95; letter-spacing: -3px; }
.hero-content > p:not(.small-title) { max-width: 500px; font-size: 17px; line-height: 1.6; opacity: .88; }
.hero-buttons { display: flex; gap: 12px; margin-top: 35px; }
.button { display: inline-flex; align-items: center; justify-content: center; min-height: 48px; padding: 0 25px; text-decoration: none; font-size: 12px; font-weight: 700; letter-spacing: 1px; text-transform: uppercase; transition: .2s ease; }
.button-dark { background: var(--black); color: var(--white); }
.button-light { background: var(--beige); color: var(--black); }
.button:hover { transform: translateY(-2px); }

.products-section { padding: 90px 5%; }
.section-heading { margin-bottom: 40px; }
.section-heading p { margin: 0 0 8px; font-size: 11px; letter-spacing: 2px; font-weight: 700; }
.section-heading h2 { margin: 0; font-size: 44px; letter-spacing: -1.5px; }
.product-grid { display: grid; grid-template-columns: repeat(4, minmax(0, 1fr)); gap: 25px; }
.product-card { background: var(--white); }
.product-image { display: block; aspect-ratio: 1 / 1; overflow: hidden; background: #e9e1d5; }
.product-image img { width: 100%; height: 100%; object-fit: cover; transition: transform .4s ease; }
.product-card:hover .product-image img { transform: scale(1.04); }
.product-information { padding: 18px; display: flex; justify-content: space-between; align-items: flex-end; gap: 15px; }
.product-information h3 { margin: 0 0 7px; font-size: 14px; text-transform: uppercase; }
.product-information h3 a { color: var(--black); text-decoration: none; }
.product-price { margin: 0; font-size: 14px; }
.product-button { padding: 8px 12px; background: var(--black); color: var(--white); text-decoration: none; font-size: 10px; font-weight: 700; letter-spacing: 1px; }

.custom-section { display: grid; grid-template-columns: 1fr 1fr; background: var(--beige); }
.custom-content { padding: 90px 10%; display: flex; flex-direction: column; justify-content: center; align-items: flex-start; }
.custom-content h2 { font-size: clamp(40px, 5vw, 65px); }
.custom-content > p:not(.small-title) { max-width: 500px; line-height: 1.6; margin-bottom: 30px; }
.custom-image { min-height: 500px; overflow: hidden; background: #c8b79c; }
.custom-image img { width: 100%; height: 100%; object-fit: cover; }

.about-section { padding: 110px 10%; text-align: center; background: var(--black); color: var(--white); }
.about-section h2 { font-size: clamp(42px, 6vw, 75px); }
.about-section > p:last-child { max-width: 600px; margin: 0 auto; line-height: 1.7; opacity: .8; }

@media screen and (max-width: 800px) {
  .brand-band { padding: 26px 6% 22px; }
  .brand-band-title { font-size: 34px; }
  .caps-subheader { padding: 12px 5%; }
  .caps-navigation { width: 100%; overflow-x: auto; gap: 18px; padding-bottom: 4px; justify-content: center; }
  .caps-navigation a { white-space: nowrap; }
  .caps-hero { min-height: 540px; padding: 60px 7%; }
  .hero-content h2 { font-size: 50px; letter-spacing: -2px; }
  .hero-buttons { flex-direction: column; align-items: stretch; }
  .button { width: 100%; }
  .products-section { padding: 65px 5%; }
  .product-grid { grid-template-columns: repeat(2, minmax(0, 1fr)); gap: 12px; }
  .product-information { padding: 12px; display: block; }
  .product-button { display: inline-block; margin-top: 10px; }
  .custom-section { grid-template-columns: 1fr; }
  .custom-content { padding: 65px 7%; }
  .custom-image { min-height: 350px; }
  .about-section { padding: 75px 7%; }
}

</style>

</body>
</html>