<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KindHaul Dashboard</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<header>
  <h1>Welcome to KindHaul Dashboard</h1>
  <nav>
    <a href="trucks.html">Trucks</a> |
    <a href="invoice.html">Invoices</a> |
    <a href="giveaways.html">Giveaways</a> |
    <a href="contact.html">Contact</a> |
    <a href="#" onclick="logout()">Logout</a>
  </nav>
</header>

<main>
  <h2>Hello, <span id="userName">User</span>!</h2>
  <p>View trucks, request invoices, and participate in giveaways.</p>
</main>

<footer>
  <p>Customer Care: <a href="tel:+15134370262">+1 (513) 437-0262</a></p>
  <div class="social-icons">
    <a href="https://www.facebook.com/share/1DqSvo7uny/?mibextid=wwXIfr" target="_blank">Facebook</a>
    <a href="https://t.me/kindhaultrucks" target="_blank">Telegram</a>
    <a href="https://wa.me/14424750778" target="_blank">WhatsApp</a>
  </div>
</footer>

<script src="script.js"></script>
<script>
document.getElementById('userName').textContent = loggedInUser?.name || "User";
</script>
</body>
</html>
