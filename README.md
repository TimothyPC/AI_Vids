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
    // Array of video sources
    const videos = [
      { src: "333923407231242244.mp4", title: "Video 1" },
      { src: "333735085892505603.mp4", title: "Video 2" },
      { src: "333628961587437568.mp4", title: "Video 3" },
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
  </script>
</body>
</html>
