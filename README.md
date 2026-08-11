# FF-top-up-BD
FF top up BD 
<!doctype html>
<html lang="bn">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>FF TopUp BD тАФ Demo</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
<header>
  <div class="brand">ЁЯТО FF TopUp BD</div>
  <a href="#admin">Admin</a>
</header>

<main>
  <section class="hero">
    <h1>Free Fire Diamond Top-Up</h1>
    <p>Demo order system тАФ ржЖрж╕рж▓ Diamond delivery/payment ржПржЦржирзЛ ржпрзБржХрзНржд ржирзЗржЗред</p>
  </section>

  <section class="card">
    <h2>ржЕрж░рзНржбрж╛рж░ ржХрж░рзБржи</h2>
    <label>Player UID</label>
    <input id="uid" inputmode="numeric" placeholder="ржпрзЗржоржи: 1234567890">

    <label>Diamond Package</label>
    <select id="package">
      <option value="100">100 ЁЯТО тАФ рз│80</option>
      <option value="310">310 ЁЯТО тАФ рз│230</option>
      <option value="520">520 ЁЯТО тАФ рз│380</option>
      <option value="1060">1060 ЁЯТО тАФ рз│750</option>
    </select>

    <label>Payment Method</label>
    <select id="payment">
      <option>bKash</option>
      <option>Nagad</option>
      <option>Upay</option>
      <option>Manual / ржкрж░рзЗ ржкрзЗржорзЗржирзНржЯ</option>
    </select>

    <button onclick="placeOrder()">ржЕрж░рзНржбрж╛рж░ рж╕рж╛ржмржорж┐ржЯ</button>
    <p id="result" class="result"></p>
  </section>

  <section class="card">
    <h2>ржЕрж░рзНржбрж╛рж░ рж╕рзНржЯрзНржпрж╛ржЯрж╛рж╕</h2>
    <input id="searchId" placeholder="Order ID рж▓рж┐ржЦрзБржи">
    <button class="secondary" onclick="checkOrder()">рж╕рзНржЯрзНржпрж╛ржЯрж╛рж╕ ржжрзЗржЦрзБржи</button>
    <div id="status"></div>
  </section>

  <section id="admin" class="card admin">
    <h2>ЁЯФР Admin Panel (Demo)</h2>
    <p class="warning">ржПржЯрж┐ рж╢рзБржзрзБ ржбрзЗржорзЛред ржмрзНрж░рж╛ржЙржЬрж╛рж░рзЗрж░ localStorage-ржП ржбрзЗржЯрж╛ ржерж╛ржХрзЗ; ржмрж╛рж╕рзНрждржм рж╕рж╛ржЗржЯрзЗ ржПржнрж╛ржмрзЗ admin security рж░рж╛ржЦрж╛ ржпрж╛ржмрзЗ ржирж╛ред</p>
    <input id="adminPass" type="password" placeholder="Demo password">
    <button class="secondary" onclick="adminLogin()">Login</button>
    <div id="adminArea" hidden>
      <button class="danger" onclick="clearOrders()">рж╕ржм ржЕрж░рзНржбрж╛рж░ ржорзБржЫрзБржи</button>
      <div id="orders"></div>
    </div>
  </section>
</main>

<footer>┬й 2026 FF TopUp BD тАФ Demo only</footer>
<script src="script.js"></script>
</body>
</html>
<img width="1080" height="1080" alt="1000044972" src="https://github.com/user-attachments/assets/648d79ea-8ab5-42c8-94e7-be1efa70b747" />
