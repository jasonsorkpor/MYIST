Web Development & Design  
Crafting modern, responsive websites that balance functionality with aesthetics. BY YOURS TRULY(JASON)

Software Solutions  
Developing lightweight applications and tools tailored to client needs, from productivity apps to educational platforms.

Digital Learning  
Offering coding tutorials, workshops, and resources to help beginners and professionals sharpen their skills.

Creative Innovation  
Exploring intersections of technology and art, including interactive storytelling and creative writing enhanced by digital tools.

🌍 Mission
To make technology accessible, intuitive, and inspiring — enabling people to transform ideas into impactful digital experience
## About Mystic Technologies

**Mystic Technologies** is a forward‑thinking tech company dedicated to building innovative digital solutions that empower individuals and businesses. Founded with a vision to merge creativity and technology, Mystic specializes in:

- 🌐 **Web Development & Design** – Crafting modern, responsive websites that balance functionality with aesthetics.
- 💻 **Software Solutions** – Developing lightweight applications and tools tailored to client needs.
- 📚 **Digital Learning** – Offering coding tutorials, workshops, and resources to help beginners and professionals sharpen their skills.
- 🎨 **Creative Innovation** – Exploring intersections of technology and art, including interactive storytelling and creative writing enhanced by digital tools.

### Mission
To make technology accessible, intuitive, and inspiring — enabling people to transform ideas into impactful digital experiences.

### Vision
Mystic Technologies aims to become a hub for innovation in West Africa, nurturing talent and delivering solutions that compete globally.

### Contact
For collaborations, inquiries, or support, reach out via the contact form or directly at **[0506365564](tel:0506365564)**.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mystic Technologies</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f9f9f9;
      color: #333;
    }
    header {
      background: #4b0082;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    section {
      padding: 40px;
      max-width: 900px;
      margin: auto;
    }
    h2, h3 {
      color: #4b0082;
    }
    ul {
      list-style: none;
      padding: 0;
    }
    ul li {
      margin: 10px 0;
      padding: 10px;
      background: #eee;
      border-radius: 5px;
    }
    footer {
      background: #4b0082;
      color: #fff;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }
    a {
      color: #4b0082;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <h1>Mystic Technologies</h1>
    <p>Innovative Digital Solutions for Africa & Beyond</p>
  </header>

  <section id="company">
    <h2>About Mystic Technologies</h2>
    <p><strong>Mystic Technologies</strong> is a forward‑thinking tech company dedicated to building innovative digital solutions that empower individuals and businesses. Founded with a vision to merge creativity and technology, Mystic specializes in:</p>
    
    <ul>
      <li>🌐 <strong>Web Development & Design</strong> – Crafting modern, responsive websites that balance functionality with aesthetics.</li>
      <li>💻 <strong>Software Solutions</strong> – Developing lightweight applications and tools tailored to client needs.</li>
      <li>📚 <strong>Digital Learning</strong> – Offering coding tutorials, workshops, and resources to help beginners and professionals sharpen their skills.</li>
      <li>🎨 <strong>Creative Innovation</strong> – Exploring intersections of technology and art, including interactive storytelling and creative writing enhanced by digital tools.</li>
    </ul>

    <h3>Mission</h3>
    <p>To make technology accessible, intuitive, and inspiring — enabling people to transform ideas into impactful digital experiences.</p>

    <h3>Vision</h3>
    <p>Mystic Technologies aims to become a hub for innovation in West Africa, nurturing talent and delivering solutions that compete globally.</p>

    <h3>Contact</h3>
    <p>For collaborations, inquiries, or support, reach out via the contact form or directly at <strong><a href="tel:0506365564">0506365564</a></strong>.</p>
  </section>

  <footer>
    <p>&copy; 2026 Mystic Technologies. All rights reserved.</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>3D Website Demo</title>
  <style>
    body { margin: 0; }
    canvas { display: block; }
  </style>
</head>
<body>
  <!-- Three.js script -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
  <script>
    // Scene setup
    const scene = new THREE.Scene();
    const camera = new THREE.PerspectiveCamera(75, window.innerWidth/window.innerHeight, 0.1, 1000);

    const renderer = new THREE.WebGLRenderer();
    renderer.setSize(window.innerWidth, window.innerHeight);
    document.body.appendChild(renderer.domElement);

    // Add a cube
    const geometry = new THREE.BoxGeometry();
    const material = new THREE.MeshBasicMaterial({ color: 0x00ff00, wireframe: true });
    const cube = new THREE.Mesh(geometry, material);
    scene.add(cube);

    camera.position.z = 5;

    // Animation loop
    function animate() {
      requestAnimationFrame(animate);
      cube.rotation.x += 0.01;
      cube.rotation.y += 0.01;
      renderer.render(scene, camera);
    }
    animate();
  </script>
</body>
</html>
