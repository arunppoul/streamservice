
<html> 
<body> 

<button onclick="playVid()" type="button">Play Video</button>
<button onclick="pauseVid()" type="button">Pause Video</button><br> 

<video id="myVideo" width="320" height="176">
  <source src="mov_bbb.mp4" type="video/mp4">
  <source src="mov_bbb.ogg" type="video/ogg">
  Your browser does not support HTML5 video.
</video>

<script> 
var vid = document.getElementById("myVideo"); 

function playVid() { 
  vid.play(); 
} 

function pauseVid() { 
  vid.pause(); 
} 
</script> 

<p>Video courtesy of </p>

<div style="position: relative; padding-top: 56.25%;"><iframe src="https://iframe.mediadelivery.net/embed/32327/b727d5f8-2068-4b00-9358-22a4424d79f8?autoplay=true" loading="lazy" style="border: none; position: absolute; top: 0; height: 100%; width: 100%;" allow="accelerometer; gyroscope; autoplay; encrypted-media; picture-in-picture;" allowfullscreen="true"></iframe></div>

</body> 
</html>
