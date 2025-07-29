
		<a-scene
			mindar-image="imageTargetSrc: /targets.mind;"
			vr-mode-ui="enabled: false"
			device-orientation-permission-ui="enabled: false"
		>
			<a-camera position="0 0 0" look-controls="enabled: false"></a-camera>
			<a-entity mindar-image-target="targetIndex: 0">
				<a-plane src="bee.jpeg" position="0 0 0" height="1.5" width="1" rotation="0 0 0"></a-plane>
			</a-entity>
		</a-scene>

