index.html<!DOCTYPE html>
<html>
<head>
  <title>駿太の動画サイト</title>
</head>
<body>

<h1>動画を選んで再生</h1>

<button onclick="changeVideo('abc123XYZ')">動画1</button>
<button onclick="changeVideo('def456XYZ')">動画2</button>

<br><br>

<iframe id="player" width="560" height="315"
src="https://www.youtube.com/embed/abc123XYZ"
frameborder="0" allowfullscreen></iframe>

<script>
function changeVideo(id){
  document.getElementById("player").src =
  "https://www.youtube.com/embed/" + id;
}
</script>

</body>
</html>
