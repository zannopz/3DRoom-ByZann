<!DOCTYPE html>
<html lang="en" >
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>3D First Person Art Gallery - No Javascript!</title>
  <link rel="stylesheet" href="./style.css">
  

</head>
<body>
<!-- partial:index.partial.html -->
<input type="checkbox" id="lightswitch" accesskey="l" />
<input type="checkbox" checked="checked" id="wall4" accesskey="x" />

<label></label><label></label><label></label><label></label><label></label><label></label><label></label><label></label><label></label><label></label><label></label><label></label><label></label><label></label>
<label class="p1hover pointer" title="Tap to zoom - double tap to view code">
  <a relhref="https://www.youtube.com/watch?v=jzD_yyEcp0M" target="_blank"></a>
  <label class="pointer"></label>
</label>
<label class="p1hover pointer" title="Tap to zoom - double tap to view code">
  <a relhref="https://www.youtube.com/watch?v=jzD_yyEcp0M" target="_blank"></a>
  <label class="pointer"></label>
</label>
<label class="p1hover pointer" title="Tap to zoom - double tap to view code">
  <a relhref="https://www.youtube.com/watch?v=jzD_yyEcp0M" target="_blank"></a>
  <label class="pointer"></label>
</label>
<label></label>
<label class="p2hover pointer" title="Tap to zoom - double tap to view code">
  <a relhref="https://www.youtube.com/watch?v=jzD_yyEcp0M" target="_blank"></a>
  <label class="pointer"></label>
</label>
<label class="p2hover pointer" title="Tap to zoom - double tap to view code">
  <a relhref="https://www.youtube.com/watch?v=jzD_yyEcp0M" target="_blank"></a>
  <label class="pointer"></label>
</label>
<label class="p2hover pointer" title="Tap to zoom - double tap to view code">
  <a relhref="https://www.youtube.com/watch?v=jzD_yyEcp0M" target="_blank"></a>
  <label class="pointer"></label>
</label>
<label></label>
<label class="p3hover pointer" title="Tap to zoom - double tap to view code">
  <a relhref="https://www.youtube.com/watch?v=jzD_yyEcp0M" target="_blank"></a>
  <label class="pointer"></label>
</label>
<label class="p3hover pointer" title="Tap to zoom - double tap to view code">
  <a relhref="https://www.youtube.com/watch?v=jzD_yyEcp0M" target="_blank"></a>
  <label class="pointer"></label>
</label>
<label class="p3hover pointer" title="Tap to zoom - double tap to view code">
  <a relhref="https://www.youtube.com/watch?v=jzD_yyEcp0M" target="_blank"></a>
  <label class="pointer"></label>
</label>
<label class="pointer turn" for="wall4" title="Rotate right"></label>
<label></label><label></label><label></label><label></label><label></label><label></label><label></label><label></label><label></label><label></label><label></label><label></label><label></label>

<z>
  <x>
    <y>
      <floor></floor>
      <ceiling></ceiling>
      <wall1>
        <painting>
          <img src="IMG/14.jpg" alt="" style="height: 1044px;">
            <p>Kita memang punya keinginan<br />
            
            <small>Zann_Opz</small>
          </p>
        </painting>
      </wall1>
      <wall2>
        <painting>
        </body>
        <video
            id="background-video"
            src="MP4/video.mp4"
            autoplay=""
            loop=""
            
            style="position: fixed; object-fit: cover"
            ></video>
          <source src="MP4/video.mp4" type="video/mp4" />
          
            <td>
                    <style type="text/css">
                            #background-video {
                                    height: 132vh;
                                    width: 98vw;
                                    object-fit: cover;
                                    position: fixed;
                                    left: 0;
                                    right: 0;
                                    top: 0
                                    ;
                                    bottom: 0;
                                    z-index: -1;
                            }
                    </style>
          <p>
             Sebenarnya tidak ada yang sulit<br />
            Mengeluhnya saja berlebihan<br />
            <small>Zann_Opz</small>
          </p>
        </painting>
      </wall2>
      <wall3>
        <painting>
          <img src="IMG/12.jpg" alt="" style="height: 961px;">
          <p>
            Demi masa depan yang cerah<br />
            Malas jangan dipelihara<br />
            <small>Zann_Opz</small>
          </p>
        </painting>
      </wall3>
      <wall4>

        <notice>

          <a title="Buy the landscape - CSS Art for your wall!" target="_blank" rel="noopener" href="https://www.youtube.com/watch?v=jzD_yyEcp0M">Buy the landscape</a>
          <a title="Buy the still life - CSS Art for your wall!" target="_blank" rel="noopener" href="https://www.youtube.com/watch?v=jzD_yyEcp0M">Buy the still life</a>
          <a title="Buy the portrait - CSS Art for your wall!" target="_blank" rel="noopener" href="https://www.youtube.com/watch?v=jzD_yyEcp0M">Buy the portrait</a>
        </notice>
        <door>
          <a target="_blank" title="Exit" rel="noopener" href="https://www.instagram.com/zann_opz/">
          </a>
        </door>

        <label for="lightswitch" class="pointer" title="Switch"></label>
        <fireexit>
          <i></i>
          <i></i>
        </fireexit>
      </wall4>
    </y>
  </x>
</z>

<label class="turnback" title="Rotate left" for="wall4"></label>
<!-- partial -->
  <script  src="./script.js"></script>

</body>
</html>

<script>
  window.addEventListener('click', function() {
      document.querySelectorAll('video').forEach(video => {
          video.muted = false;
          video.play();
      });
  });
</script>
