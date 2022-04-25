
<html>
  <head>
    <script src="https://aframe.io/releases/1.3.0/aframe.min.js"></script>
    <script src="https://cdn.jsdelivr.net/gh/donmccurdy/aframe-extras@v6.1.1/dist/aframe-extras.min.js"></script>
    <script src="https://rawgit.com/Ctrl-Alt-Zen/aframe-mobile-controls/master/components/twoway-motion/twoway-motion.js"></script>
    <script src="https://raw.githubusercontent.com/n5ro/aframe-extras/master/dist/aframe-extras.misc.min.js"></script>
    <script src="https://cdn.jsdelivr.net/gh/n5ro/aframe-physics-system@v$npm_package_version/dist/aframe-physics-system.min.js"></script>
    <script src="http://supereggbert.github.io/aframe-aobake-component/dist/build.js"></script>
        <script src="https://unpkg.com/aframe-particle-system-component@1.0.x/dist/aframe-particle-system-component.min.js"></script>
      <script src="https://unpkg.com/aframe-sprite-particles-component@^0.5.0/aframe-sprite-particles-component.js"></script>
    <script src="https://raw.githubusercontent.com/AdaRoseCannon/aframe-xr-boilerplate/glitch/simple-navmesh-constraint.js"></script>
    <script src="https://threejs.org/examples/js/deprecated/Geometry.js"></script>

   </head>
  <body>
    <a-scene>
     
      
      <a-entity light="color: #f06265; intensity: 0.5; type: spot; distance: 5;" position="-0.616 2.152 -1.235" rotation="-89.995 -0.001 0" ></a-entity>
      
      <a-entity light="type: ambient"></a-entity>
 
     
      
      <a-entity light="distance: 1; intensity: 0.3; type: point" position="3.086 0.786 -2.211"></a-entity>
      
    

      
      
<a-entity gltf-model="https://raw.githubusercontent.com/jujubeesloco/VinuAframe/master/vinustation.glb" position="0.35381 0.7 -1.71235" shadow="receive: true; cast: true" scale="3 3 3"></a-entity>
      
     
<a-entity light="distance: 1; intensity: 0.3; type: point" position="3.1 1.277 -1.757"></a-entity>
      
      <a-entity light="distance: 1; intensity: 0.3; type: point" position="3.1 1.277 -0.751"></a-entity>
      
      <a-entity light="distance: 1; intensity: 0.3; type: point" position="1.033 1.277 -1.757"></a-entity>
      
      <a-entity light="distance: 1; intensity: 0.3; type: point" position="1.033 1.277 -0.751"></a-entity>
      
      <a-entity light="distance: 1; intensity: 0.3; type: point" position="5.149 1.277 -1.757"></a-entity>
      
      <a-entity light="distance: 1; intensity: 0.3; type: point" position="5.149 1.277 -0.751"></a-entity>
      
      <a-entity light="distance: 1; intensity: 0.3; type: point" position="7.219 1.277 -1.757"></a-entity>
      
      <a-entity light="distance: 1; intensity: 0.3; type: point" position="7.219 1.277 -0.751"></a-entity>
      
      <a-entity light="distance: 1; intensity: 0.3; type: point" position="9.329 1.277 -1.757"></a-entity>
      
      <a-entity light="distance: 1; intensity: 0.3; type: point" position="9.329 1.277 -0.751"></a-entity>
      
      <a-entity light="distance: 1; intensity: 0.3; type: point" position="11.383 1.277 -1.757"></a-entity>
      
      <a-entity light="distance: 1; intensity: 0.3; type: point" position="11.383 1.277 -0.751"></a-entity>
      
      <a-entity light="distance: 1; intensity: 0.3; type: point" position="13.477 1.277 -1.757"></a-entity>
      
      <a-entity light="distance: 1; intensity: 0.3; type: point" position="13.477 1.277 -0.751"></a-entity>
      
      <a-entity light="distance: 1; intensity: 0.3; type: point" position="15.522 1.277 -1.757"></a-entity>
      
      <a-entity light="distance: 1; intensity: 0.3; type: point" position="15.522 1.277 -0.751"></a-entity>
      
      <a-entity light="distance: 1; intensity: 0.3; type: point" position="17.578 1.277 -1.757"></a-entity>
      
      <a-entity light="distance: 1; intensity: 0.3; type: point" position="17.578 1.277 -0.751"></a-entity>
      
      <a-entity light="distance: 1; intensity: 0.3; type: point" position="19.661 1.277 -1.757"></a-entity>
      
      <a-entity light="distance: 1; intensity: 0.3; type: point" position="19.661 1.277 -0.751"></a-entity>
      
      
      <a-entity geometry="primitive: plane" rotation="-30.006945646591472 -90.00021045914971 0" scale="0.24114 0.16716 1" position="19.63137 1.19682 -1.23415" material="src: https://raw.githubusercontent.com/jujubeesloco/VinuAframe/main/VinuCode.mp4"></a-entity>
      

      <a-entity geometry="primitive: sphere; radius: 0.3;" position="19.206 1.594 -1.250" material="offset:  [object Object];  opacity:  0.5;  repeat:  [object Object];  ambientOcclusionTextureOffset:  [object Object];  ambientOcclusionTextureRepeat:  [object Object];  displacementTextureOffset:  [object Object];  displacementTextureRepeat:  [object Object];  metalnessTextureOffset:  [object Object];  metalnessTextureRepeat:  [object Object];  normalScale:  [object Object];  normalTextureOffset:  [object Object];  normalTextureRepeat:  [object Object];  roughnessTextureOffset:  [object Object];  roughnessTextureRepeat:  [object Object]"></a-entity>
      
    <a-entity geometry="primitive: sphere; radius: 400" material="src: https://cdn.eso.org/images/publicationjpg/eso0932a.jpg; side: back;" rotation="13.337 152.315 162.420" ></a-entity>
      
      
      
      
      <a-entity nav-mesh geometry="primitive: plane; height: 10; width: 10" position="9.510 0 -1.293" scale="2 0.055 1" rotation="-90 0 0"></a-entity>
     
    
      <a-entity id="rig" movement-controls="constrainToNavMesh: true" twoway-motion="nonMobileLoad: false" trackpad-controls="" position="1.297 0 -1.224">
    <a-entity id="camera" camera="" position="0 1.6 0" look-controls="" twoway-motion="" rotation="-12.032113697747292 -4.9274370381250785 0" data-aframe-inspector-original-camera=""></a-entity>

      
     
      <a-sky color="#000000"></a-sky>
    </a-scene>
  </body>
</html>
