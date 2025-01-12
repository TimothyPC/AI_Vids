<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Video Gallery with External Audio</title>
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
    video, audio {
      width: 100%;
    }
  </style>
</head>
<body>
  <div id="videoGallery"></div>

  <script>
    // Array of video and optional audio sources
    const media = [
      { videoSrc: "333923407231242244.mp4", audioSrc: "tornado_sound_1.mp3", title: "Tornado" },
      { videoSrc: "video2.mp4", title: "Video 2 without Audio" },
      { videoSrc: "video3.mp4", audioSrc: "audio3.mp3", title: "Video 3 with Audio" },
    ];

    // Reference to the video gallery container
    const videoGallery = document.getElementById("videoGallery");

    // Create video and audio elements dynamically
    media.forEach(item => {
      const container = document.createElement("div");
      container.classList.add("video-container");

      const videoElement = document.createElement("video");
      videoElement.src = item.videoSrc;
      videoElement.controls = true;

      const title = document.createElement("p");
      title.textContent = item.title;

      container.appendChild(videoElement);
      container.appendChild(title);

      // If there's an associated audio file, create an audio element
      if (item.audioSrc) {
        const audioElement = document.createElement("audio");
        audioElement.src = item.audioSrc;

        // Synchronize audio with the video
        videoElement.addEventListener("play", () => {
          audioElement.play();
        });

        videoElement.addEventListener("pause", () => {
          audioElement.pause();
        });

       videoElement.addEventListener("ended", () => {
    audioElement.pause();
    audioElement.currentTime = 0;
  });
        

        audioElement.controls = true; // Optional: Add controls for the audio
        container.appendChild(audioElement);
      }

      videoGallery.appendChild(container);
    });
  </script>
  
</body>
</html>


      
     





















   

