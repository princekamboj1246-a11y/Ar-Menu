<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no" />
    <title>AR Restaurant Menu</title>
    <!-- Stable A-Frame & AR.js Libraries -->
    <script src="https://aframe.io/releases/1.3.0/aframe.min.js"></script>
    <script src="https://raw.githack.com/AR-js-org/AR.js/master/aframe/build/aframe-ar.js"></script>
  </head>
  <body style="margin: 0px; overflow: hidden;">
    <a-scene embedded arjs="sourceType: webcam; debugUIEnabled: false;">
      <a-marker preset="hiro">
        <a-box position="0 0.5 0" material="color: red;"></a-box>
        <a-text value="Special Burger - $5" position="-0.8 1.2 0" color="yellow"></a-text>
      </a-marker>
      <a-entity camera></a-entity>
    </a-scene>
  </body>
</html>
