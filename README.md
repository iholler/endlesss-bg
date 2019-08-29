<video autoplay muted loop id="myVideo">
  <source src="https://media.giphy.com/media/ht2NLwZFTh9wk/giphy.mp4" type="video/mp4">
  Your browser does not support HTML5 video.
</video>
<script>
var video = document.getElementById("myVideo");
var btn = document.getElementById("myBtn");

function myFunction() {
  if (video.paused) {
    video.play();
    btn.innerHTML = "Pause";
  } else {
    video.pause();
    btn.innerHTML = "Play";
  }
}
</script>
