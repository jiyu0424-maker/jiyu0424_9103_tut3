<h1 align="center">🎬 Quiz 8 — <em>Cloud Atlas</em>: Imaging & Coding Technique Exploration</h1>

---

## 🌌 Part 1: Imaging Technique Inspiration

One inspiring visual technique in *Cloud Atlas* (2012) is its **reflective symmetry with vibrant lighting**.  
Throughout the film, reflections in **water, glass, and futuristic architecture** produce mesmerizing compositions that merge natural and digital aesthetics.  
This use of *mirroring and light balance* gives each frame depth, contrast, and emotion.  

In a web-based interactive project, this technique can inspire compositions where elements respond to user input symmetrically — for instance, **duplicating motion, color, or form** across an invisible axis, creating a sense of harmony and visual rhythm.

---

<h3 align="center">✨ Visual References from <em>Cloud Atlas</em></h3>

<p align="center">
  <img src="https://tse2.mm.bing.net/th/id/OIP.7OpvZeO345Kz2JX8aY-1BQHaDJ?cb=12&pid=Api" width="70%" alt="Cloud Atlas neon reflection scene">
</p>

<p align="center">
  <img src="https://tse3.mm.bing.net/th/id/OIP.Dn15wmtw8Cf6X8GzTJHUJQHaEK?cb=12&pid=Api" width="70%" alt="Cloud Atlas reflection symmetry scene">
</p>

**Image Reference:**  
- [Cinema & Arquitetura: Cloud Atlas (ArchDaily Brasil)](https://www.archdaily.com.br/br/01-106201/cinema-and-arquiteura-cloud-atlas)  

---

## 💡 Part 2: Coding Technique Exploration

To recreate *Cloud Atlas*’s visual reflection digitally, we can use **mirror and kaleidoscopic transformations** in web graphics.  

By applying a horizontal flip transform in JavaScript or p5.js, we can mirror visuals dynamically.  
For instance, using `context.scale(-1, 1)` before drawing operations reflects the canvas horizontally, producing symmetry that responds to user movement or input.  

For more advanced *neon-reflective* results, WebGL shaders (as used in Three.js or GLSL) can simulate glowing mirrored surfaces and animated kaleidoscopic reflections — perfect for an immersive, futuristic web aesthetic.

---

<h3 align="center">🧠 Coding Techniques & Examples</h3>

| Technique | Example / Demo | Description |
|------------|----------------|--------------|
| **Canvas Flip Transformation** | [StackOverflow Example](https://stackoverflow.com/questions/32177213/canvasrenderingcontext2d-flip-transformation) | Demonstrates using `scaleX(-1)` to mirror the HTML canvas horizontally. |
| **WebGL Mirror (Three.js)** | [CodePen Demo by sjcobb](https://codepen.io/sjcobb/pen/JWrXeq) | Real-time mirror and reflection rendering using Three.js and shaders. |
| **Kaleidoscope Shader** | [CodePen Demo by Darko Komericki](https://codepen.io/darko-komericki/pen/abQbpOx) | Shader-based kaleidoscope with neon tones and symmetrical reflections. |
| **CSS Image Flip** | [W3Schools Flip Example](https://www.w3schools.com/howto/howto_css_flip_image.asp) | Basic CSS transform mirror technique using `transform: scaleX(-1)`. |
| **CSS/JS Image Flipping Tutorial** | [PQINA Blog](https://pqina.nl/blog/flipping-images-with-css-and-javascript/) | Explains image flipping using both CSS and JavaScript with visual results. |