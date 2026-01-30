no put the pic as logo of my product <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Social Hub Pro</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" rel="stylesheet">
<style>
body {
  background: #0f0f0f;
  color: #fff;
  font-family: 'Segoe UI', sans-serif;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 0;
}
.container {
  text-align: center;
  background: #1c1c1c;
  padding: 50px;
  border-radius: 20px;
  width: 100%;
  max-width: 400px;
  box-shadow: 0 0 40px #000;
}
h1 {
  margin-bottom: 40px;
  font-size: 28px;
  letter-spacing: 1px;
}
a {
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 15px 0;
  padding: 15px;
  border-radius: 12px;
  text-decoration: none;
  color: #fff;
  font-size: 18px;
  font-weight: bold;
  transition: all 0.3s ease;
  position: relative;
  overflow: hidden;
}
a i {
  margin-right: 12px;
  font-size: 22px;
  transition: transform 0.3s;
}
/* TikTok button */
.tiktok { background: #000; border: 1px solid #fff; }
.tiktok:hover { transform: scale(1.1); box-shadow: 0 0 20px #fff; }
/* Instagram button */
.instagram {
  background: linear-gradient(45deg,#f58529,#dd2a7b,#8134af);
}
.instagram:hover { transform: scale(1.1); box-shadow: 0 0 20px #f58529; }
/* Facebook button */
.facebook { background: #1877f2; }
.facebook:hover { transform: scale(1.1); box-shadow: 0 0 20px #1877f2; }
/* Pulse icon on hover */
a:hover i {
  transform: rotate(15deg) scale(1.2);
}
/* Floating background effect */
a::before {
  content: '';
  position: absolute;
  width: 300%;
  height: 300%;
  top: -100%;
  left: -100%;
  background: rgba(255,255,255,0.1);
  transform: rotate(45deg);
  transition: all 0.5s ease;
}
a:hover::before {
  top: -50%;
  left: -50%;
}
</style>
</head>
<body>
<div class="container">
  <h1>Follow My Business</h1>
  <a class="tiktok" href="https://www.tiktok.com/@nini.chocolat?_r=1&_t=ZS-93VAu3WE3O5" target="_blank">
    <i class="fab fa-tiktok"></i> TikTok
  </a>
  <a class="instagram" href="https://www.instagram.com/cho_co_nini?igsh=Mzc3OHhkbmF1ejR3" target="_blank">
    <i class="fab fa-instagram"></i> Instagram
  </a>
  <a class="facebook" href="https://www.facebook.com/share/1E7E4Ggbtd/?mibextid=wwXIfr" target="_blank">
    <i class="fab fa-facebook-f"></i> Facebook
  </a>
</div>
</body>
</html>
