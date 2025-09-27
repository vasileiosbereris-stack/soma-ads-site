<!DOCTYPE html>
<html lang="el">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>soma-ads</title>
  <style>
    * {margin:0; padding:0; box-sizing:border-box;}
    body {font-family: Arial, sans-serif; background:#000; color:#fff; line-height:1.6;}
    header, section {padding:60px 20px; text-align:center;}
    h1, h2, h3 {color:#0ff; margin-bottom:20px;}
    p {max-width:800px; margin:0 auto 20px;}
    .btn {background:#0f0; color:#000; padding:12px 24px; border-radius:8px; text-decoration:none; font-weight:bold; display:inline-block;}
    .features {display:grid; grid-template-columns:repeat(auto-fit,minmax(220px,1fr)); gap:20px; margin-top:40px;}
    .feature {background:#111; padding:20px; border-radius:12px; box-shadow:0 0 15px rgba(0,255,255,0.3);}
    .how {display:grid; grid-template-columns:repeat(auto-fit,minmax(220px,1fr)); gap:20px; margin-top:40px;}
    .step {background:#111; padding:20px; border-radius:12px;}
    .grid {display:grid; grid-template-columns:repeat(auto-fit,minmax(220px,1fr)); gap:20px; margin-top:40px;}
    .package {background:#111; padding:30px; border-radius:12px; box-shadow:0 0 20px rgba(0,255,255,0.3);}
    form {display:flex; flex-direction:column; gap:15px; max-width:500px; margin:0 auto;}
    input, textarea {padding:12px; border:none; border-radius:8px;}
    footer {padding:20px; background:#111; text-align:center; margin-top:40px;}
    video {max-width:100%; border-radius:12px;}
  </style>
</head>
<body>

  <!-- Hero Section -->
  <header>
    <video autoplay loop muted>
      <source src="assets/hero-avatar.mp4" type="video/mp4">
    </video>
    <h1>Ζωντανέψτε το Brand σας με Ομιλούντες AI Χαρακτήρες</h1>
    <p>Προσωποποιημένα avatars. Εξατομικευμένα περιβάλλοντα. Διαφημίσεις που δείχνουν αληθινές και συνδέονται άμεσα.</p>
    <a href="#contact" class="btn">Δημιουργήστε τη δική σας AI Διαφήμιση Σήμερα</a>
  </header>

  <!-- Γιατί soma-ads -->
  <section>
    <h2>Γιατί να επιλέξετε soma-ads;</h2>
    <div class="features">
      <div class="feature">👤 Ομιλούντα Avatars – Υπερ-ρεαλιστικοί χαρακτήρες που μεταδίδουν το μήνυμά σας.</div>
      <div class="feature">🏙️ Προσαρμοσμένα Περιβάλλοντα – Σκηνικά που ταιριάζουν με το ύφος του brand σας.</div>
      <div class="feature">🌎 Προσωποποίηση – Προφορές, τόνοι και εμφάνιση που ταιριάζουν στο κοινό σας.</div>
      <div class="feature">📱 Έτοιμες για Social Ads – Μορφές βελτιστοποιημένες για TikTok, Instagram, YouTube.</div>
    </div>
  </section>

  <!-- Πώς Λειτουργεί -->
  <section>
    <h2>Πώς Λειτουργεί</h2>
    <div class="how">
      <div class="step">Επιλέξτε το Avatar – Διαλέξτε εμφάνιση, ύφος και στυλ.</div>
      <div class="step">Ορίστε το Σκηνικό – Εταιρικό περιβάλλον ή φουτουριστικό φόντο.</div>
      <div class="step">Σενάριο + Παραγωγή – Το avatar σας παραδίδει το τέλειο μήνυμα.</div>
      <div class="step">Ανέβασμα στα Social Media – Έτοιμο για δημοσίευση, γρήγορα.</div>
    </div>
    <a href="#demo" class="btn">Δείτε τα Avatars σε Δράση</a>
  </section>

  <!-- Demo Reel / Showcase με περιγραφές -->
  <section id="demo">
    <h2>Demo Reel / Showcase</h2>
    <video autoplay loop muted controls>
      <source src="assets/demo-main.mp4" type="video/mp4">
    </video>
    <div class="grid">
      <div>
        <video autoplay loop muted controls><source src="assets/avatar1.mp4" type="video/mp4"></video>
        <p>Avatar 1 – Άνδρας, εταιρικό περιβάλλον</p>
      </div>
      <div>
        <video autoplay loop muted controls><source src="assets/avatar2.mp4" type="video/mp4"></video>
        <p>Avatar 2 – Γυναίκα, φουτουριστικό φόντο</p>
      </div>
      <div>
        <video autoplay loop muted controls><source src="assets/avatar3.mp4" type="video/mp4"></video>
        <p>Avatar 3 – Πολυγλωσσικό, εταιρικό περιβάλλον</p>
      </div>
      <div>
        <video autoplay loop muted controls><source src="assets/avatar4.mp4" type="video/mp4"></video>
        <p>Avatar 4 – Γυναίκα, φουτουριστικό φόντο</p>
      </div>
    </div>
  </section>

  <!-- Πακέτα -->
  <section>
    <h2>Πακέτα / Τιμοκατάλογος</h2>
    <div class="grid">
      <div class="package">
        <h3>Starter Ad – 199€</h3>
        <p>Ένα avatar σε απλό περιβάλλον (15 δευτ. διαφήμιση).</p>
      </div>
      <div class="package">
        <h3>Pro Ad – 499€</h3>
        <p>Προσαρμοσμένο avatar + εταιρικό περιβάλλον (30 δευτ., 1 διόρθωση).</p>
      </div>
      <div class="package">
        <h3>Premium Ad – 999€</h3>
        <p>Πολλαπλά avatars, κινηματογραφικές σκηνές, προηγμένη προσωποποίηση (1–2 λεπτά).</p>
      </div>
    </div>
  </section>

  <!-- About -->
  <section>
    <h2>Σχετικά με τη soma-ads</h2>
    <p>Συνδυάζουμε την καινοτομία της Τεχνητής Νοημοσύνης με ρεαλιστικά avatars για τη δημιουργία διαφημιστικών βίντεο που είναι αυθεντικά, προσωπικά και αξέχαστα.</p>
  </section>

  <!-- Επικοινωνία -->
  <section id="contact">
    <h2>Επικοινωνία</h2>
    <form>
      <input type="text" placeholder="Όνομα" required>
      <input type="email" placeholder="Email" required>
      <input type="text" placeholder="Εταιρεία">
      <textarea placeholder="Μήνυμα" rows="5"></textarea>
      <button type="submit" class="btn">Ας Δημιουργήσουμε Μαζί τη Διαφήμιση με το Avatar σας</button>
    </form>
  </section>

  <footer>
    <p>© 2025 soma-ads | Follow us on Social Media</p>
  </footer>

</body>
</html>
