<!DOCTYPE html>
<html>
<head>
  <title>MR.VIX SU</title>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
  <header>
    <h1>WELCOME TO HOME OF SURE ODDS</h1>
    <nav>
      <ul>
        <li><a href="                              
        <li><a href="#vip-tips">VIP Betting Tips</a></li>
        <li><a href="                         
        <li><a href="#contact">Contact Us</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <section id="tips">
      <h2>Free daily odd</h2>
      <ul>
        <li>Chelsea vs Man Utd (2:1)</li>
      </ul>
    </section>
    <section id="vip-tips"> To access vip odds message the contact below
      <h2>VIP ODDS</h2>
      <p>Password required: <input type="password" id="vip-password">
      <button onclick="checkPassword()">Enter</button>
      <div id="vip-content" style="display:none;">
        <p>WEEKLY SUBSCRIPTION 21000UGX
        </p>
        <p>
          
        </p>DAILY SUBSCRIPTION 3000UGX</p>
      </div>
    </section>
    <section id="about">
      <h2>About Us</h2>
      <p>We provide expert sure odds for Uganda and global matches.</p>
    </section>
    <section id="contact">
      <h2>Contact Us</h2>
      <p>Contact on WhatsApp: <a href="https://wa.me/256782149337">+256 782149337</a></p>

    </section>
  </main>
  <script>
    function checkPassword() {
      let pass = document.getElementById('vip-password').value;
      if(pass == 'NIIRO') {
        document.getElementById('vip-content').style.display = 'block';
      } else {
        alert('password entered is incorrect !');
      }
    }
  </script>
</body>
</html>
