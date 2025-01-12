 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Video Gallery</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      display: flex;
      flex-wrap: wrap;
      gap: 16px;
      justify-content: center;
    }
    .video-container {
      max-width: 300px;
    }
    video {
      width: 100%;
      height: auto;
    }
  </style>
</head>
<body>
  <div id="videoGallery"></div>




  <script>

<audio id="my-audio" src="audio.mp3"></audio>

   
    // Array of video sources
    const videos = [
      { src: "333923407231242244.mp4", title: "Tornado" },
      { src: "333735085892505603.mp4", title: "Beyonce and Macaulay Culkin" },
      { src: "333628961587437568.mp4", title: "Beyonce snd Michael Jackson" },
     
{ src: "333608505539035140.mp4", title: "Beyonce Smokes" },
      
{ src: "333606574510817289.mp4", title: "Beyonce and Blue Earrings" },
      
{ src: "333594070342651905.mp4", title: "Beyonce and Mud" },
      
{ src: "332834079352217606.mp4", title: "Teddy Bears Rock" },
      
{ src: "video1.mp4", title: "Video 1" },
      

{ src: "video1.mp4", title: "Video 1" },
      

{ src: "video1.mp4", title: "Video 1" },

{ src: "video1.mp4", title: "Video 1" },
      
{ src: "video1.mp4", title: "Video 1" },
      
{ src: "video1.mp4", title: "Video 1" },
      
{ src: "video1.mp4", title: "Video 1" },
      
{ src: "video1.mp4", title: "Video 1" },
      
{ src: "video1.mp4", title: "Video 1" },
      

{ src: "video1.mp4", title: "Video 1" },
      

{ src: "video1.mp4", title: "Video 1" },
      
     
{ src: "video1.mp4", title: "Video 1" },


{ src: "video1.mp4", title: "Video 1" },
      
{ src: "video1.mp4", title: "Video 1" },
      
     
{ src: "video1.mp4", title: "Video 1" },

{ src: "video1.mp4", title: "Video 1" },

{ src: "video1.mp4", title: "Video 1" },
      
{ src: "video1.mp4", title: "Video 1" },


     { src: "video1.mp4", title: "Video 1" },
      
     


     
    ];

    // Reference to the video gallery container
    const videoGallery = document.getElementById("videoGallery");

 // Dynamically create video elements
    videos.forEach(video => {
      const container = document.createElement("div");
      container.classList.add("video-container");

      const videoElement = document.createElement("video");
      videoElement.src = video.src;
      videoElement.controls = true;

      const title = document.createElement("p");
      title.textContent = video.title;

      container.appendChild(videoElement);
      container.appendChild(title);
      videoGallery.appendChild(container);
    });




// Synchronize audio with the video

   const audio = document.getElementById("my-audio");
         

videos.addEventListener("play", () => {
    audio.play();
  });

   videos.addEventListener("pause", () => {
    audio.pause();
    
  });


   
videos.addEventListener("ended", () => {
    audio.pause();
    audio.currentTime = 0;
  });






  
  </script>
</body>
</html>
