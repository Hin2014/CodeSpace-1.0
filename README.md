# CodeSpace-1.0
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>Mi juego Flash</title>
  <script src="https://unpkg.com/@ruffle-rs/ruffle"></script>
</head>
<body>

<div id="game"></div>

<script>
  const ruffle = window.RufflePlayer.newest();
  const player = ruffle.createPlayer();
  document.getElementById("game").appendChild(player);
  player.load("juego.swf");
</script>

</body>
</html>
