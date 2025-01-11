
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Video Example</title>
</head>
<body>
  <h1>Video Example</h1>

  <!-- Video element -->
  <video id="myVideo" width="600" controls>
    <source src="333923407231242244.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>

  <!-- Video element 2 -->
  <video id="myVideo" width="600" controls>
    <source src="333735085892505603.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>





  

  <!-- Buttons to control the video -->
  <br>
  <button onclick="playVideo()">Play</button>
  <button onclick="pauseVideo()">Pause</button>

  <script>
    // Get the video element
    const video = document.getElementById('myVideo');

    // Function to play the video
    function playVideo() {
      video.play();
    }

    // Function to pause the video
    function pauseVideo() {
      video.pause();
    }
  </script>
</body>
</html>
