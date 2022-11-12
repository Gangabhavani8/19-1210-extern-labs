# 19-1210-extern-labs
<!DOCTYPE html>
<html>
  <head>
    <title>Image Slider</title>
    <style>
      body {
        margin: 10px auto;
        text-align: center;
      }
      .content {
        max-width: 800px;
        text-align: left;
        margin: auto;
      }
      .simple-ss {
        width: 800px;
        height: 250px;
        background-color: #eeeeee;
        margin: auto;
        background-image: url("/uploads/media/default/0001/03/5bfad15a7fd24d448a48605baf52655a5bbe5a71.jpeg");
        animation-name: slide;
        animation-duration: 10s;
        animation-direction: normal;
        animation-timing-function: ease;
        animation-iteration-count: infinite;
      }
      @keyframes slide {
        0% {
          background-position: 0 0;
        }
        16.66% {
          background-position: 0 0;
        }
        33.32% {
          background-position: -800px 0;
        }
        49.98% {
          background-position: -800px 0;
        }
        66.64% {
          background-position: -1600px 0;
        }
        83.30% {
          background-position: -1600px 0;
        }
        100% {
          background-position: 0 0;
        }
      }
    </style>
  </head>
  <body>
    <div class="simple-ss"></div>
    <div class="content">
      <p>
        This is a proof-of-concept for a slideshow that doesn't use any Javascript. It does not have pages or left/right buttons etc.
      </p>
    </div>
  </body>
</html>![ext1](https://user-images.githubusercontent.com/118047985/201468595-4c64e113-d7cd-43ea-95e2-94602c756e87.jpeg)
![Ext2](https://user-images.githubusercontent.com/118047985/201468693-2e0293ba-9a19-4b45-9f94-fe7a8b2be848.jpeg)
