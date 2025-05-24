# consulenzaautolegale
<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Consulenza Auto Legale</title>
  <style>
    body {
      font-family: Georgia, serif;
      margin: 0;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background-color: #00274d;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    header img {
      max-width: 100px;
      margin-bottom: 1rem;
    }
    nav {
      text-align: center;
      margin-top: 1rem;
    }
    nav a {
      margin: 0 1rem;
      color: #00274d;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }
    h2 {
      color: #00274d;
    }
    footer {
      background-color: #00274d;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
    form input, form textarea {
      width: 100%;
      padding: 0.5rem;
      margin-top: 0.5rem;
      margin-bottom: 1rem;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    form button {
      background-color: #00274d;
      color: white;
      padding: 0.7rem 1.5rem;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="Logo Consulenza Auto Legale">
    <h1>Consulenza Auto Legale</h1>
    <p>Assistenza giuridica per privati e concessionarie – Civitavecchia, Roma, Viterbo</p>
  </header>
  <nav>
    <a href="#chi-siamo">Chi siamo</a>
    <a href="#servizi">Servizi</a>
    <a href="#contatti">Contatti</a>
  </nav>

  <section id="chi-siamo">
    <h2>Chi siamo</h2>
    <p>Laureato in Giurisprudenza con esperienza diretta nel mondo delle concessionarie, offro consulenze legali specializzate in ambito automobilistico. Lavoro principalmente tra Civitavecchia, Roma e Viterbo, fornendo supporto a privati e professionisti del settore auto.</p>
  </section>

  <section id="servizi">
    <h2>Servizi offerti</h2>
    <ul>
      <li>Verifica e redazione contratti di acquisto auto</li>
      <li>Assistenza su vizi occulti e garanzie legali</li>
      <li>Consulenze su leasing, noleggio e fermi amministrativi</li>
      <li>Ricorsi e difesa per multe</li>
      <li>Richieste di risarcimento danni da sinistri o difetti</li>
      <li>Supporto in controversie legali legate al mondo auto</li>
    </ul>
  </section>

  <section id="contatti">
    <h2>Contatti</h2>
    <p>Email: <a href="mailto:info@consulenzaautolegale.it">info@consulenzaautolegale.it</a></p>
    <p>Telefono / WhatsApp: <a href="tel:+393202768801">320 276 8801</a></p>
    <form action="mailto:info@consulenzaautolegale.it" method="post" enctype="text/plain">
      <label for="nome">Nome</label>
      <input type="text" id="nome" name="nome" required>

      <label for="email">Email</label>
      <input type="email" id="email" name="email" required>

      <label for="messaggio">Messaggio</label>
      <textarea id="messaggio" name="messaggio" rows="5" required></textarea>

      <button type="submit">Invia richiesta</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Consulenza Auto Legale – Tutti i diritti riservati</p>
  </footer>
</body>
</html>
