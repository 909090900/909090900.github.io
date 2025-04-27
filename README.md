<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Ver Canal en Vivo</title>
  <style>
    body { background: #000; margin: 0; padding: 0; display: flex; justify-content: center; align-items: center; height: 100vh; }
    video { width: 90%; height: auto; border: 2px solid #fff; }
  </style>
</head>
<body>

<video id="video" controls autoplay></video>

<script src="https://cdn.jsdelivr.net/npm/hls.js@latest"></script>
<script>
  var video = document.getElementById('video');
  var videoSrc = 'http://181.78.82.6:46090/play/a00q/index.m3u8';

  if (Hls.isSupported()) {
    var hls = new Hls();
    hls.loadSource(videoSrc);
    hls.attachMedia(video);
    hls.on(Hls.Events.MANIFEST_PARSED,function() {
      video.play();
    });
  }
  else if (video.canPlayType('application/vnd.apple.mpegurl')) {
    video.src = videoSrc;
    video.addEventListener('loadedmetadata',function() {
      video.play();
    });
  }
</script>

</body>
</html>







 
