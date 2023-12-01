<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link rel="icon" href="/assets/img/newlogo.png">
  <link href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap" rel="stylesheet" />
  <link rel="stylesheet" href="/assets/css/style.css" />
  <script src="/assets/js/functions.js"></script>
  <script data-cfasync="false" typ="text/javascript" src="ads.js"></script>
  <script data-cfasync="false" typ="text/javascript" src="ads2.js"></script>
  <title>Search | Snorlax's Cave</title>
</head>
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-ZTCTYH80S1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-ZTCTYH80S1');
</script>
<body>
  <nav>
    <div class="heading">
       <a href="/#" class="headinglink">Snorlax's Cave</a>
    </div>
    <ul class="nav-links">
      <li><a href="/">Home</a></li>
      <li><a href="/math">Games</a></li>
      <li><a href="/english">Apps</a></li>
      <li><a class="active" href="/science">Proxy</a></li>
      <li><a href="/about">About</a></li>
      <li><a href="/settings">Settings</a></li>

    </ul>
  </nav>
  <br>
  <br>
  <form class="proxyform">
    <h1 style="font-size:33px;color:white;">Proxy</h1>
    <br>
    <input class="proxy" placeholder="Type URL or search query" style="color:white;"></input>
  </form>
  <script src="/assets/js/index.js"></script>
  <script src="/uv/uv.bundle.js"></script>
  <script src="/uv/uv.config.js"></script>
  <script>
    // Custom Background Check
    var bgUrl = localStorage.getItem('backgroundImage');
    if (bgUrl === 'none' || bgUrl === null || bgUrl === '') {
      document.body.style.backgroundImage = `url('/assets/img/snorlax_background.jpg')`;
    } else {
        document.body.style.backgroundImage = `url(${bgUrl})`;
    }
    </script>
</body>
</html>
