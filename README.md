# Mezo
links
<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <title>روابطي</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    /* خلفية بلورية متدرجة */
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #89f7fe, #66a6ff, #d5c2ff, #ffd6f5);
      background-size: 400% 400%;
      animation: gradientBG 20s ease infinite;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    @keyframes gradientBG {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    .card {
      background: rgba(255, 255, 255, 0.2);
      backdrop-filter: blur(20px);
      border-radius: 25px;
      width: 360px;
      padding: 30px 20px;
      text-align: center;
      box-shadow: 0 15px 40px rgba(0,0,0,0.2);
      transition: transform 0.3s, box-shadow 0.3s;
      border: 1px solid rgba(255, 255, 255, 0.3);
    }

    .card:hover {
      transform: translateY(-10px);
      box-shadow: 0 25px 50px rgba(0,0,0,0.3);
    }

    .profile-img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid rgba(255,255,255,0.6);
      margin-bottom: 15px;
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .profile-img:hover {
      transform: scale(1.12);
      box-shadow: 0 0 20px rgba(255,255,255,0.5);
    }

    h2 {
      margin: 10px 0;
      color: #fff;
      text-shadow: 1px 1px 4px rgba(0,0,0,0.4);
    }

    p {
      color: #eee;
      margin-bottom: 25px;
      font-size: 14px;
      text-shadow: 1px 1px 2px rgba(0,0,0,0.3);
    }

    .links {
      display: flex;
      justify-content: center;
      gap: 15px;
      flex-wrap: wrap;
    }

    .links a {
      font-size: 24px;
      width: 50px;
      height: 50px;
      line-height: 50px;
      border-radius: 50%;
      color: white;
      display: inline-block;
      transition: 0.3s;
      text-align: center;
      position: relative;
    }

    .links a::after {
      content: attr(aria-label);
      position: absolute;
      bottom: -35px;
      left: 50%;
      transform: translateX(-50%);
      background: rgba(0,0,0,0.75);
      color: #fff;
      padding: 4px 10px;
      border-radius: 6px;
      font-size: 12px;
      opacity: 0;
      pointer-events: none;
      transition: 0.3s;
      white-space: nowrap;
    }

    .links a:hover::after {
      opacity: 1;
      bottom: -45px;
    }

    .links a:hover {
      transform: scale(1.3);
      box-shadow: 0 0 15px rgba(255,255,255,0.6);
    }

    /* ألوان الأيقونات مع glow */
    .facebook { background: #1877f2; box-shadow: 0 0 8px #1877f2; }
    .instagram { background: #e1306c; box-shadow: 0 0 8px #e1306c; }
    .twitter { background: #1da1f2; box-shadow: 0 0 8px #1da1f2; }
    .tiktok { background: #000; box-shadow: 0 0 8px #000; }
    .snapchat { background: #fffc00; color: #000; border: 1px solid #ccc; box-shadow: 0 0 8px #fffc00; }
    .whatsapp { background: #25D366; box-shadow: 0 0 8px #25D366; }

  </style>
</head>
<body>

  <div class="card">
    <img src="https://via.placeholder.com/120" alt="صورة شخصية" class="profile-img">
    <h2>مازن كامل</h2>
    <p>تابعني على مواقعي للتواصل 👇</p>
    <div class="links">
      <a href="https://www.facebook.com/btykhmskh" class="facebook" target="_blank" aria-label="فيسبوك"><i class="fab fa-facebook-f"></i></a>
      <a href="https://www.instagram.com/btykhmskh" class="instagram" target="_blank" aria-label="انستغرام"><i class="fab fa-instagram"></i></a>
      <a href="https://twitter.com/mazen_kamel5021" class="twitter" target="_blank" aria-label="تويتر"><i class="fab fa-twitter"></i></a>
      <a href="https://www.tiktok.com/@mazen_kamel5021" class="tiktok" target="_blank" aria-label="تيك توك"><i class="fab fa-tiktok"></i></a>
      <a href="https://www.snapchat.com/add/mazen_kamel5021" class="snapchat" target="_blank" aria-label="سناب شات"><i class="fab fa-snapchat-ghost"></i></a>
      <a href="https://wa.me/249129428096" class="whatsapp" target="_blank" aria-label="واتساب"><i class="fab fa-whatsapp"></i></a>
    </div>
  </div>

</body>
</html>
