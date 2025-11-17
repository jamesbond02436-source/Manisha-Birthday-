<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Happy Birthday Manisha 🎂💖</title>

  <style>
    *{margin:0;padding:0;box-sizing:border-box;font-family:"Poppins",sans-serif;}

    body{
      min-height:100vh;
      background:radial-gradient(circle at top,#ffe0f0,#fbc2eb,#a18cd1);
      display:flex;
      align-items:center;
      justify-content:center;
      padding:18px;
      color:#fff;
      overflow-x:hidden;
      position:relative;
    }

    h1{
      font-size:2.4rem;
      text-shadow:0 3px 8px rgba(0,0,0,0.35);
      margin-bottom:10px;
      text-align:center;
    }

    .name{color:#ffe082;}

    .wrapper{max-width:900px;width:100%;text-align:center;}

    /* Floating Hearts */
    .heart{
      position:absolute;
      color:rgba(255,255,255,0.45);
      font-size:22px;
      animation:floatUp 6s linear infinite;
      z-index:0;
    }
    @keyframes floatUp{
      0%{transform:translateY(100vh) translateX(0);}
      100%{transform:translateY(-10vh) translateX(20px);}
    }

    /* Cake Animation */
    .cake-area{display:flex;justify-content:center;margin:28px 0;}
    .cake{position:relative;width:160px;height:160px;animation:floatCake 3s ease-in-out infinite;}
    @keyframes floatCake{0%,100%{transform:translateY(0);}50%{transform:translateY(-8px);}}
    .cake-base{
      position:absolute;bottom:0;left:50%;transform:translateX(-50%);
      width:140px;height:55px;background:#ff9eb5;border-radius:18px 18px 10px 10px;
      box-shadow:0 8px 18px rgba(0,0,0,0.35);
    }
    .cake-layer{
      position:absolute;bottom:40px;left:50%;transform:translateX(-50%);
      width:130px;height:45px;background:#ffe4f2;border-radius:18px 18px 14px 14px;
      box-shadow:0 4px 10px rgba(0,0,0,0.25);
    }
    .icing{
      position:absolute;bottom:70px;left:50%;transform:translateX(-50%);
      width:120px;height:26px;background:#fff2fa;border-radius:18px;overflow:hidden;
    }
    .icing::before,.icing::after{
      content:"";position:absolute;width:28px;height:28px;background:#ffd1ec;border-radius:50%;top:10px;
    }
    .icing::before{left:15px;}
    .icing::after{right:15px;}
    .sprinkles span{
      position:absolute;width:6px;height:3px;border-radius:3px;background:#ff6f9c;
    }
    .sprinkles span:nth-child(1){top:6px;left:18px;}
    .sprinkles span:nth-child(2){top:4px;left:40px;}
    .sprinkles span:nth-child(3){top:8px;left:62px;}
    .sprinkles span:nth-child(4){top:6px;left:84px;}
    .sprinkles span:nth-child(5){top:4px;left:100px;}
    .candle{
      position:absolute;bottom:92px;left:50%;transform:translateX(-50%);
      width:10px;height:35px;background:repeating-linear-gradient(to bottom,#ff9eb5,#ff9eb5 5px,#fff 5px,#fff 10px);
      border-radius:5px;
    }
    .flame{
      position:absolute;top:-14px;left:50%;transform:translateX(-50%);
      width:16px;height:24px;background:radial-gradient(circle at 50% 20%,#fff7a0,#ffb347);
      border-radius:50%;box-shadow:0 0 12px rgba(255,215,130,0.9);
      animation:flicker .6s infinite alternate;
    }
    @keyframes flicker{0%{transform:translateX(-50%) scale(1);}100%{transform:translateX(-48%) scale(1.08);}}


    /* Gallery */
    .gallery-title{font-size:1.2rem;margin-bottom:12px;font-weight:500;}
    .gallery{
      display:grid;gap:14px;
      grid-template-columns:repeat(auto-fit,minmax(160px,1fr));
      margin-top:12px;
    }
    .photo{
      position:relative;border-radius:14px;overflow:hidden;
      border:2px solid rgba(255,255,255,0.6);
      box-shadow:0 6px 16px rgba(0,0,0,0.35);
      background:rgba(255,255,255,0.15);
    }
    .photo img{
      width:100%;height:190px;object-fit:cover;display:block;
      transition:.25s;
    }
    .photo:hover img{transform:scale(1.05);}
    .photo-tag{
      position:absolute;bottom:6px;left:8px;right:8px;
      background:rgba(0,0,0,0.45);font-size:.75rem;padding:3px 6px;border-radius:999px;
    }

  </style>
</head>
<body>

  <!-- Floating Hearts -->
  <span class="heart" style="left:10%; animation-delay:0s;">❤</span>
  <span class="heart" style="left:30%; animation-delay:2s;">❤</span>
  <span class="heart" style="left:50%; animation-delay:4s;">❤</span>
  <span class="heart" style="left:70%; animation-delay:1s;">❤</span>
  <span class="heart" style="left:90%; animation-delay:3s;">❤</span>

  <div class="wrapper">
    <h1>Happy Birthday <span class="name">Manisha</span> 🎉</h1>

    <!-- CAKE -->
    <div class="cake-area">
      <div class="cake">
        <div class="cake-base"></div>
        <div class="cake-layer"></div>
        <div class="icing">
          <div class="sprinkles"><span></span><span></span><span></span><span></span><span></span></div>
        </div>
        <div class="candle"><div class="flame"></div></div>
      </div>
    </div>

    <!-- PHOTO GALLERY -->
    <div class="gallery-title">Some beautiful moments of Manisha 💖</div>
    <div class="gallery">

      <div class="photo">
        <img src="manisha1.jpg" alt="">
        <div class="photo-tag">Memorable day 🌿</div>
      </div>

      <div class="photo">
        <img src="manisha2.jpg" alt="">
        <div class="photo-tag">Lovely smile ✨</div>
      </div>

      <div class="photo">
        <img src="manisha3.jpg" alt="">
        <div class="photo-tag">Adorable baby 👶💗</div>
      </div>

      <div class="photo">
        <img src="manisha4.jpg" alt="">
        <div class="photo-tag">Mountain vibes 🌄</div>
      </div>

    </div>
  </div>
</body>
</html>
