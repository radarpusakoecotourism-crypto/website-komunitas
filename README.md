[radar_pusako_ecotourism.html](https://github.com/user-attachments/files/32813861/radar_pusako_ecotourism.html)
# website-komunitas
web
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Radar Pusako Ecotourism</title>
<meta name="description" content="Radar Pusako Ecotourism - pengembangan pariwisata berbasis alam, budaya dan sejarah di Sumatera Barat.">
<style>
:root{
  --green:#1f4d3a; --green2:#2f6b4f; --cream:#f5f0e5; --sand:#d9c7a2;
  --dark:#183127; --white:#fff; --muted:#68766f;
}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{font-family:Arial,Helvetica,sans-serif;color:var(--dark);background:#fbfaf6;line-height:1.6}
nav{position:fixed;top:0;left:0;right:0;z-index:10;background:rgba(24,49,39,.95);color:white;padding:15px 6%;display:flex;align-items:center;justify-content:space-between}
.logo{font-weight:800;letter-spacing:1px}
.logo span{display:block;font-size:11px;font-weight:400;letter-spacing:2px;color:#d9c7a2}
nav a{color:#fff;text-decoration:none;margin-left:22px;font-size:14px}
.hero{min-height:100vh;padding:150px 7% 80px;display:flex;align-items:center;background:linear-gradient(90deg,rgba(20,45,35,.9),rgba(20,45,35,.45)),url('https://images.unsplash.com/photo-1511497584788-876760111969?auto=format&fit=crop&w=1800&q=85') center/cover;color:white}
.hero-inner{max-width:720px}
.badge{display:inline-block;border:1px solid rgba(255,255,255,.5);padding:8px 14px;border-radius:30px;margin-bottom:20px;font-size:13px}
h1{font-size:clamp(42px,7vw,78px);line-height:1.02;margin-bottom:20px}
.hero p{font-size:19px;max-width:650px;color:#edf2ee}
.btn{display:inline-block;margin-top:28px;padding:13px 22px;border-radius:8px;background:#d9c7a2;color:#183127;text-decoration:none;font-weight:700;margin-right:10px}
.btn.alt{background:transparent;color:white;border:1px solid rgba(255,255,255,.6)}
section{padding:85px 7%}
.section-head{max-width:720px;margin-bottom:38px}
.kicker{color:var(--green2);font-size:13px;text-transform:uppercase;letter-spacing:2px;font-weight:800;margin-bottom:8px}
h2{font-size:38px;line-height:1.15;margin-bottom:12px}
.section-head p{color:var(--muted)}
.about{display:grid;grid-template-columns:1fr 1fr;gap:55px;align-items:center}
.about-img{height:430px;border-radius:18px;background:url('https://images.unsplash.com/photo-1500534623283-312aade485b7?auto=format&fit=crop&w=1200&q=85') center/cover}
.points{display:grid;grid-template-columns:1fr 1fr;gap:15px;margin-top:25px}
.point{background:var(--cream);padding:18px;border-radius:12px}
.point b{display:block;margin-bottom:4px}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:20px}
.card{background:white;border:1px solid #e8e4da;border-radius:15px;overflow:hidden;box-shadow:0 7px 24px rgba(25,45,35,.05)}
.card-img{height:180px;background-position:center;background-size:cover}
.card-body{padding:22px}
.card h3{margin-bottom:8px}
.card p{color:var(--muted);font-size:14px}
.program .card{padding:25px;min-height:210px}
.icon{font-size:32px;margin-bottom:12px}
.destination .card-img{height:220px}
.tag{display:inline-block;background:#edf3ee;color:var(--green);font-size:11px;padding:5px 9px;border-radius:20px;margin-top:12px}
.band{background:var(--green);color:white}
.band .section-head p{color:#dbe6df}
.article{background:var(--cream)}
.gallery{display:grid;grid-template-columns:2fr 1fr 1fr;grid-auto-rows:190px;gap:12px}
.gallery div{background-size:cover;background-position:center;border-radius:12px}
.gallery .big{grid-row:span 2}
.contact{background:linear-gradient(135deg,#173c2d,#2f6b4f);color:white;text-align:center}
.contact p{max-width:650px;margin:0 auto;color:#dce8e1}
footer{background:#12271f;color:#cbd7d1;text-align:center;padding:28px 7%;font-size:13px}
@media(max-width:800px){
 nav{padding:14px 5%} nav .links{display:none}
 section{padding:65px 6%}
 .about,.grid{grid-template-columns:1fr}
 .about-img{height:300px}
 .points{grid-template-columns:1fr}
 .gallery{grid-template-columns:1fr 1fr;grid-auto-rows:160px}
 .gallery .big{grid-row:span 1}
 h2{font-size:32px}
}
</style>
</head>
<body>
<nav>
  <div class="logo">RP ECOTOURISM<span>RADAR PUSAKO</span></div>
  <div class="links">
    <a href="#tentang">Tentang</a><a href="#program">Program</a><a href="#destinasi">Destinasi</a><a href="#galeri">Galeri</a><a href="#artikel">Artikel</a><a href="#kontak">Kontak</a>
  </div>
</nav>

<header class="hero">
 <div class="hero-inner">
   <div class="badge">SUMATERA BARAT • INDONESIA</div>
   <h1>Radar Pusako<br>Ecotourism</h1>
   <p>Menjaga Alam • Merawat Budaya • Mengembangkan Ekowisata</p>
   <p style="margin-top:10px">Mengembangkan potensi wisata berbasis alam, budaya dan sejarah melalui riset, pendampingan, konservasi dan wisata minat khusus.</p>
   <a class="btn" href="#destinasi">Jelajahi Destinasi</a>
   <a class="btn alt" href="#tentang">Kenali Kami</a>
 </div>
</header>

<section id="tentang">
 <div class="about">
  <div class="about-img"></div>
  <div>
   <div class="kicker">Tentang Kami</div>
   <h2>Membangun ekowisata bersama masyarakat</h2>
   <p>Radar Pusako Ecotourism merupakan komunitas yang bergerak dalam pengembangan pariwisata berbasis alam, budaya dan sejarah di Sumatera Barat.</p>
   <p style="margin-top:14px">Kami mendorong destinasi yang menjaga lingkungan, mengangkat kearifan lokal dan membuka ruang bagi masyarakat untuk menjadi bagian utama dari pengembangan pariwisata.</p>
   <div class="points">
    <div class="point"><b>Visi</b>Ekowisata berkelanjutan berbasis potensi lokal.</div>
    <div class="point"><b>Wilayah</b>Sumatera Barat dengan basis Kota Pariaman.</div>
    <div class="point"><b>Fokus</b>Alam, budaya, sejarah dan masyarakat.</div>
    <div class="point"><b>Pendekatan</b>Riset, pendampingan dan kolaborasi.</div>
   </div>
  </div>
 </div>
</section>

<section id="program" class="program band">
 <div class="section-head"><div class="kicker" style="color:#d9c7a2">Program Kami</div><h2>Ekowisata yang tumbuh dari potensi lokal</h2><p>Program dirancang untuk menghubungkan riset, masyarakat, konservasi dan pengalaman wisata.</p></div>
 <div class="grid">
  <div class="card"><div class="icon">🌳</div><h3>Pengembangan Ekowisata</h3><p>Pendampingan pengembangan destinasi berbasis alam dan masyarakat.</p></div>
  <div class="card"><div class="icon">🔎</div><h3>Riset & Studi Potensi</h3><p>Identifikasi potensi alam, budaya, sejarah dan daya tarik wisata.</p></div>
  <div class="card"><div class="icon">🥾</div><h3>Wisata Minat Khusus</h3><p>Trekking, camping, river exploration dan pengalaman alam.</p></div>
  <div class="card"><div class="icon">🏘️</div><h3>Pemberdayaan Masyarakat</h3><p>Mendorong masyarakat lokal menjadi pelaku utama pariwisata.</p></div>
  <div class="card"><div class="icon">🌱</div><h3>Konservasi Alam</h3><p>Mendorong kegiatan wisata yang memperhatikan kelestarian lingkungan.</p></div>
  <div class="card"><div class="icon">🏛️</div><h3>Budaya & Sejarah</h3><p>Mengangkat tradisi, sejarah dan kearifan lokal sebagai daya tarik.</p></div>
 </div>
</section>

<section id="destinasi" class="destination">
 <div class="section-head"><div class="kicker">Destinasi</div><h2>Menemukan potensi ekowisata Sumatera Barat</h2><p>Halaman destinasi dapat dikembangkan menjadi database potensi wisata dan dokumentasi lapangan.</p></div>
 <div class="grid">
  <div class="card"><div class="card-img" style="background-image:url('https://images.unsplash.com/photo-1433086966358-54859d0ed716?auto=format&fit=crop&w=1000&q=85')"></div><div class="card-body"><h3>Lubuk Nango Ecotourism</h3><p>V Koto Timur, Padang Pariaman.</p><span class="tag">Studi Potensi</span></div></div>
  <div class="card"><div class="card-img" style="background-image:url('https://images.unsplash.com/photo-1448375240586-882707db888b?auto=format&fit=crop&w=1000&q=85')"></div><div class="card-body"><h3>Destinasi Alam</h3><p>Ruang untuk dokumentasi destinasi potensial lainnya.</p><span class="tag">Eksplorasi</span></div></div>
  <div class="card"><div class="card-img" style="background-image:url('https://images.unsplash.com/photo-1473445361085-b9a07f55608b?auto=format&fit=crop&w=1000&q=85')"></div><div class="card-body"><h3>Wisata Budaya</h3><p>Mengangkat cerita, tradisi dan kearifan masyarakat.</p><span class="tag">Budaya</span></div></div>
 </div>
</section>

<section id="galeri">
 <div class="section-head"><div class="kicker">Galeri</div><h2>Catatan perjalanan dan kegiatan lapangan</h2><p>Foto kegiatan komunitas, survei, trekking, sungai, budaya dan masyarakat dapat ditampilkan di sini.</p></div>
 <div class="gallery">
  <div class="big" style="background-image:url('https://images.unsplash.com/photo-1464822759023-fed622ff2c3b?auto=format&fit=crop&w=1200&q=85')"></div>
  <div style="background-image:url('https://images.unsplash.com/photo-1501785888041-af3ef285b470?auto=format&fit=crop&w=900&q=85')"></div>
  <div style="background-image:url('https://images.unsplash.com/photo-1432405972618-c60b0225b8f9?auto=format&fit=crop&w=900&q=85')"></div>
  <div style="background-image:url('https://images.unsplash.com/photo-1470770841072-f978cf4d019e?auto=format&fit=crop&w=900&q=85')"></div>
  <div style="background-image:url('https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?auto=format&fit=crop&w=900&q=85')"></div>
 </div>
</section>

<section id="artikel" class="article">
 <div class="section-head"><div class="kicker">Artikel</div><h2>Cerita, riset dan pengetahuan ekowisata</h2></div>
 <div class="grid">
  <div class="card"><div class="card-body"><div class="kicker">Ekowisata</div><h3>Mengenal Potensi Ekowisata Lubuk Nango</h3><p>Contoh artikel untuk mendokumentasikan hasil studi potensi destinasi.</p></div></div>
  <div class="card"><div class="card-body"><div class="kicker">Lingkungan</div><h3>Menjaga Sungai sebagai Aset Wisata dan Kehidupan</h3><p>Ruang edukasi tentang hubungan konservasi dan pariwisata.</p></div></div>
  <div class="card"><div class="card-body"><div class="kicker">Masyarakat</div><h3>Ekowisata dan Pemberdayaan Masyarakat Lokal</h3><p>Catatan tentang kolaborasi masyarakat dalam pengembangan destinasi.</p></div></div>
 </div>
</section>

<section id="kontak" class="contact">
 <div class="section-head" style="margin:0 auto">
  <div class="kicker" style="color:#d9c7a2">Kolaborasi</div>
  <h2 style="color:white">Mari tumbuh bersama</h2>
  <p>Terbuka untuk kolaborasi riset, pendampingan destinasi, konservasi, wisata minat khusus dan pengembangan potensi lokal.</p>
  <a class="btn" href="https://wa.me/6280000000000">Hubungi Kami</a>
 </div>
</section>

<footer>
 © 2026 Radar Pusako Ecotourism • Kota Pariaman, Sumatera Barat<br>
 <span style="font-size:11px">Menjaga Alam • Merawat Budaya • Mengembangkan Ekowisata</span>
</footer>
</body>
</html>
