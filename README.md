index.html

<!DOCTYPE html>
<html lang="ms">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>List Midman Trusted Malaysia</title>

<style>
body{
  margin:0;
  font-family:Arial, sans-serif;
  background:#0b0b0b;
  color:#fff;
}
.header{
  text-align:center;
  padding:30px 15px;
}
.header h1{
  color:#00ffcc;
  margin-bottom:10px;
}
.header p{
  color:#aaa;
  font-size:14px;
}
.search-box{
  padding:15px;
}
.search-box input{
  width:100%;
  padding:12px;
  border-radius:8px;
  border:none;
  outline:none;
}
.card{
  background:#141414;
  margin:15px;
  padding:15px;
  border-radius:12px;
  box-shadow:0 0 10px rgba(0,255,204,0.1);
}
.name{
  font-size:18px;
  font-weight:bold;
}
.verified{
  background:red;
  color:white;
  font-size:12px;
  padding:3px 8px;
  border-radius:5px;
  margin-left:8px;
}
.status{
  color:#00ff66;
  margin-top:5px;
}
.btn{
  margin-top:12px;
  display:block;
  text-align:center;
  padding:10px;
  border:2px solid #00ff66;
  border-radius:8px;
  color:#00ff66;
  text-decoration:none;
}
</style>
</head>

<body>

<div class="header">
  <h1>List Midman Trusted Malaysia</h1>
  <p>Rasmi • Dikemaskini 21/1/2026 • Elak scam</p>
</div>

<div class="search-box">
  <input type="text" placeholder="Cari nama midman..." onkeyup="searchMidman(this.value)">
</div>

<div id="list">

<div class="card">
  <div class="name">MIDMAN IPANZZ <span class="verified">VERIFIED</span></div>
  <p>WhatsApp: 01118524137
</p>
  <div class="status">Status: Paid / Trusted Midman</div>
  <a class="btn" href="https://wa.me/601118524137">Hubungi WhatsApp</a>
</div>

<div class="card">
  <div class="name">MIDMAN IJAD</div>
  <p>WhatsApp: 01172621738</p>
  <div class="status">Status: Trusted Malaysia</div>
  <a class="btn" href="https://wa.me/601172621738">Hubungi WhatsApp</a>
</div>

</div>

<script>
function searchMidman(keyword){
  let cards = document.querySelectorAll('.card');
  keyword = keyword.toLowerCase();
  cards.forEach(card=>{
    let text = card.innerText.toLowerCase();
    card.style.display = text.includes(keyword) ? "block" : "none";
  });
}
</script>

</body>
</html>
