<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <title>Demo: Page Visibility API</title>
</head>
<body>
  <video src="YOUR_LINK_HERE" id="video" muted="" autoplay="" width="300"></video>
  <button onclick="togglePictureInPicture()">Toggle Picture in Picture</button>
  
  <p>you choose your video by going to the code and changing the YOUR_LINK_HERE with your video link</p>
  
<script>
function togglePictureInPicture() {
  if (document.pictureInPictureElement) {
      document.exitPictureInPicture();
  } else {
    if (document.pictureInPictureEnabled) {
      video.requestPictureInPicture();
    }
  }
}
</script>
</body>
</html>
