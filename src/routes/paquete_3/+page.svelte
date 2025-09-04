
		<a-scene
			mindar-image="imageTargetSrc: /inv_leon.mind;"
			vr-mode-ui="enabled: false"
			device-orientation-permission-ui="enabled: false"
		>
			<a-camera position="0 0 0" look-controls="enabled: false"></a-camera>
					 <a-assets>
    <!-- svelte-ignore a11y_media_has_caption -->
    <video
          id="videoId"
          muted
          loop
          playsinline
          webkit-playsinline
        >
          <!-- HEVC video for safari support -->
          <source src="leon_ios.mov" type="video/mp4;codecs=hvc1">
          <!-- WEBM video for chrome and firefox -->
          <!-- <source src="https://video-src-url/video.webm" type="video/webm" />  -->
        </video>
  </a-assets>
			<a-entity mindar-image-target="targetIndex: 0">
				


  <!-- Using the asset management system. -->


  <!-- Defining the URL inline. Not recommended but more comfortable for web developers. -->
  <a-video width="1.9" height="2.1"  src="/inv_leon.mp4"></a-video>
			</a-entity>
 
		</a-scene>