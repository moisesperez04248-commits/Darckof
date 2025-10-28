[index.html](https://github.com/user-attachments/files/23194579/index.html)
<!doctype html>

<!-- Encabezado estilo neón para Barber Studio Darckof -->
<section style="background-color:#000; padding:80px 20px; text-align:center;">
  <h1 style="
    font-size:3.2em;
    font-weight:bold;
    text-transform:uppercase;
    font-family:'Arial Black', sans-serif;
    text-shadow:
      0 0 10px #fff,
      0 0 20px #fff,
      0 0 30px #ff0000,
      0 0 40px #0000ff,
      0 0 70px #0000ff,
      0 0 80px #ff0000;
    color:white;
    animation: neon-flash 2s infinite;
    margin-bottom:20px;
  ">
    Barber Studio Darckof
  </h1>

  <p style="
    color:#d4af37;
    font-size:1.4em;
    font-weight:500;
    letter-spacing:1px;
    text-shadow:0 0 10px #d4af37;
  ">
    Estilo, precisión y clase en cada corte 💈✨
  </p>
</section>

<!-- Animación del efecto neón -->
<style>
@keyframes neon-flash {
  0%, 100% {
    color: #fff;
    text-shadow:
      0 0 5px #fff,
      0 0 10px #fff,
      0 0 20px #ff0000,
      0 0 40px #0000ff,
      0 0 60px #0000ff;
  }
  50% {
    color: #ff0000;
    text-shadow:
      0 0 10px #ff0000,
      0 0 20px #0000ff,
      0 0 30px #fff,
      0 0 50px #ff0000,
      0 0 80px #0000ff;
  }
}
</style>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Barber Studio Darckof</title>
<style>
    :root{
      --bg:#0b0b0d; /* very dark */
      --card:#111214;
      --accent:#c59f22; /* gold-like */
      --muted:#9aa0a6;
      --white:#f5f5f5;
      --glass: rgba(255,255,255,0.03);
      font-family: Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    *{box-sizing:border-box}
    body{margin:0;background:linear-gradient(180deg,var(--bg),#070708);color:var(--white);}
    .container{max-width:1000px;margin:30px auto;padding:24px}
    header{display:flex;align-items:center;justify-content:space-between;gap:16px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:64px;height:64px;border-radius:12px;background:linear-gradient(135deg,#1b1b1c,#141314);display:flex;align-items:center;justify-content:center;border:2px solid rgba(255,255,255,0.03)}
    h1{margin:0;font-size:24px;letter-spacing:0.4px}
    .tagline{color:var(--muted);font-size:13px}
    nav{display:flex;gap:10px}
    .btn{background:var(--accent);color:#0b0b0d;padding:8px 12px;border-radius:8px;border:none;cursor:pointer;font-weight:600}
    .secondary{background:transparent;border:1px solid rgba(255,255,255,0.06);padding:8px 12px;border-radius:8px;color:var(--muted);cursor:pointer}
    main{display:grid;grid-template-columns:1fr 360px;gap:24px;margin-top:22px}
    .card{background:var(--card);padding:18px;border-radius:14px;box-shadow:0 6px 18px rgba(0,0,0,0.6);border:1px solid rgba(255,255,255,0.02)}
    .hero{padding:28px;border-radius:12px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));display:flex;gap:18px}
    .hero img{width:180px;height:180px;object-fit:cover;border-radius:8px}
    .services table{width:100%;border-collapse:collapse;margin-top:12px}
    .services th,.services td{padding:10px;text-align:left;border-bottom:1px dashed rgba(255,255,255,0.03)}
    .muted{color:var(--muted);font-size:13px}
    .gallery{display:grid;grid-template-columns:repeat(2,1fr);gap:8px}
    .gallery .photo{height:120px;background:var(--glass);border-radius:8px;display:flex;align-items:center;justify-content:center;color:var(--muted)}
    .contact .line{display:flex;justify-content:space-between;align-items:center;padding:8px 0;border-bottom:1px dashed rgba(255,255,255,0.03)}
    footer{margin-top:20px;color:var(--muted);font-size:13px;text-align:center}
    .lang-toggle{background:transparent;border:1px solid rgba(255,255,255,0.04);padding:6px 8px;border-radius:8px;color:var(--muted);cursor:pointer}
    /* responsive */
    @media (max-width:920px){main{grid-template-columns:1fr;}.hero img{width:120px;height:120px}}
  </style><style>
.redes {
  background-color: #000;
  color: gold;
  text-align: center;
  padding: 40px 15px;
  border-top: 2px solid gold;
  font-family: 'Poppins', sans-serif;
}

.redes h2 {
  margin-bottom: 20px;
  font-size: 22px;
  letter-spacing: 1.5px;
}

.botones-redes {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 15px;
}

.btn-red {
  display: flex;
  align-items: center;
  gap: 10px;
  background-color: transparent;
  border: 2px solid gold;
  border-radius: 30px;
  padding: 10px 20px;
  color: white;
  text-decoration: none;
  font-weight: 500;
  transition: 0.3s;
}

.btn-red img {
  width: 25px;
  height: 25px;
}

.btn-red:hover {
  background-color: gold;
  color: black;
  transform: scale(1.05);
  box-shadow: 0 0 10px gold;
}
</style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
               <div>
          <h1 id="brandName"></h1>
          <div class="tagline" id="tagline"></div>
        </div>
      </div>
      <nav>
        <button class="secondary lang-toggle" id="langBtn">EN</button>
        <button class="btn" id="bookBtn">Reservar cita</button>
      </nav>
    </header><main>
  <section>
    <div class="card hero">
      <img src="https://i.ibb.co/2JqmX8s/IMG-20250917-154755-715.webp" alt="Barber image">
      <div>
        <h2 id="heroTitle">Bienvenido a Barber Studio Darckof</h2>
        <p class="muted" id="heroDesc">Especialistas en cortes clásicos, afeitados y diseño de barba. Reserva tu cita y luce impecable.</p>
        <div style="margin-top:14px;display:flex;gap:10px">
          <a id="whatsappLink" class="btn" href="#">WhatsApp</a>
          <a class="secondary" href="#gallery">Ver galería</a>
        </div>
      </div>
    </div>

    <div class="card services" style="margin-top:18px">
      <h3 id="servicesTitle">Servicios</h3>
      <table>
        <thead>
          <tr><th>Servicio</th><th>Desde</th></tr>
        </thead>
        <tbody>
          <tr><td id="s1">Corte clásico o estudiantil</td><td id="p1">$35</td></tr>
          <tr><td id="s2">Afeitado medio</td><td id="p2">$35</td></tr>
          <tr><td id="s3">Afeitado bajo</td><td id="p3">$35</td></tr>
          <tr><td id="s4">Afeitado completo</td><td id="p4">$40</td></tr>
          <tr><td id="s5">Barbas completa y estilos</td><td id="p5">$35</td></tr>
          <tr><td id="s6">Peinados y trenzas craneales</td><td id="p6">Desde $40</td></tr>
        </tbody>
      </table>
      <p class="muted" style="margin-top:10px" id="priceNote">Precios mínimos. Pueden variar según el diseño solicitado.</p>
    </div>

    <div class="card" style="margin-top:18px">
      <h3 id="storeTitle">Tienda Online</h3>
      <p class="muted" id="storeNote">Próximamente: productos para el cuidado del cabello y la barba.</p>
    </div>

    <div class="card" id="gallery" style="margin-top:18px">
      <h3 id="galleryTitle">Galería</h3>
      <div class="gallery">
      <section id="galeria" style="background-color:#000; color:white; padding:50px 20px; text-align:center;">
  <h2 style="color:#d4af37; font-size:2em; margin-bottom:20px;">💈 Barber Studio Darckof 💈</h2>
  <p style="color:#ccc; font-size:1.1em; margin-bottom:40px;">
    Estilo, precisión y calidad en cada corte. ¡Descubre algunos de nuestros mejores trabajos!
  </p>

  <div style="display:grid; grid-template-columns:repeat(3, minmax(250px, 1fr)); gap:20px;">
    <img src="https://i.ibb.co/GfWCn5PR/20251011-144648.jpg" alt="Corte 1" style="width:100%; border-radius:12px; transition:0.3s; cursor:pointer;" onmouseover="this.style.transform='scale(1.05)';" onmouseout="this.style.transform='scale(1)';">
    <img src="https://i.ibb.co/V00df5y1/20251011-144641.jpg" alt="Corte 2" style="width:100%; border-radius:12px; transition:0.3s; cursor:pointer;" onmouseover="this.style.transform='scale(1.05)';" onmouseout="this.style.transform='scale(1)';">
    <img src="https://i.ibb.co/XxpRD9fv/20251010-170610.jpg" alt="Corte 3" style="width:100%; border-radius:12px; transition:0.3s; cursor:pointer;" onmouseover="this.style.transform='scale(1.05)';" onmouseout="this.style.transform='scale(1)';">
    <img src="https://i.ibb.co/whDL43bB/20251010-170559.jpg" alt="Corte 4" style="width:100%; border-radius:12px; transition:0.3s; cursor:pointer;" onmouseover="this.style.transform='scale(1.05)';" onmouseout="this.style.transform='scale(1)';">
    <img src="https://i.ibb.co/tMhT8NQg/20251009-201624.jpg" alt="Corte 5" style="width:100%; border-radius:12px; transition:0.3s; cursor:pointer;" onmouseover="this.style.transform='scale(1.05)';" onmouseout="this.style.transform='scale(1)';">
    <img src="https://i.ibb.co/pvhs4txs/20251007-172535.jpg" alt="Corte 6" style="width:100%; border-radius:12px; transition:0.3s; cursor:pointer;" onmouseover="this.style.transform='scale(1.05)';" onmouseout="this.style.transform='scale(1)';">
    <img src="https://i.ibb.co/SDvNVW75/20251006-173021.jpg" alt="Corte 7" style="width:100%; border-radius:12px; transition:0.3s; cursor:pointer;" onmouseover="this.style.transform='scale(1.05)';" onmouseout="this.style.transform='scale(1)';">
    <img src="https://i.ibb.co/pBCk4ZVH/20251006-164609.jpg" alt="Corte 8" style="width:100%; border-radius:12px; transition:0.3s; cursor:pointer;" onmouseover="this.style.transform='scale(1.05)';" onmouseout="this.style.transform='scale(1)';">
    <img src="https://i.ibb.co/27LwKMdh/20251005-195647.jpg" alt="Corte 9" style="width:100%; border-radius:12px; transition:0.3s; cursor:pointer;" onmouseover="this.style.transform='scale(1.05)';" onmouseout="this.style.transform='scale(1)';">
    <img src="https://i.ibb.co/fzNnrgHB/20250921-145939.jpg" alt="Corte 10" style="width:100%; border-radius:12px; transition:0.3s; cursor:pointer;" onmouseover="this.style.transform='scale(1.05)';" onmouseout="this.style.transform='scale(1)';">
    <img src="https://i.ibb.co/xKy00j3q/20250919-165236.jpg" alt="Corte 11" style="width:100%; border-radius:12px; transition:0.3s; cursor:pointer;" onmouseover="this.style.transform='scale(1.05)';" onmouseout="this.style.transform='scale(1)';">
    <img src="https://i.ibb.co/F49dNT3d/20250917-200712.jpg" alt="Corte 12" style="width:100%; border-radius:12px; transition:0.3s; cursor:pointer;" onmouseover="this.style.transform='scale(1.05)';" onmouseout="this.style.transform='scale(1)';">
    <img src="https://i.ibb.co/LDq8ByDJ/20250906-142954.jpg" alt="Corte 13" style="width:100%; border-radius:12px; transition:0.3s; cursor:pointer;" onmouseover="this.style.transform='scale(1.05)';" onmouseout="this.style.transform='scale(1)';">
    <img src="https://i.ibb.co/gLzVdNt6/20250816-190650.jpg" alt="Corte 14" style="width:100%; border-radius:12px; transition:0.3s; cursor:pointer;" onmouseover="this.style.transform='scale(1.05)';" onmouseout="this.style.transform='scale(1)';">
    <img src="https://i.ibb.co/Ndc9gQk4/20250816-171326.jpg" alt="Corte 15" style="width:100%; border-radius:12px; transition:0.3s; cursor:pointer;" onmouseover="this.style.transform='scale(1.05)';" onmouseout="this.style.transform='scale(1)';">
  </div>
</section>
    </div>

</section>

  <aside>
    <div class="card contact">
      <h3 id="contactTitle">Contacto</h3>
      <div class="line"><div><strong id="addressTitle">Ubicación</strong><div class="muted" id="address">Houston, TX</div></div></div>
      <div class="line"><div><strong id="whatsappTitle">WhatsApp</strong><div class="muted" id="whatsappNumber">[+1 281 995 0659  
]</div></div></div>
      <div class="line"><div><strong id="instagramTitle">Instagram</strong><div class="muted" id="instagram">@barberstudiodarckof</div></div></div>
      <div class="line"><div><strong id="hoursTitle">Horario</strong><div class="muted" id="hours">Lun-Sab 10:00 - 20:00 / Dom con cita</div></div></div>
      <div style="margin-top:12px;display:flex;gap:10px">
        <button class="btn" id="reserveSmall">Reservar</button>
        <button class="secondary" id="mapBtn">Ver mapa</button>
      </div>
    </div>

    <div class="card" style="margin-top:18px">
      <h4 id="aboutTitle">Sobre nosotros</h4>
      <p class="muted" id="aboutText">Barber Studio Darckof ofrece diseños y cortes personalizados con atención al detalle. Todos los estilos: clásicos, modernos y urbanos.</p>
    </div>

  </aside>
</main>

<footer>
  <div class="muted">© <span id="year"></span> Barber Studio Darckof — Todos los derechos reservados</div>
</footer>

  </div>  <script>
    // basic language toggle (es/en)
    const langBtn = document.getElementById('langBtn');
    const yearSpan = document.getElementById('year');
    yearSpan.textContent = new Date().getFullYear();

    const translations = {
      en:{ 
</style>
        heroTitle:'Welcome to Barber Studio Darckof',
        heroDesc:'Specialists in classic cuts, shaves and beard design. Book your appointment and look sharp.',
        servicesTitle:'Services',
        s1:'Classic / Student Haircut', p1:'$35',
        s2:'Medium Shave', p2:'$35',
        s3:'Low Shave', p3:'$35',
        s4:'Full Shave', p4:'$40',
        s5:'Full Beard & Styling', p5:'$35',
        s6:'Braids & Hairstyles', p6:'From $40',
        priceNote:'Prices are minimums and may vary depending on the requested design.',
        storeTitle:'Online Store', storeNote:'Coming soon: hair & beard care products.',
        galleryTitle:'Gallery',
        contactTitle:'Contact', addressTitle:'Location', address:'Houston, TX',
        whatsappTitle:'WhatsApp', whatsappNumber:'+1 281-995-0659',
        instagramTitle:'Instagram', instagram:'@barberstudiodarckof',
        hoursTitle:'Hours', hours:'Mon-Sat 10:00 - 20:00 / Sun by appointment',
        aboutTitle:'About us', aboutText:'Barber Studio Darckof offers personalized designs and cuts with attention to detail. All styles: classic, modern and urban.'
      },
      es:{
        brandName:'Barber Studio Darckof',
        tagline:'Tu estilo, tu presencia, tu marca.',
        heroTitle:'Bienvenido a Barber Studio Darckof',
        heroDesc:'Especialistas en cortes clásicos, afeitados y diseño de barba. Reserva tu cita y luce impecable.',
        servicesTitle:'Servicios',
        s1:'Corte clásico o estudiantil', p1:'$35',
        s2:'Afeitado medio', p2:'$35',
        s3:'Afeitado bajo', p3:'$35',
        s4:'Afeitado completo', p4:'$40',
        s5:'Barbas completa y estilos', p5:'$35',
        s6:'Peinados y trenzas craneales', p6:'Desde $40',
        priceNote:'Precios mínimos. Pueden variar según el diseño solicitado.',
        storeTitle:'Tienda Online', storeNote:'Próximamente: productos para el cuidado del cabello y la barba.',
        galleryTitle:'Galería',
        contactTitle:'Contacto', addressTitle:'Ubicación', address:'Houston, TX',
        whatsappTitle:'WhatsApp', whatsappNumber:'+1 281-995-0659',
        instagramTitle:'Instagram', instagram:'@barberstudiodarckof',
        hoursTitle:'Horario', hours:'Lun-Sab 10:00 - 20:00 / Dom con cita',
        aboutTitle:'Sobre nosotros', aboutText:'Barber Studio Darckof ofrece diseños y cortes personalizados con atención al detalle. Todos los estilos: clásicos, modernos y urbanos.'
      }
    };

    let current = 'es';
    function apply(lang){
      const t = translations[lang];
      if(!t) return;
      document.getElementById('brandName').textContent = t.brandName;
      document.getElementById('tagline').textContent = t.tagline;
      document.getElementById('heroTitle').textContent = t.heroTitle;
      document.getElementById('heroDesc').textContent = t.heroDesc;
      document.getElementById('servicesTitle').textContent = t.servicesTitle;
      document.getElementById('s1').textContent = t.s1; document.getElementById('p1').textContent = t.p1;
      document.getElementById('s2').textContent = t.s2; document.getElementById('p2').textContent = t.p2;
      document.getElementById('s3').textContent = t.s3; document.getElementById('p3').textContent = t.p3;
      document.getElementById('s4').textContent = t.s4; document.getElementById('p4').textContent = t.p4;
      document.getElementById('s5').textContent = t.s5; document.getElementById('p5').textContent = t.p5;
      document.getElementById('s6').textContent = t.s6; document.getElementById('p6').textContent = t.p6;
      document.getElementById('priceNote').textContent = t.priceNote;
      document.getElementById('storeTitle').textContent = t.storeTitle;
      document.getElementById('storeNote').textContent = t.storeNote;
      document.getElementById('galleryTitle').textContent = t.galleryTitle;
      document.getElementById('contactTitle').textContent = t.contactTitle;
      document.getElementById('addressTitle').textContent = t.addressTitle;
      document.getElementById('address').textContent = t.address;
      document.getElementById('whatsappTitle').textContent = t.whatsappTitle;
      document.getElementById('whatsappNumber').textContent = t.whatsappNumber;
      document.getElementById('instagramTitle').textContent = t.instagramTitle;
      document.getElementById('instagram').textContent = t.instagram;
      document.getElementById('hoursTitle').textContent = t.hoursTitle;
      document.getElementById('hours').textContent = t.hours;
      document.getElementById('aboutTitle').textContent = t.aboutTitle;
      document.getElementById('aboutText').textContent = t.aboutText;
      document.getElementById('storeTitle').textContent = t.storeTitle;
      // update lang button text
      langBtn.textContent = lang === 'es' ? 'EN' : 'ES';
      current = lang;
    }

    langBtn.addEventListener('click', ()=>{
      apply(current === 'es' ? 'en' : 'es');
    });

    // reserve button behaviour: open whatsapp if number provided (replace with your number)
    const whatsappLink = document.getElementById('whatsappLink');
    const reserveSmall = document.getElementById('reserveSmall');
    const bookBtn = document.getElementById('bookBtn');

    function setWhatsAppNumber(num){
      const clean = (num || '').replace(/\D/g,'');
      if(!clean) {
        whatsappLink.href = '#';
        whatsappLink.onclick = (e)=>{e.preventDefault(); alert('Por favor agrega tu número de WhatsApp en el archivo HTML.');}
        reserveSmall.onclick = bookBtn.onclick = ()=>{alert('Por favor agrega tu número de WhatsApp en el archivo HTML.');}
        document.getElementById('whatsappNumber').textContent = num || '[Agrega tu número]';
      } else {
        whatsappLink.href = 'https://wa.me/' + clean;
        reserveSmall.onclick = bookBtn.onclick = ()=>{ window.open('https://wa.me/' + clean, '_blank'); }
        document.getElementById('whatsappNumber').textContent = num;
      }
    }

    // set initial (user should edit the HTML to add their actual number)
    setWhatsAppNumber('https://wa.me/+1 281-995-0659?text=Hola%20quiero%20agendar%20un%20corte');

    // initial apply
    apply('es');
  </script></body><footer class="redes">
  <h2>Síguenos en redes</h2>
  <div class="botones-redes">
    <a href="https://www.instagram.com/Studio_Darckof" target="_blank" class="btn-red instagram">
      <img src="https://cdn-icons-png.flaticon.com/512/2111/2111463.png" alt="Instagram" />
      Instagram
    </a>

    <a href="https://www.facebook.com/share/1A79J2F3ym/" target="_blank" class="btn-red facebook">
      <img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook" />
      Facebook
    </a>

    <a href="https://www.tiktok.com/@darckofstudio?_t=ZP-90piaUugirf&_r=1" target="_blank" class="btn-red tiktok">
      <img src="https://cdn-icons-png.flaticon.com/512/3046/3046121.png" alt="TikTok" />
      TikTok
    </a>

    <a href="https://www.youtube.com/@darckof" target="_blank" class="btn-red youtube">
      <img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" alt="YouTube" />
      YouTube
    </a>
  </div>
</footer>
</html>
