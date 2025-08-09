<!doctype html>
<html lang="tr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Eylül Hüneş Cihangir – Portfolyo</title>
  <meta name="description" content="Eylül Hüneş Cihangir – Görsel İletişim Tasarımı öğrencisi portfolyo sitesi" />
  <style>
    :root{
      --bg:#0f1724;
      --muted:#6b7280;
      --accent:#4f46e5;
      --accent-2:#06b6d4;
      --glass: rgba(255,255,255,0.04);
      --radius:12px;
      --max-width:1100px;
      font-family: "Inter", system-ui, -apple-system, "Segoe UI", Roboto, Arial;
    }
    *{box-sizing:border-box;margin:0;padding:0}
    body{
      background:linear-gradient(180deg,#f8fafc, #eef2ff 60%);
      color:#071023;
      line-height:1.45;
      font-size:16px;
      -webkit-font-smoothing:antialiased;
    }
    .container{width: calc(100% - 2rem);max-width: var(--max-width);margin: 0 auto;}
    header{padding:1rem 0;display:flex;justify-content:space-between;align-items:center;}
    header h1{color:var(--accent);font-size:1.2rem}
    nav a{text-decoration:none;color:inherit;margin-left:1rem;padding:.4rem .6rem;border-radius:8px}
    nav a:hover{background:var(--glass)}
    section{padding:2.25rem 0;}
    .hero{display:grid;gap:1.5rem}
    .hero h2{font-size:clamp(1.6rem,4vw,2.4rem)}
    .lead{color:var(--muted);margin-top:.5rem}
    .btn{display:inline-block;margin-top:1rem;padding:.6rem .9rem;border-radius:8px;background:linear-gradient(90deg,var(--accent),var(--accent-2));color:white;text-decoration:none}
    .about{display:grid;gap:1.5rem;align-items:center}
    .about img{width:100%;max-width:300px;border-radius:12px;box-shadow:0 6px 18px rgba(0,0,0,0.08)}
    @media(min-width:800px){
      .hero{grid-template-columns:1fr 1fr}
      .about{grid-template-columns:300px 1fr}
    }
    footer{text-align:center;padding:1rem 0;color:var(--muted);font-size:.95rem}
  </style>
</head>
<body>
  <header class="container">
    <h1>Eylül Hüneş Cihangir</h1>
    <nav>
      <a href="#about">Hakkımda</a>
      <a href="#contact">İletişim</a>
    </nav>
  </header>

  <main class="container">
    <section class="hero">
      <div>
        <h2>Görsel İletişim Tasarımıyla Fikirleri Hayata Geçiriyorum</h2>
        <p class="lead">Üsküdar Üniversitesi Görsel İletişim Tasarımı öğrencisi olarak, estetik ve işlevselliği bir arada sunan projeler geliştiriyorum.</p>
        <a class="btn" href="#contact">Benimle Çalış</a>
      </div>
      <div>
        <img src="https://via.placeholder.com/500x300.png?text=Eyl%C3%BCl+H%C3%BCne%C5%9F+Cihangir" alt="Eylül Hüneş Cihangir portfolyo görseli">
      </div>
    </section>

    <section id="about" class="about">
      <img src="https://via.placeholder.com/300x400.png?text=Profil+Foto" alt="Eylül Hüneş Cihangir">
      <div>
        <h2>Hakkımda</h2>
        <p>Merhaba, ben <strong>Eylül Hüneş Cihangir</strong>. Üsküdar Üniversitesi Görsel İletişim Tasarımı bölümünde öğrenim görüyorum. Tasarımda estetik, işlevsellik ve duyguyu bir arada kullanarak insanlara ilham veren görsel deneyimler oluşturmayı seviyorum.</p>
        <p>Görsel iletişim alanında kendimi sürekli geliştiriyor, renk, tipografi ve kompozisyon konularında güçlü projeler üretmeyi hedefliyorum. Yeni teknolojiler ve yaratıcı fikirler ile harmanlanmış özgün tasarımlar yaratmak en büyük tutkum.</p>
      </div>
    </section>

    <section id="contact">
      <h2>İletişim</h2>
      <p>Bana ulaşmak için e-posta gönderebilirsiniz: <a href="mailto:ornek@mail.com">ornek@mail.com</a></p>
    </section>
  </main>

  <footer>
    © <span id="year"></span> Eylül Hüneş Cihangir. Tüm hakları saklıdır.
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>