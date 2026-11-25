<!DOCTYPE html>
<html lang="min">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Coding Minang - Arsitektur Kode Ranah Minangkabau</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&family=Playfair+Display:ital,wght@0,700;0,900;1,700&family=Fira+Code:wght@400;500;600&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif}
:root{
  --merah:#7B1113;
  --merah-terang:#A8181B;
  --emas:#D4AF37;
  --emas-terang:#F5E08E;
  --hitam:#121212;
  --hitam-mudo:#1a1a1a;
  --hitam-kartu:#222222;
  --krem:#FFF8E7;
  --border:#383838;
}
body{background:var(--hitam);color:#fff;scroll-behavior:smooth;overflow-x:hidden}
/* Songket & Marawa Motif Accent */
.songket{height:14px;background:repeating-linear-gradient(45deg,var(--emas) 0 16px,var(--merah) 16px 32px,#000 32px 48px,var(--emas) 48px 54px)}
.marawa-strip{height:6px;background:linear-gradient(90deg,#000 33.3%,var(--merah) 33.3% 66.6%,var(--emas) 66.6%)}
/* Header & Navigation */
header{background:linear-gradient(rgba(10,10,10,0.92),rgba(123,17,19,0.95)),url('https://images.unsplash.com/photo-1550745165-9bc0b252726f?w=1600') center/cover;padding:22px 5% 80px;text-align:center;position:relative}
nav{display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:15px;position:relative;z-index:10}
.logo{font-family:'Playfair Display';font-size:26px;color:var(--emas);letter-spacing:1px;display:flex;align-items:center;gap:8px}
.logo span{color:#fff}
.nav-links{display:flex;align-items:center;flex-wrap:wrap;gap:18px}
nav a{color:#fff;text-decoration:none;font-size:14px;transition:.3s;font-weight:500}
nav a:hover{color:var(--emas)}
/* Language Switcher */
.lang-switcher{display:inline-flex;background:rgba(0,0,0,0.7);border:1px solid var(--emas);border-radius:25px;padding:3px;gap:2px}
.lang-btn{background:transparent;color:#ddd;border:none;padding:5px 12px;border-radius:20px;font-size:12px;font-weight:600;cursor:pointer;transition:.25s}
.lang-btn:hover{color:#fff}
.lang-btn.active{background:var(--emas);color:#000;box-shadow:0 2px 10px rgba(212,175,55,.45)}
/* Buttons */
.btn{background:var(--emas);color:#000;padding:12px 26px;border:none;border-radius:30px;font-weight:700;cursor:pointer;transition:.3s;display:inline-flex;align-items:center;gap:8px;font-size:14px}
.btn:hover{background:#fff;transform:translateY(-2px);box-shadow:0 5px 18px rgba(212,175,55,.4)}
