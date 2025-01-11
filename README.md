

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

<h1 id="heading"> </h1>
<script>
  document.getElementById("heading").textContent = 'Tornado';
</script>

var numSelect = 1;

  
<br>
  
<style>
    body {
      background-color: black;
      color: white;
    }
    .dark-mode {
      background-color: white;
      color: black;
    }
  </style>

  
</head>
<body>
  <h1 id="heading"> </h1>

  <!-- Video element -->
  <video id="myVideo" width="600" controls>
    

    Your browser does not support the video tag.
  </video>

  <!-- Buttons to control the video -->
  <br>
  <button onclick="playVideo()">Play</button>
  <button onclick="pauseVideo()">Pause</button>


  <!-- Buttons to control Selection -->
  <br>
  <button onclick="prevVideo()">Previous</button>
  <button onclick="nextVideo()">Next</button>



  
  
  <script>
    
    // Get the video element
    const video = document.getElementById('myVideo');
    
const audio = document.getElementById("my-audio");
    
    
    // Function to play the video
    function playVideo() {
      video.play();
    }

    // Function to pause the video
    function pauseVideo() {
      video.pause();
    }

video.addEventListener("click", () => {
    if (audio.paused) {
      audio.play();
    }
  });

  // Stop audio when the video ends
  video.addEventListener("ended", () => {
    audio.pause();
    audio.currentTime = 0;
  });

video.addEventListener("play", () => audio.play());
    video.addEventListener("pause", () => audio.pause());


    // Function to play the video
    function prevVideo() {

         <script>
  document.getElementById("heading").textContent = 'Tornado_2';
</script>

      <audio id="my-audio"       src="tornado_sound_1.mp3"></audio>
    
    <source src="333923407231242244.mp4" type="video/mp4">
        
      video.play();

  }

    // Function to pause the video
    function nextVideo() {
      
    }


    
    
  </script>
</body>

</html>
