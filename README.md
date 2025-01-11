

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AI Videos</title>
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
  <h1>Tornado</h1>
  
  <!-- Video element -->
  <video id="myVideo" width="600" controls>
    <source src="333923407231242244.mp4" type="video/mp4">

    <audio id="my-audio" src="tornado_sound_1.mp3"></audio>
    
    Your browser does not support the video tag.
  </video>

  <!-- Buttons to control the video -->
  <br>
  <button onclick="playVideo()">Play</button>
  <button onclick="pauseVideo()">Pause</button>


<h1>Beyonce and Macaulay Culkin </h1>
  
  <!-- Video element -->
  <video id="myVideo_2" width="600" controls>
    <source src="333735085892505603.mp4" type="video/mp4">
    
    Your browser does not support the video tag.
  </video>

  <!-- Buttons to control the video -->
  <br>
  <button onclick="playVideo_2()">Play</button>
  <button onclick="pauseVideo_2()">Pause</button>

<h1>Beyonce and Michael Jackson</h1>
  
  <!-- Video element -->
  <video id="myVideo_3" width="600" controls>
    <source src="333628961587437568.mp4" type="video/mp4">
    
    Your browser does not support the video tag.
  </video>

  <!-- Buttons to control the video -->
  <br>
  <button onclick="playVideo_3()">Play</button>
  <button onclick="pauseVideo_3()">Pause</button>



<h1>Beyonce Smokes</h1>
  
  <!-- Video element -->
  <video id="myVideo_4" width="600" controls>
    <source src="333608505539035140.mp4" type="video/mp4">
    
    Your browser does not support the video tag.
  </video>

  <!-- Buttons to control the video -->
  <br>
  <button onclick="playVideo_4()">Play</button>
  <button onclick="pauseVideo_4()">Pause</button>



  <h1>Beyonce and Blue Earrings</h1>
  
  <!-- Video element -->
  <video id="myVideo_5" width="600" controls>
    <source src="333606574510817289.mp4" type="video/mp4">
    
    Your browser does not support the video tag.
  </video>

  <!-- Buttons to control the video -->
  <br>
  <button onclick="playVideo_5()">Play</button>
  <button onclick="pauseVideo_5()">Pause</button>

  
<h1>Beyonce and Mud</h1>
  
  <!-- Video element -->
  <video id="myVideo_6" width="600" controls>
    <source src="333594070342651905.mp4" type="video/mp4">
    
    Your browser does not support the video tag.
  </video>

  <!-- Buttons to control the video -->
  <br>
  <button onclick="playVideo_6()">Play</button>
  <button onclick="pauseVideo_6()">Pause</button>


  


  <h1>Teddy Bears Rock</h1>
  
  <!-- Video element -->
  <video id="myVideo_7" width="600" controls>

<audio id="my-audio_7" src="The_Street_Beat_3.mp3"></audio>

    
    <source src="332834079352217606.mp4" type="video/mp4">
    
    Your browser does not support the video tag.
  </video>

  <!-- Buttons to control the video -->
  <br>
  <button onclick="playVideo_7()">Play</button>
  <button onclick="pauseVideo_7()">Pause</button>













  
  
  <script>
    
    // Get the video element
    const video = document.getElementById('myVideo');

const video_2 = document.getElementById('myVideo_2');
const video_3 = document.getElementById('myVideo_3');
const video_4 = document.getElementById('myVideo_4');

const video_5 = document.getElementById('myVideo_5');

const video_6 = document.getElementById('myVideo_6');

const video_7 = document.getElementById('myVideo_7');

const audio = document.getElementById("my-audio");
    
    const audio_7 = document.getElementById("my-audio_7");

    
    
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
    video.addEventListener("pause", () => audio.pause()



    

    // Function to play the video
    function playVideo_2() {
      video_2.play();
    }

    // Function to pause the video
    function pauseVideo_2() {
      video_2.pause();
    }

// Function to play the video
    function playVideo_3() {
      video_3.play();
    }

    // Function to pause the video
    function pauseVideo_3() {
      video_3.pause();
    }

// Function to play the video
    function playVideo_4() {
      video_4.play();
    }

    // Function to pause the video
    function pauseVideo_4() {
      video_4.pause();
    }

// Function to play the video
    function playVideo_5() {
      video_5.play();
    }

    // Function to pause the video
    function pauseVideo_5() {
      video_5.pause();
    }

// Function to play the video
    function playVideo_6() {
      video_6.play();
    }

    // Function to pause the video
    function pauseVideo_6() {
      video_6.pause();
    }

// Function to play the video
    function playVideo_7() {
      video_7.play();
    }

    // Function to pause the video
    function pauseVideo_7() {
      video_7.pause();
    }

video_7.addEventListener("click", () => {
    if (audio_7.paused) {
      audio_7.play();
    }
  });

  // Stop audio when the video ends
  video_7.addEventListener("ended", () => {
    audio_7.pause();
    audio_7.currentTime = 0;
  });

video_7.addEventListener("play", () => audio_7.play());
    video_7.addEventListener("pause", () => audio_7.pause());
    


    
    
    
    
  </script>
</body>

</html>
