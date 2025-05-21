<!DOCTYPE html><html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gandhok Simbok</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fff0f0;
      color: #330000;
    }
    header {
      background-color: #cc0000;
      color: white;
      padding: 1em;
      text-align: center;
    }
    nav {
      background-color: #990000;
      padding: 0.5em;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 1em;
      text-decoration: none;
    }
    .produk {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1em;
      padding: 1em;
    }
    .card {
      border: 1px solid #ddd;
      border-radius: 10px;
      padding: 1em;
      background-color: #fff8f8;
    }
    .card h3 {
      margin-top: 0;
    }
    .btn {
      background-color: #cc0000;
      color: white;
      border: none;
      padding: 0.5em 1em;
      border-radius: 5px;
      cursor: pointer;
    }
    footer {
      text-align: center;
      background-color: #330000;
      color: white;
      padding: 1em;
      margin-top: 2em;
    }
  </style>
</head>
<body>
  <header>
    <h1>Gandhok Simbok</h1>
    <p>Rasanya Nampol, Pedesnya Nagih!</p>
  </header>  <nav>
    <a href="#kremesan">Kremesan</a>
    <a href="#krispi">Krispi Celup</a>
    <a href="#mie">Mie Jebew</a>
    <a href="https://wa.me/6281234567890" target="_blank">Chat Simbok</a>
  </nav>  <section class="produk" id="kremesan">
    <div class="card">
      <h3>Kremesan Sambal Original</h3>
      <p>Pedas gurih khas Simbok.</p>
      <button class="btn">Tambah ke Keranjang</button>
    </div>
    <div class="card">
      <h3>Kremesan Sambal Terasi</h3>
      <p>Wangi terasi yang menggoda.</p>
      <button class="btn">Tambah ke Keranjang</button>
    </div>
    <!-- Tambahkan varian lainnya -->
  </section>  <section class="produk" id="krispi">
    <div class="card">
      <h3>Krispi Celup Saus Judes</h3>
      <p>Rasa pedas menggigit!</p>
      <button class="btn">Tambah ke Keranjang</button>
    </div>
    <!-- Tambahkan varian lainnya -->
  </section>  <section class="produk" id="mie">
    <div class="card">
      <h3>Mie Jebew Rasa Rendang</h3>
      <p>Rasa lokal yang mewah.</p>
      <button class="btn">Tambah ke Keranjang</button>
    </div>
    <!-- Tambahkan varian lainnya -->
  </section>  <footer>
    <p>&copy; 2025 Gandhok Simbok. Semua hak dilindungi.</p>
  </footer>
</body>
</html>
