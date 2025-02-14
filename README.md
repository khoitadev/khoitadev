# <p align="center">Trần Anh Khôi</p>

<p align="center">
	<a href="https://github.com/trananhkhoi">
	<img src="https://avatars.githubusercontent.com/u/99550496?v=4" width = "200" alt="TAK">
	</a>
</p>

<h2 align="center">About me</h2>

```C#
namespace AK
{
    class TranAnhKhoi
    {
        static void Main(string[] args)
        {
            string Name = "Trần Anh Khôi";
            string Age = "2001";
            string Gender = "Male";
            string Address = "Hà Tĩnh, Việt Nam";
            string University = "Trường Đại học Vinh";
            string Skills = "C, C++, C#, Java, Python, HTML, PHP, JavaScript";
            string FamousQuotes = "Bình thường nhưng không tầm thường";
        }
    }
}
```

## <p align="center">You can reach me at 🌹</p>

<p align="center">
  <a href="https://www.facebook.com/khoitadev">
    <img src="https://www.vectorlogo.zone/logos/facebook/facebook-official.svg" alt="Facebook" height="30" width="30">
  </a>
	
  <a href="https://github.com/trananhkhoi">
    <img src="https://www.vectorlogo.zone/logos/github/github-tile.svg" alt="Github" height="30" width="30">
  </a>
  
  <a href="https://dev.to/trananhkhoi">
    <img src="https://www.vectorlogo.zone/logos/devto/devto-icon.svg" alt="DevTo" height="30" width="30">
  </a>
	
  <!-- <a href="https://www.linkedin.com/in/trananhkhoi/">
    <img src="https://www.vectorlogo.zone/logos/linkedin/linkedin-icon.svg" alt="Linkedin" height="30" width="30">
  </a> -->
  
  <a href="mailto:khoitadev@gmail.com">
    <img src="https://www.vectorlogo.zone/logos/google/google-icon.svg" alt="Google" height="30" width="30">
  </a>
	
  <a href="https://www.instagram.com/trananhkhoi5657/">
    <img src="https://www.vectorlogo.zone/logos/instagram/instagram-icon.svg" alt="Instagram" height="30" width="30">
  </a>
  
  <a href="/https://www.tiktok.com/@khoi_167601">
    <img src="https://raw.githubusercontent.com/gilbarbara/logos/master/logos/tiktok-icon.svg" alt="TikTok" height="30" width="30">
  </a>
  
  <a href="https://www.youtube.com/channel/UCvStEl7lHuGZlCuxtgvNFEQ">
    <img src="https://www.vectorlogo.zone/logos/youtube/youtube-icon.svg" alt="YouTube" height="30" width="30">
  </a>
</p>
</p>

<hr>
<br>

##

<p align="center"><img src="https://thumbs.gfycat.com/GoodnaturedFondGaur-size_restricted.gif" alt="Synthwave" height="300" width="500"></p>

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta
      name="viewport"
      content="width=device-width, 
                   initial-scale=1.0"
    />
    <title>Neon Cursor</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet" />
    <style>
      body,
      html,
      #app {
        margin: 0;
        width: 100%;
        height: 100%;
      }

      #app {
        overflow: hidden;
        touch-action: pan-up;
        color: #ffffff;
        font-family: 'Montserrat', sans-serif;
        text-align: center;
        text-shadow: 0 0 5px #ffffff, 0 0 20px #000, 0 0 30px #000;
      }

      #app h1 {
        --fontSize: 60px;
        --lineHeight: 80px;
        width: auto;
        height: calc(2 * var(--lineHeight));
        line-height: var(--lineHeight);
        margin: calc(50vh - var(--lineHeight)) auto 0;
        font-size: var(--fontSize);
        text-transform: uppercase;
      }

      #app a {
        margin-top: 10px;
        display: inline-block;
        text-decoration: none;
        color: #fff;
      }

      #app canvas {
        display: block;
        position: fixed;
        z-index: -1;
        top: 0;
      }
    </style>
  </head>

  <body>
    <div id="app">
      <div id="hero"></div>
    </div>
  </body>
  <script type="module">
    import { neonCursor } from 'https://unpkg.com/threejs-toys@0.0.8/build/threejs-toys.module.cdn.min.js'

    neonCursor({
      el: document.getElementById('app'),
      shaderPoints: 16,
      curvePoints: 80,
      curveLerp: 0.5,
      radius1: 5,
      radius2: 30,
      velocityTreshold: 10,
      sleepRadiusX: 100,
      sleepRadiusY: 100,
      sleepTimeCoefX: 0.0025,
      sleepTimeCoefY: 0.0025,
    })
  </script>
</html>

