<!DOCTYPE html>
<html>
<head>
  <!-- I include the Three.js library -->
  <script src="https://cdn.jsdelivr.net/npm/three@0.119.1/build/three.js"></script>
  <!-- I set the margin of the body to 0 and display the canvas block -->
  <style>
    body { margin: 0; }
    canvas { display: block; }
  </style>
</head>
<body>
  <!-- I define my JavaScript code -->
  <script>
    // I create the scene
    const scene = new THREE.Scene();

    // I create the camera
    const camera = new THREE.PerspectiveCamera(75, window.innerWidth / window.innerHeight, 0.1, 1000);
    camera.position.z = 5;

    // I create the renderer
    const renderer = new THREE.WebGLRenderer();
    renderer.setSize(window.innerWidth, window.innerHeight);
    document.body.appendChild(renderer.domElement);

    // I create the vertices for the polygon
    const vertices = [
      new THREE.Vector3(-1, 1, 1),
      new THREE.Vector3(1, 1, 1),
      new THREE.Vector3(0, -1, 1),
      new THREE.Vector3(-1, -1, 1),
      new THREE.Vector3(1, -1, 1)
    ];

    // I create a line from each vertex to the next
    for (let i = 0; i < vertices.length; i++) {
      const start = vertices[i];
      const end = vertices[(i + 1) % vertices.length];
      const lineGeometry = new THREE.Geometry();
      lineGeometry.vertices.push(start, end);
      const lineMaterial = new THREE.LineBasicMaterial({ color: 0xff0000 });
      const line = new THREE.Line(lineGeometry, lineMaterial);
      scene.add(line);
    }

    // I animate the polygon
    function animate() {
      requestAnimationFrame(animate);
      scene.rotation.x += 0.01;
      scene.rotation.y += 0.01;
      renderer.render(scene, camera);
    }

    // I start the animation
    animate();
  </script>
</body>
</html>
